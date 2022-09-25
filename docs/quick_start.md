# LensBot v0 Docs

## What is LensBot?

LensBot is a Lens Protocol Telegram bot that helps you keep an eye on your favourite lens creator from the comfort of your own telegram.

LensBot also allows you to post and comment from telegram without holding your profile NFT, This is achieved by enabling our Dispatcher so we can gaslessly relay your posts.

# Quick Start

## Setup

1. add the [LensBot](https://t.me/lenstream_bot) bot to your telegram

2. type `/help` to get the initial list of commands



# Notifications Features

## Watching an account

to get notifications for a specific Lens account: 

```
/watch letsraave.lens
```
Replace `letsraave.lens` with the account you wanna watch. 

## Unwatching an account

```
/unwatch verynoisyaccount.lens
```


# Publishing Features


## Enabling Dispatcher

In order to be able to post, comment or follow via lensbot, You need to enable the dispatcher:

1. start the dispatcher flow
    ```
    /dispatch
    ```
    ![dispatch](/assets/dispatch.png)


    Open the link where you have access to the wallet holding the lens profile, 

    > Example: if you're using metamask on your laptop and telegram on your phone, go open that link on your laptop instead of your phone.

2. Click Login to sign into lens

    Once you're there click login and sign the login challenge. you should be able to see your profile picture and lens handle.
    ![shortcode](/assets/shortcode.png)

3. Enter the shortcode on your phone. you should now see your telegram username on the browser.
    ![codeconfirmed](/assets/codeconfirmed.png)

4. now you're ready to click the big green `Enable Dispatcher` button. Sign the msg and thats all.


## Posting from Telegram

To enable posting from your lensbot, you need to [enable the lensbot dispatcher first](#enabling-dispatcher), This is gonna require you to login to lens.

You can now use `/post` command to directly post to lens protocol. gasslessly, and without ever having to hold your precious profile NFT on your mobile. 

**NOTE** you can post any of the supported MIME types to lens, this includes, pics, gifs, videos & audio
![postFlow](/assets/postFlow.png)

The body of content of the picture/video posts is the caption
![postPic](/assets/postPicFlow.png)

## Commenting 

Currently you can only comment on posts that you got notified on, simply by replying with a `/comment [your comment text goes here.]` 

![comment](/assets/comment.png)


