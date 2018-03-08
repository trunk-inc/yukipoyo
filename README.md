# Project Summary
Yukipoyo LINE bot is bot like yukipoyo.
ゆきぽよと会話しているかのようなLINE botをつくる

# Skills
- Python 3.x
- LINE Messaging API
- [Minette](https://github.com/uezo/minette-python)
- [Google Cloud Natural Language Analyzing Sentiment API](https://cloud.google.com/natural-language/docs/analyzing-sentiment?hl=en)
- API Gateway
- AWS Lambda
- DynamoDB

# DynamoDB
```
{
  "documentSentiment": {
    "magnitude": 0.8,
    "score": 0.8
  },
  "sentences": [
    {
      "text": {
        "content": "好きな人の力ってすごいんだね。",
        "beginOffset": 0
      },
      "sentiment": {
        "magnitude": 0.8,
        "score": 0.8
      }
    }
  ]
}
```

