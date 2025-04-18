WhatsApp Rent Reminder Bot using Twilio

This Python script helps automate rent sharing and sends WhatsApp reminders using the Twilio API. Ideal for roommates or hostel groups!


Features:

- Calculates rent, food, and electricity share per person
- Sends personalized WhatsApp reminders before due date
- Message scheduled 3 days before rent due date
- Works with Twilio WhatsApp Sandbox


 Requirements:


- Python 3.7 or above
- Twilio account (with WhatsApp Sandbox setup)
- Install required library:
  ```bash
  pip install twilio
  
-> How to Use?
Step 1: Set Up Twilio Account

Before using the bot, you'll need a **Twilio account**. Here's how to get started:

1. Sign Up on Twilio: 
   - Go to [Twilio](https://www.twilio.com/) and create a free account.

2. Obtain Twilio Credentials:
   - After logging into the Twilio Console, get your **Account SID** and **Auth Token**.
   - Obtain a **WhatsApp-enabled Twilio number** by visiting the [Twilio Sandbox for WhatsApp](https://www.twilio.com/docs/whatsapp/quickstart).

Step 2: Install the Required Libraries

This bot requires the **Twilio Python library** to send WhatsApp messages. To install it, run the following command in your terminal:

```bash
pip install twilio


