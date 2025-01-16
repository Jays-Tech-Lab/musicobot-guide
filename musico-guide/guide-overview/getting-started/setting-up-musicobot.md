---
description: >-
  This page provides a quick overview of the setup process for Musico, guiding
  users through each step to ensure a smooth and customized experience.
cover: >-
  ../../.gitbook/assets/untug_The_Text_Musico_Setup_In_purple_Light_Text_above_Turntabl_a55b524e-32d2-48ac-b70c-b40161bf4aa1.png
coverY: 1072.378486055777
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# 🖱️ Setting up MusicoBot

### Step 1

* [ ] <mark style="color:orange;">**Begin by inviting**</mark>**&#x20;**<mark style="color:purple;">**MusicoBot**</mark>**&#x20;**<mark style="color:orange;">**to your Discord by using the provided "**</mark>[<mark style="color:blue;">**Invite Link**</mark>](https://discord.com/oauth2/authorize?client_id=810540985032900648\&permissions=2150754416\&scope=bot)<mark style="color:orange;">**", or through the**</mark> [**Dashboard**](musicobot-dashboard.md)<mark style="color:orange;">**. Then Authorize**</mark>**&#x20;**<mark style="color:purple;">**MusicoBot**</mark>**&#x20;**<mark style="color:orange;">**by selecting the appropriate permissions as shown below:**</mark>

<div align="center"><figure><img src="../../.gitbook/assets/image (1).png" alt="" width="89"><figcaption><p>MusicoBot Permissions</p></figcaption></figure></div>

#### Authorization Requirements

{% hint style="success" %}
_<mark style="color:green;">You should have Administrator Rights on the server your attempting to add Musico too, it will make the process much smoother and you should not be adding bots to servers that you are not Administrator on anyway.</mark>_
{% endhint %}

***

### Step 2

* [ ] <mark style="color:orange;">**Adding a custom music channel**</mark>

- After inviting Musico to your server, run the `.setup` command to initiate the setup process & add the custom #musico-request channel. In here you can complete the rest of the setup and start listening to music with Musico!

***

### Step 3

* [ ] <mark style="color:orange;">**Setting Custom Prefix (Optional)**</mark>

-   Use the `.set-prefix` command and choose your desired prefix. For example

    ```
    .set-prefix !
    ```

{% hint style="info" %}
The prefix in the context of Discord bots refers to the character or characters that users need to type before a command to invoke the bot's functionality. It helps distinguish bot commands from regular messages in a server.&#x20;
{% endhint %}

* For example, if a bot's prefix is set to `.` and there's a command to play music called "play", users would type `.play` to execute that command.

{% hint style="info" %}
_In essence, the prefix serves as a signal to the Discord server that the following text is a command intended for the bot to interpret and act upon. It's customizable,allowing server administrators to set it to their preferred character or string to avoid conflicts with other bots or server commands._
{% endhint %}

***

### Step 4

* [ ] <mark style="color:orange;">**Configuring Text and Voice Channels**</mark>

- Determine which text channels Musico can interact with and specify the voice channels where it's allowed to play music. This ensures seamless integration without cluttering unrelated channels.
- _For channel selection use `.text-channels <channel name>`_
- _For voice channels use `.set-voice <channel name>`_
