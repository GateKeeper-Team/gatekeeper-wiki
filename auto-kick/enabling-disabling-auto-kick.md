# Setting Up Auto Kick

Please ensure you have enabled rule screening before using the command, without doing so will cause unexpected results. The commands to configure auto kick can be found below, to reconfigure the settings you simply need to re-enter the `/autokick enable` command.

{% tabs %}
{% tab title="Enable and Edit" %}
```
/autokick enable <grace_period> <message(optional)> <use_embed(optional)>
```



When enabling autokick you are provided a couple of different options to tweak your user's experience.

The grace period is the number of hours you want a user to remain in the server before being kicked should they not accept the rules. The message is a custom message the user is DM'd when they are kicked and the final option toggles if the message is embedded or not.

We recommend sending the invite link in the message in case the user would like to rejoin.

> You can assign a grace period of up to **48 hours** with **GateKeeper Standard**

#### Wait up to a Week ![GateKeeper Plus Feature](https://img.shields.io/badge/GateKeeper%20Plus-5865F2?style=flat)

* **GateKeeper Plus** subscribers can set a **grace period of up to seven days** instead of **two days**.
{% endtab %}

{% tab title="Disable" %}
```
/autokick disable
```



This command will disable auto kick in your server.
{% endtab %}

{% tab title="Show Config" %}
```
/autokick show-config
```



Displays the current configuration of auto kick within your server. If a message is configured, then an example message will also be sent.
{% endtab %}
{% endtabs %}

