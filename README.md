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

6. **What format does my phone number need to be in?**

Mobile phone numbers need to be entered in international formatting with the country code and without spaces, plus signs or leading zeros.

**Did not find what you're looking for ?**

Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feature Request
Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feedback
Send feedback to our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).
