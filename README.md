# vercel-checkin

## How to use

#### 1. Install vercel-cli

```bash
$ npm i -g vercel
```

#### 2. Run with vercel-cli

```bash
$ vercel deploy
```

#### 3. Setup the environment variables

`TG_BOT_TOKEN` for your telegram bot token

`TELEGRAM_CHAT_ID` for your telegram chat id

`V2EX_COOKIE` for your v2ex cookies

`ALIYUNPAN_REFRESH_TOKEN` for your 阿里云盘 refresh_token


![img](https://i.imgur.com/i0w6hSd.png)


#### 4. Github auto commit setup

Go to project `Settings - Actions - General`, set `Workflow permissions` to `Read and write permissions`. Then click save button.


## Or you can setup all by clicking this button

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FFaiChou%2Fvercel-checkin)


**Don't forget to setup environment variables.**