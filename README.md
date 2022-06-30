# geo-bot

## Telegram calls

### Delete telegram webhook
❯ curl  "https://api.telegram.org/bot<Token from botfather>/deleteWebhook?url=https://38f3-213-113-63-169.eu.ngrok.io/register" 
{"ok":true,"result":true,"description":"Webhook was deleted"}
### create telegram webhook
❯ curl  "https://api.telegram.org/bot<Token from botfather>/setWebhook?url=https://38f3-213-113-63-169.eu.ngrok.io/webhook" 
{"ok":true,"result":true,"description":"Webhook was set"}
### Respond to message through chat_id
❯ curl 'https://api.telegram.org/bot<Token from botfather>/sendMessage?chat_id=355897800&text=hi+bla'
{"ok":true,"result":{"message_id":10,"from":{"id":5117424180,"is_bot":true,"first_name":"geobot","username":"IsItABirdOrAPlaneBot"},"chat":{"id":355897800,"first_name":"Jo\u00e3o","last_name":"Veiga","username":"jcsvveiga","type":"private"},"date":1656589988,"text":"hi bla"}}

