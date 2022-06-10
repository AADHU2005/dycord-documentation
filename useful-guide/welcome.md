---
description: A simple guide for Welcome module which can make you understand how to use it.
---

# Welcome

### Default Configuration

The default configurations are as follows:

Message: `Hello {user.mention}! Welcome to **{server}`**`**`**&#x20;

Delete after: Each welcome message will be deleted after 8 seconds.

{% hint style="info" %}
**You can enable welcome module without any configurations.**
{% endhint %}

### How to enable/disable welcome module?

* Typing `-welcome <#channel>` will enable welcome in that channel.
* Typing `-welcome disable` will disable welcome in your server.

{% hint style="info" %}
You add upto 3 Text Channel.
{% endhint %}

### How can I change welcome message?

* Type `-welcome` to see welcome message variables.
* Type `-welcome [message/msg] <message>` to set custom welcome message.

![Welcome Variables](<../.gitbook/assets/Screenshot 2022-04-05 192935.png>)

![Tutorial: How to set custom welcome message](<../.gitbook/assets/Screenshot 2022-04-04 195841.png>)

### Setting delete after

Delete after is the number of seconds after which the greet message should be deleted. This can be helpful if you don't the channel to get flooded with greeting messages.

Command: `-welcome time <time(in seconds)>`

![Tutorial: Setting time for welcome message](../.gitbook/assets/image.png)

{% hint style="info" %}
Set delete after to `0s`, if you don't want welcome messages to be deleted.

Command: `-welcome time 0s`
{% endhint %}

### Variables

#### Member Variables

* `{user.mention}` - The member's mention (@Aadhu)
* `{user.tag}` - The member's tag (Aadhu#0345)
* `{user.name}` - The member's username (Aadhu)
* `{user.id}` - The member's ID (815480311285547079)

Server Variables&#x20;

* `{server}` - The server's name (Dycord HQ :microscope:)
* `{memercount}` - The server's member count (3522)
* `{membercount.ordinal}` - Same as membercount but includes ordinal number (3522nd)

{% hint style="success" %}
To review and test your final settings, Use **`-welcome test`** command.
{% endhint %}
