# Disctopia Setup guide

## **Discord**

### Step 1# Create server

You need to create a Discord server using [this](https://discord.new/k2BdGKDEpQpJ) template.

You should get this on Discord after clicking the link:
![image](https://i.ibb.co/WczCgPZ/Capture.png)
Give your server a name and click on the "Create" button.

### Step 2# Create the Webhook

You need to create 2 Discord Webhooks from your **Servers Settings >> Intergrations >> Webhooks.**

 Name it **"Keylogger"** and set it's channel to **"main"**

![image](https://i.ibb.co/RBmNS3K/Capture.png)

I suggest you Copy the webhook URL and save it somewhere as you will need it while building a backdoor.


### Step 3# Create the Bot

 You need to create a Discord Bot from the **discord developer portal.** So make sure you are connected to Discord from the Web Browser and head over to [this](https://discordapp.com/developers/applications/me) page and click on **"New Application."**

![image](https://i.ibb.co/JKg1Y9c/Capture.png)

Then you need to give your application a name and click on **"Create"**.

![image](https://i.ibb.co/W5BhCvv/Capture.png)

Now from the settings on the left, you need to click on **"Bot"** and then **"Add Bot"**.

![image](https://i.ibb.co/zSm3Jsz/Capture.png)

The last thing you can do is to customize the bot. Change its name, its avatar etc.

![image](https://i.ibb.co/b3YJmBq/Capture.png)

Once you get to this page, **Copy** the bot token and save it somewhere as you will need this for later.

Make sure you scroll down and enable the 3 options from the **Privileged Gateway Intents** section.

![image](https://i.ibb.co/f2P9KgQ/Capture.png)

### Step 4# Invite the Bot

Now you need to invite the bot to your server. Head to the [application page](https://discord.com/developers/applications) and click on the Application that you just created. Then click on the **OAuth2 tab** list and click on the **URL Generator** tab.

![image](https://i.ibb.co/x65JKxm/Capture.png)

Now you need to select the **bot** option from the scopes and the **Administrator** option from the bot permissions.

![image](https://i.ibb.co/qYVftpR/Capture.png)

The last thing you need to do is to copy the **URL** from the bottom of the page and paste it on your browser.

![image](https://i.ibb.co/FWGSXqS/Capture.png)

Now access the link that you coppied and you should see th bot invitation page. From the **"Add to serrver"** drop down menu make sure you select the server that yuo just created and click on **Continue**. You will also be asked to **Authorize** access to the bot and complete a CAPTCHA.

![image](https://i.ibb.co/hgqLsVB/Capture.png)

Once you are done with these you should see your Bot on your server.


### Step 5# Enable developer mode

You will need to enable the developer option for your Discord account. To do that head to your **Account Settings >> Advanced** and Enable **Developer Mode**

![image](https://i.ibb.co/BKnvn8H/Discord-Web-Enable-Developer-Mode.png)


## Step 6# Gather the important info

Now that you are all setup, in order to build a Discord based backdoor you are going to need the Bot Token,Webhook, main channel's ID and Servers ID.

If you followed the instructions you should already have the Bot token and webhook saved somewhere. Now let's get those ID's

To get the Server ID, right on the server you created and click on **Copy Server ID**

![image](https://i.ibb.co/yq5fqnD/Screenshot-2023-04-15-at-01-01-37.png)

And to get the channel ID go to the main channel on the server, right click on the channel and **Copy Channel ID**

![image](https://i.ibb.co/fMCfrcf/Screenshot-2023-04-15-at-01-04-38.png)

Now that you have all the important info gathered you can go ahead and build a Discord based backdoor.

---

## **Telegram**

### Step #1 Create Bot

Go to your telegram client and search for "BotFather"

![image](https://i.ibb.co/JKXgzgH/Screenshot-2023-04-15-at-01-06-38.png)

Run the following commands on the chat:

![image](https://i.ibb.co/tKyZnmV/Screenshot-2023-04-15-at-01-09-01.png)

In the last command result your **bot token** should appear. Copy that and save it as you will need it to generate a telegram based backdoors.

### Step #2 Get User Info

Next, search for "userinfobot"

![image](https://i.ibb.co/fq5bvVw/Screenshot-2023-04-15-at-01-09-47.png)

Now send that bot the following command:

![image](https://i.ibb.co/VwrSR4m/Screenshot-2023-04-15-at-01-09-55.png)

Copy and save your **id** as you will also need it to generate a telegram backdoor.

---

## **GitHub**

### Step #1 Create A Private Repo

You preferably want to make the repo private so that nobody can control the target machines other than you. You create one using [this](https://github.com/new) link:

![image](https://i.ibb.co/XsNM4Z2/Screenshot-2023-04-15-at-12-09-38.png)

### Step #2 Create A Personal Access Token

Go to your accounts settings and scroll down till you see developer on the left side.

![image](https://i.ibb.co/Z23Bnrh/Screenshot-2023-04-15-at-12-08-05.png)

Click on that and you should see a Personal Access Token section. Click on Fine-grained tokens:

![image](https://i.ibb.co/Kz9MFsh/Screenshot-2023-04-15-at-12-08-19.png)

Now create a new one:

![image](https://i.ibb.co/2t06Dsd/Screenshot-2023-04-15-at-12-08-30.png)

Give it a long Expiration and a unique name:

![image](https://i.ibb.co/qR5rfsZ/Screenshot-2023-04-15-at-12-08-57.png)

Now you need to give it access to the repo you just created:

![image](https://i.ibb.co/fDVLQJN/Screenshot-2023-04-15-at-12-10-46.png)

And the last step is to give your topken permissions. Head to **Repository Permissions** and look for **Contents** and **Pull Requests**. Set these both to **read and write**. In the end you should have the following permissions on the overview:

![image](https://i.ibb.co/ZVFm300/Screenshot-2023-04-15-at-12-12-15.png)


Once you are done with this, generate your token and save it as you may not see it again. You will have to regenerate it.