# 서버리스 Telegram Bot 샘플

# 준비사항 

### (개발시) ngrok 사용

외부IP가 없는 개발환경에서 필요.

```
> ngrok http 3000 -region jp
```
되도록 속도가 빠른 일본리전(jp)을 사용한다.

### webhook 활성화

```
https://api.telegram.org/bot<BOT_TOKEN>/setWebhook
```
Param) url="API Endpoint"

예) url=https://53278c5d.jp.ngrok.io/message

# 사용법

텔레그램으로 대화를 하면서 내 문장에 `hello` 라는 단어가 있으면 봇이 반응을 하는게 전부이다.

