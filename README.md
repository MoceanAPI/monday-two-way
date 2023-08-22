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

You can get 20 FREE credits and credits are valid for 14 days. Subject to approval.

2. **Can I send international messages?**

Yes. We are an international SMS provider. You can send out SMS both locally and internationally based on our price list.

3. **What is the maximum characters per SMS I can put into the message?**
   
English messages can be up to 160 characters, while for Unicode text messages (including Arabic, Chinese, etc.), the limit is 70 characters.

5. **Can I send long message content?**

Yes, you can send long message content and your credit will be deducted based on the length of the message content.

6. **Is there a limit to how many numbers I can send at one time?**

There is no limit on numbers to be sent in one go.

7. **What format does my phone number need to be in?**

Mobile phone numbers need to be entered in international formatting with the country code and without spaces, plus signs or leading zeros.

8. **What is the character limit for the sender/sender ID?**

The alpha sender ID can be a maximum of 11 characters, while the numeric sender can consist of up to 15 digits.

### SMS Compliance in United States (US)

1. **SMS Compliance Guidelines**

Below are some general guidelines / best practices you can follow:

<ins>Obtain proper consent</ins>: You must obtain consent from the mobile subscriber before sending any SMS messages. The consent should be opt-in and clearly disclose the frequency and nature of messages.
<ins>Include opt-out instructions</ins>: Every SMS message should include clear and easy-to-follow instructions on how to opt-out of receiving further messages.
<ins>Provide customer support</ins>: Your SMS messaging program should include customer support options for subscribers to receive assistance
<ins>Comply with content restrictions</ins>: SMS messages should comply with all content restrictions and regulations

2. **Campaigns Prohibited:**

- Loan advertisements except for messages from direct lenders for secured loans
- Payday loans
- Credit repair
- Debt relief
- Pharmacy/Cannabis/Tobacco/Vape
- ED
- Work from home, 'secret shopper' and similar advertising campaigns
- Gambling/sweepstakes
- Cryptocurrencies
- Lead generation campaigns that indicate the sharing of collected information with third parties

3. **Messaging Prohibited:**

- Message streams that result in excessive complaints or STOP commands typically indicate an unwanted message campaign and will not be allowed to continue.
- Phishing: Messages that attempt to obtain sensitive information, such as usernames, passwords, or financial information, through fraudulent means are strictly prohibited.
- Fraud or scams: Messages that deceive subscribers by promoting fraudulent or misleading offers, schemes, or scams are not allowed.
- Messages that use deceptive marketing practices or false claims to promote products or services are prohibited.
- Messages that distribute malware or direct subscribers to download apps from non-secure locations are strictly prohibited.
- Loan, debt consolidation, debt relief, and student loan programs from any enterprise that cannot grant the loan themselves: Enterprises that cannot grant loans themselves are not allowed to promote loan, debt consolidation, debt relief, and student loan programs.
- Affiliate lead generation for these financial programs is also prohibited.

4. **US SMS Delivery Option**

| Section| 10DLC | TOLL FREE| DEDICATED SHORT CODE|
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Introduction                 | 10DLC is just the new name for sending primarily 1-way A2P messages over local long codes. In the past using local long codes was primarily for 2-way conversational traffic (P2P) but companies were using it for 1-way traffic as well. If you wanted to send any kind of volume of messages via long codes (more than a few hundred a day) you had to use a pool of senders because velocity filters would treat high volumes of messages coming from one sender as SPAM and automatically block the sender. Now with 10DLC registration you can send higher volumes of messages from a single sender. This works really well for sending under about 2,000 messages per day and if you or your customer wants a local sender in their area. External vetting is also available for an additional fee to get more than 2,000 messages per day per sender.  | A few years ago Operators started allowing SMS to be delivered via the toll free number pool that was previously only for voice calls. Toll free numbers are also 10 digits long but all start with one of the following dial codes: 1800, 1888, 1877, 1866, 1855, 1844 or 1833. This route allows for handset DLR (delivery receipt) instead of the less accurate gateway DLR provided on 10 DLC. The route also did not have a volume limit per sender like long codes do so it was ideal for business use. Additionally, the service comes with auto responders built in for STOP, HELP and CANCEL responses from mobile subscribers, and has a gateway maintained opt-out database per sender. The route currently has the same content restrictions as 10 DLC. | In the USA a short code is a dedicated 5 or 6 digit sender ID assigned to a specific brand for a specific purpose or campaign. A good example is a bank sending one time codes to their customers for 2 factor authentication. This is the most premium SMS service in the USA as it has handset DLR and goes through a lengthy vetting process. There are several requirements to get one of these codes approved, they take about 1-2 months to get fully approved and have significant monthly and setup fees, so they are typically used by larger corporations with very high volume sending. Client needs to show opt-in process and be able to handle auto responders for HELP/STOP/CANCEL as well as maintain opt-out database per campaign.  |
| Type of Number &amp; Example | Long Number (Example: 13458677777)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Toll-Free Number (Example: 18885555555)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 5 or 6 digit Short Code (Example: 12345)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Suggested Use Cases          | High volumes, Marketing, 2FA, Alerts, 2FA, Notifications, Customer Care, Alerts, Higher Education, Low Volume Mixed, Marketing, Polling and Voting, Public Service Announcement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Low - Medium volumes, 2FA, Non-Marketing &amp; Marketing, Customer Service, Alert Notifications                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | High Volume School/Flight/Appt reminders                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Approval Process             | To send messages via this route, it is necessary to register brands and campaigns with TCR (The Campaign Registry) as required by the Operators and interconnected gateways. TCR is an independent registry authorized to register brands and campaigns with T-Mobile and AT&amp;T. Although Verizon, the other major USA operator, is currently not participating, registration requirements are not as strict at this time. Clients must show their opt-in process and ability to handle auto responders for HELP/STOP/CANCEL and maintain opt-out databases per campaign.                                                                                                                                                                                                                                                                                  | To send messages through this route, we must obtain approval from the toll-free gateway for our campaigns. Although they require less information than TCR for 10DLC, their content guidelines are still strict. If the campaign volume is less than 25,000 per month, we can proceed without official gateway approval, but we must adhere to all regulations, and our support department must review the verification form submitted.                                                                                                                                                                                                                                                                                                                             | To send messages through this route, we must obtain campaign approval from the Operators.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Time to register             | 2-7 business days                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 5-15 business days                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 1-2 months                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| Canadian Reach               | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | No (User must purchase a Canadian Short Code)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| 2-Way Possible               | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Concatenated                 | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Unicode                      | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Yes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| How to order                 | Email your request to [sales@moceanapi.com](mailto:sales@moceanapi.com)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Download TFN registration form [here](https://docs.google.com/document/d/1I37LP5jF4fnpno9FUcvcQ0p06oGtOqhZ/edit?usp=sharing&ouid=115964922142813966781&rtpof=true&sd=true)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Email your request to [sales@moceanapi.com](mailto:sales@moceanapi.com)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |


**Did not find what you're looking for ?**

Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feature Request
Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feedback
Send feedback to our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).
