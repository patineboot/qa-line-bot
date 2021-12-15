# qa-line-bot

質問に答えるLine botだよ。

質問と回答は、Microsoft Azure QnA Makerで生成します。
Line Message APIを使用しています。

## 実行手順

_.env.sample_から_.env_に名前を変えて、Line Message APIとAzure QnA Makerの鍵の設定をします。

```bash
LINE_CHANNEL_ACCESS_TOKEN=
LINE_CHANNEL_SECRET=
AZURE_QNAMAKER_URL=
AZURE_QNAMAKER_SUBSCRIPTION_KEY=
```

インターネトからURLへ配置して実行してください。
Message APIは以下に設定する必要があります。

`http://[your host name or IP address]/callback`

## 使用するサービス

- Microsoft Azure QnA Maker  
   https://azure.microsoft.com/ja-jp/services/cognitive-services/qna-maker/
- Line Message API  
   https://developers.line.biz/ja/services/messaging-api/

## 使用するSDK

- Messaging API SDK  
   https://github.com/line/line-bot-sdk-python
