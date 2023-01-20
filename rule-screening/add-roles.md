---
description: Add roles to the rule screening menu.
---

# Setting Up Roles

When a user accepts the rules, they are automatically assigned the roles you have set. It is a simple yet effective way to remove less advanced spam bots from your server without impacting the experiences of other users.

GateKeeper version 3 and onward **supports auto-role features without having rule screening enabled** - however, we don't recommend using a community server without rule screening as you lose the protection against spam bots which it provides.

{% tabs %}
{% tab title="Add Roles" %}
```
/autorole add-role <role> <invite_url(optional)>
```



Adding roles is quite simple.

Just type the **above command** and hit enter. The bot will run a couple checks to ensure it has the correct permissions and then respond with a confirmation message or the steps to fix any problems with setup.

We recommend using the list roles command to confirm the role has been setup correctly, but this isn't required for the feature to work.

#### Bonus Roles ![GateKeeper Plus Feature](https://img.shields.io/badge/GateKeeper%20Plus-5865F2?style=flat)

* You can assign up to **5 roles** per server and if you are a **GateKeeper Plus** subscriber, you get an **additional 10 roles** for a total of 15 roles.

#### Invite Specific Roles ![GateKeeper Plus Feature](https://img.shields.io/badge/GateKeeper%20Plus-5865F2?style=flat)

* If you are a **GateKeeper Plus** subscriber, you can add a different selection of roles depending on the invite URL a user used.
{% endtab %}

{% tab title="Remove Roles" %}
<pre><code><strong>/autorole remove-role &#x3C;role> &#x3C;invite_url(optional)>
</strong></code></pre>

When you remove a role, it will be deducted from the total number of auto-roles you have assigned.

#### Remove All Roles

```
/autorole remove-all
```

* Removes all roles to be added to the current server.
{% endtab %}

{% tab title="List Roles" %}
```
/autorole list-roles
```



Listing roles is an effective way to ensure all the roles you have set have been added successfully.&#x20;

When the hierarchy of roles is changed, if a role is placed above the bot's own, it will automatically be removed. If a role you added doesn't show up here, please [contact the support server](https://support.gatekeeperbot.net/).
{% endtab %}
{% endtabs %}

