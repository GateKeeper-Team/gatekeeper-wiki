# Setting Up Channel Messages

The welcome message functionality makes GateKeeper send a message to a channel when a user joins your server and accepts the rule screening (if it is enabled).

{% tabs %}
{% tab title="Enable and Edit" %}
```
/welcome enable <channel>
```



Adding a welcome message is a really easy process! To start, type the command along with the channel it should be sent to and then select the option you wish to use: an embedded message or a plain message. After selecting this option, a modal will open and ask you for the rest of the relevant information.



#### Custom Fields

* You can add custom fields to your message which are dynamically added when the message is sent.

<table><thead><tr><th>Field</th><th></th><th data-type="checkbox">Works In Title</th><th data-hidden></th></tr></thead><tbody><tr><td>{username}</td><td>User's Username</td><td>true</td><td></td></tr><tr><td>{nickname}</td><td>User's Nickname</td><td>true</td><td></td></tr><tr><td>{usernameMention}</td><td>Mentions Username</td><td>false</td><td></td></tr><tr><td>{serverName}</td><td>Server's Name</td><td>true</td><td></td></tr><tr><td>{serverCount}</td><td>Server's Member Count</td><td>true</td><td></td></tr><tr><td>{currentTime}</td><td>Time the User Joined</td><td>true</td><td></td></tr><tr><td>{timeStampWithDate}</td><td>Time And Date</td><td>false</td><td></td></tr><tr><td>{shortDate}</td><td>Short Date</td><td>false</td><td></td></tr><tr><td>{longDate}</td><td>Long Date</td><td>false</td><td></td></tr><tr><td>{timeStamp}</td><td>Time</td><td>false</td><td></td></tr><tr><td>{timeSinceJoin}</td><td>Time Since the User Joined</td><td>false</td><td></td></tr></tbody></table>



#### Custom Image Links ![GateKeeper Plus Feature](https://img.shields.io/badge/GateKeeper%20Plus-5865F2?style=flat)

* Want to use an image link from a provider other than Imgur? Well, you can! **GateKeeper Premium** subscribers can use **any link** they wish.
{% endtab %}

{% tab title="Disable" %}
```
/welcome disable
```



Stops the welcome message from being sent.
{% endtab %}

{% tab title="Show Configuration" %}
```
/welcome show-config
```



An easy way to see how your message will look. The response will tell you the channel the message will be sent to as well as an example of the message itself.
{% endtab %}
{% endtabs %}
