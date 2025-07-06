# action-repo

Dummy repo to trigger webhooks

📦 action-repo

This is a dummy GitHub repository created as part of the TechStaX Developer Assessment. Its purpose is to trigger GitHub webhook events such as:



✅ push



✅ pull\_request



These events are sent to the webhook server hosted in webhook-repo, where they are logged into MongoDB and displayed in a live UI.



🔧 Usage

To trigger webhook events from this repository:



✅ Push: Commit any new file or change and push to main



✅ Pull Request: Create a pull request from a feature branch



✅ Merge: Merge a pull request (triggers as part of pull\_request event)



🔗 Webhook Endpoint

A webhook is configured for this repo to send events to the Flask server:



nginx

Copy

Edit

Payload URL: https://<ngrok-id>.ngrok-free.app/webhook

(Replace <ngrok-id> with your current ngrok URL)



Content type: application/json

Events: push, pull\_request



👩‍💻 Author

Punya Shree T S

punyashree7.27@gmail.com





