# Mocean monday.com Two Way SMS User Documentation

## Looking for other documentation ?
- [MoceanAPI - SMS Broadcast Documentation](https://moceanapi.github.io/monday-dashboard/)
- [MoceanAPI - Send SMS Documentation](https://moceanapi.github.io/monday-item/) 
- [MoceanAPI - Two Way SMS Documentation](https://moceanapi.github.io/monday-two-way/) (Current)
- [MoceanAPI - SMS Automation Documentation](https://moceanapi.github.io/monday-automation/)
- [SMS Sender ID Country List](https://moceanapi.github.io/monday/)

## Contents
- [Installation](#installation)
- [Buy a Virtual Number](#buy-a-virtual-number)
- [Usage](#usage)
    - [Prerequisites](#prerequisites)
    - [Send Two Way SMS](#send-two-way-sms)
    - [Send SMS](#send-sms)
    - [Get notified on new SMS replies](#get-notified-on-new-sms-replies)
- [Whitelist IP Address](#whitelist-ip-address)
- [Frequently Asked Questions](#faq)
- [Feature Request](#feature-request)
- [Feedback](#feedback)

## Installation

1. Select the board you would like to install MoceanAPI Two Way SMS App
2. Click on one of the items in the board and click on the `+` sign
![image](https://user-images.githubusercontent.com/24620178/153553705-bdb6e98f-0b16-4386-9283-aa0121e28589.png)
3. Search for `Mocean` in the search bar and install the `MoceanAPI - Two Way SMS`
![image](https://user-images.githubusercontent.com/24620178/212603128-99102bc7-156b-4f11-8c66-9ca5ea73eb93.png)
4. After installing the app, you will need to `Authenticate` your account
![image](https://user-images.githubusercontent.com/24620178/153554028-b92b902d-3758-43e6-a50f-7ddce1541673.png)
5. Enter your Mocean API Credentials and the sender
![image](https://user-images.githubusercontent.com/24620178/206361287-89fdabaf-15ea-498a-9f22-4654b0653a38.png)
6. After you've successfully authenticated, you will be redirected back to `monday.com`

## Buy a Virtual Number

### Non United States (US) Virtual Number

**Important** If you would like to enable the sending of two-way SMS, kindly get in touch with our sales team [here](mailto:sales@moceanapi.com) to initiate the setup process.

Follow the steps below to buy a non US virtual number
1. Navigate to [Buy virtual number page](https://dashboard.moceanapi.com/number/show)
2. Select the country of the virtual number you'd like to own
![image](https://user-images.githubusercontent.com/24620178/220541278-a7a796a6-3858-4994-94df-0578e15d6ed8.png)
3. After selecting your desired number, click on Buy
![image](https://user-images.githubusercontent.com/24620178/220541846-631cba9a-163c-4469-abe5-8d1f01efc5c2.png)

### United States (US) Virtual Number

Follow the steps below to buy a US virtual number. We will guide you through the information required to own a US virtual number.

1. Please contact our sales team [here](mailto:sales@moceanapi.com) for detailed configuration

## Usage
### Prerequisites
1. Before you can send SMS, you will need to specify the `Phone column` in the settings
![image](https://user-images.githubusercontent.com/24620178/220550902-106c3c77-01f3-4da6-9b42-b0dfae30d21a.png)
2. You'll need to buy a virtual number [here](#buy-a-virtual-number) to receive the SMS from your recipients
3. You can then select your virtual numbers in the `Virtual Numbers` dropdown menu

### Send Two Way SMS

1. If you would like to enable the sending of two-way SMS, kindly get in touch with our sales team [here](mailto:sales@moceanapi.com) to initiate the setup process.

### Send SMS

1. Our App will automatically populate the `Phone number` field if it detects a value in the specified `Phone Column`
2. Select the virtual number you owned in `Virtual Numbers` dropdown menu.
3. Compose the SMS you would like to send and click on Send SMS.
4. The SMS status will be shown at the bottom of the SMS card

![image](https://user-images.githubusercontent.com/24620178/220551544-f31aea05-00b0-48ab-ae74-eb5747de21f7.png)

**SMS Statuses**
- Pending = SMS is awaiting Delivery Report (SMS may have already been sent)
- Fail = SMS failed to deliver
- Success = SMS delivered

### Get notified on new SMS replies

1. You will need to `Connect your monday.com account to MoceanAPI`
2. Navigate to `Update API Credentials page`
![image](https://user-images.githubusercontent.com/24620178/220545760-55f66576-0c32-4f3b-af67-bacc5af96339.png)
3. Click on `Connect MoceanAPI`
4. Continue the process until you're redirected back to the `Update API Credentials page`
5. You can now proceed to `enable` or `disable` receiving notifications in monday.com on every SMS reply
6. Configure the **Person Column** you'd like to receive notifications on every SMS replies
![image](https://user-images.githubusercontent.com/24620178/220549544-89966ee0-6e78-46a2-b6f4-9113c3542359.png)
7. Now just send the SMS as usual and we'll send you a `notification` in **monday.com** on every new SMS reply

Want to get notified on other channels ? Talk to our [Support](#feature-request)

## Whitelist IP Address

For added security, you should whitelist `192.168.4.1` IP address in your [MoceanAPI Dashboard](https://dashboard.moceanapi.com)

To do so, follow these steps

1. Go to [MoceanAPI Dashboard](https://dashboard.moceanapi.com/user/apisetting)
2. Navigate to **API Account** 
3. Key in **`192.168.4.1`** into **Allow IP** field

![image](https://user-images.githubusercontent.com/24620178/200761674-1ccb6e6c-2d7b-499d-bef6-ee47a3e2a624.png)

## FAQ
1. **Can I get Test Credits ?**
- You can get 20 FREE credits. Please note that once you make a top-up, the free credits will be removed.

2. **What means by 20 credits, 1 credit = EUR 1?**
- No, during the trial period, 1 credit equals 1 SMS. So, with 20 credits, you can test 20 SMS.

3. **Can I request more trial credits?**
- Yes, of course! If you&#39;d like to test further, feel free to request from us.

4. **Can I send international messages?**
- Yes. We are an international SMS provider. You can send out SMS both locally and internationally.
The price for each country varies, do check out our pricing list [here](https://moceanapi.com/pricing)

5. **What is the maximum characters per SMS I can put into the message?**
- English messages can be up to 160 characters, while for Unicode text messages (including Arabic,
Chinese, etc.), the limit is 70 characters.

6. **Do you support long message content?**
- Yes, you can send long message content and your credit will be deducted based on the length of the message content.

7. **Is there a limit to how many numbers I can send at one time?**
- There is no limit on numbers to be sent in one go.

8. **What format does my phone number need to be in?**
- Mobile phone numbers need to be entered in international formatting with the country code and without spaces, plus signs or leading zeros. Example: Country code 60 for country Malaysia, 60123456789

9. **What is the character limit for the sender/sender ID?**
- The alpha sender ID can be a maximum of 11 characters, while the numeric sender can consist of up to 15 digits.

10. **I attempted to send messages to US numbers, but they failed to be delivered. Why?**
- Message content that is not registered will result in a failure. To comply with US regulations, it’s essential to buy a number and undergo a use case verification before you can send SMS to your customers.

11. **Can I utilize my personal mobile or landline number as the sender for SMS to the US?**
- No, it’s necessary to purchase a dedicated number, such as a Toll-Free Number, and complete the use case verification process.

12. **How do I go about obtaining or purchasing a Toll Free Number in the US/Canada?**
- Steps:
1) Complete the number registration form available [here](https://docs.google.com/document/d/1b-VJCcCGcNgHXgm2dmelWW6m0vsN6Kfg/edit) 
2) Proceed with the payment.
3) After your registration is accepted and approved, you’ll be able to send and receive SMS using your Toll Free Number.

13. **What is the expected timeframe for number approval?**
- The duration varies, but typically it takes approximately 2-3 weeks.

14. **I am currently having an US / Canada TFN / 10DLC from another provider. I want to use the same number on your platform. Is that possible?**
- Yes, it is possible. We would need a LoA (Letter of Agency) signed to allow us to take over the SMS part of the number. Please [contact us](mailto:support@moceanapi.com?cc=sookchin@moceansms.com) for further assistance.

15. **Why my SMS failed to deliver?**
- You may have set an invalid sender ID, alphanumeric sender ID must be less than 12 characters, and numeric sender ID must be less than 16 characters. Another common issue is you did not specify the correct phone number format including country code. Example: Country code 60 for country Malaysia, 60123456789

16. **I would like to send my content to the US and Canada, but it has been changed to 'Customer ABC just booked an appointment'. May I know why?**
 - This occurs because, during the trial period, your content is automatically replaced with that message. To comply with regulations, you will need to purchase a number and verify your use case in order to send your own content. You can download the necessary form [here](https://docs.google.com/document/d/1b-VJCcCGcNgHXgm2dmelWW6m0vsN6Kfg/edit), and we’ll assist you in obtaining a Toll-Free number. Once you have it, you’ll be able to send your content freely.

17. **I want to purchase SMS credits, how to top up my account?**
- Easy &amp; fast, just follow a few steps below:
1) Login to your account at [https://dashboard.moceanapi.com/login](https://dashboard.moceanapi.com/login) 
2) Go to Top Up page on left menu
3) Select Payment
4) Pay with credit card / PayPal
Your account will be credited instantly and enjoy texting!

18. **Why I cannot buy a Virtual Number?**
- This is due to your account is under trial mode or has insufficient balance. Please top up before proceeding with number purchase.

19. **Why I cannot get monday.com Notifications after receiving an SMS reply?**
- You will need to connect your Monday.com account with us. We have a video for you to follow along to connect your Monday.com account and MoceanAPI. Check it out [here](https://www.youtube.com/watch?v=P1DG6grBlQ0)

20. **Do I need a Virtual Number to send 1-Way SMS?**
- No, you don’t need a Virtual Number to send 1-Way SMS, unless you are sending SMS to recipients in the US &amp; Canada.

21. **Can I send SMS with shortener URL to United States (US)?**
- Public URL shorteners, such as bit.ly and TinyURL, are not allowed.
Please check [here](https://moceanapi.com/question/62) for more info. 

22. **What is forbidden message categories for SMS in the US/Canada?**
- The messaging use cases described [here](https://moceanapi.com/question/63) are strictly prohibited.
Even if your specific use case isn't explicitly listed as prohibited, certain types of message content may still face restrictions. For example, using shared or free public URL shorteners is not allowed and could result in filtering. Please make sure that any shortened URLs you use are company-branded.

23. **Can I use the same WhatsApp number on Monday.com and my WhatsApp mobile app to send messages to my customers?**
- No. Once a phone number is registered on the WhatsApp Business Platform for use with Monday.com, it can no longer be used on the WhatsApp mobile app.

24. **I tested WhatsApp marketing messages to US numbers, but the messages were not delivered. Why?**
- Starting April 1, 2025, META has temporarily paused the delivery of all marketing template messages to WhatsApp users with United States phone numbers (numbers with the +1 dialing code and a US area code). Therefore, we recommend using SMS to send your marketing messages to ensure delivery.

25. **Can I use automation to send reminders?**
- Yes, our app can integrate with Google Calendar to send reminders automatically via automation. Please refer to the provided guide [here](https://github.com/MoceanAPI/monday-dashboard/blob/main/Monday%20integration%20with%20google%20calendar.pdf) for more details.

26. **US Toll Free Number (TFN) SMS delivery features**

| Section| TOLL FREE|
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Introduction                 | A few years ago Operators started allowing SMS to be delivered via the toll free number pool that was previously only for voice calls. Toll free numbers are also 10 digits long but all start with one of the following dial codes: 1800, 1888, 1877, 1866, 1855, 1844 or 1833. This route allows for handset DLR (delivery receipt) instead of the less accurate gateway DLR provided on 10 DLC. The route also did not have a volume limit per sender like long codes do so it was ideal for business use. Additionally, the service comes with auto responders built in for STOP, HELP and CANCEL responses from mobile subscribers, and has a gateway maintained opt-out database per sender. The route currently has the same content restrictions as 10 DLC.  |
| Type of Number & Example | Toll-Free Number (Example: 18885555555)|                                                                                                                                                                |
| Suggested Use Cases | Low - Medium volumes, 2FA, Non-Marketing &amp; Marketing, Customer Service, Alert Notifications |
| Approval Process             | To send messages through this route, we must obtain approval from the toll-free gateway for our campaigns. Although they require less information than TCR for 10DLC, their content guidelines are still strict. If the campaign volume is less than 25,000 per month, we can proceed without official gateway approval, but we must adhere to all regulations, and our support department must review the verification form submitted. |
| Time to register             | 5-15 business days  |
| Canadian Reach               | Yes |
| 2-Way Possible               | Yes |
| Concatenated                 | Yes |
| Unicode                      | Yes |
| How to order                 | Download TFN registration form [here](https://docs.google.com/document/d/1b-VJCcCGcNgHXgm2dmelWW6m0vsN6Kfg/edit)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |

**Did not find what you're looking for ?**

Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feature Request
Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feedback
Send feedback to our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).
