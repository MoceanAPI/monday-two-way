# Mocean monday.com Two Way SMS User Documentation

## Looking for other documentation ?
- [MoceanAPI - SMS Broadcast Documentation](https://moceanapi.github.io/monday-dashboard/)
- [MoceanAPI - Send SMS Documentation](https://moceanapi.github.io/monday-item/) 
- [MoceanAPI - Two Way SMS Documentation](https://moceanapi.github.io/monday-two-way/) (Current)
- [MoceanAPI - SMS Automation Documentation](https://moceanapi.github.io/monday-automation/)
- [SMS Sender ID Country List](https://moceanapi.github.io/monday/)

## Contents
- [Installation](#installation)
- [Usage](#usage)
    - [Prerequisites](#prerequisites)
    - [Send SMS](#send-sms)
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

## Buy a Virtual Number (VLN)

### Non United States (US) Virtual Number
Follow the steps below to buy a non US virtual number
1. Navigate to [Buy virtual number page](https://dashboard.moceanapi.com/number/show)
2. Select the country of the virtual number you'd like to own

![image](https://user-images.githubusercontent.com/24620178/220541278-a7a796a6-3858-4994-94df-0578e15d6ed8.png)

3. After selecting your desired number, click on Buy

![image](https://user-images.githubusercontent.com/24620178/220541846-631cba9a-163c-4469-abe5-8d1f01efc5c2.png)

### United States (US) Virtual Number

Follow the steps below to buy a US virtual number. We will guide you through the information required to own a US virtual number.

TBA

## Usage
### Prerequisites
1. Before you can send SMS, you will need to specify the `Phone column` in the settings

![image](https://user-images.githubusercontent.com/24620178/212603999-cdf12e58-75fd-4260-bb93-4fbc8c5012cf.png)

2. You'll need to buy a virtual number [here](https://dashboard.moceanapi.com/number/show) to receive the SMS from your recipients

3. You can then select your virtual numbers in the `Virtual Numbers` dropdown menu

### Virtual Number

1. Please buy a virtual number [here](https://dashboard.moceanapi.com/number/show) if you don't already have one.

2. Login to [MoceanAPI Dashboard](https://dashboard.moceanapi.com) and navigate to [API Account](https://dashboard.moceanapi.com/user/apisetting) on the left navigation menu.
 
3. Configure the **MO URL** to `https://monday.moceanapi.com/api/v1/receive_sms`

![image](https://user-images.githubusercontent.com/24620178/213127689-2f8df906-99d3-4292-a640-7a37161d68df.png)

### Send SMS

1. Our App will automatically populate the `Phone number` field if it detects a value in the specified `Phone Column`
2. Select the virtual number you owned in `Virtual Numbers` dropdown menu.
3. Compose the SMS you would like to send and click on Send SMS.
4. The SMS status will be shown at the bottom of the SMS card

![image](https://user-images.githubusercontent.com/24620178/212608210-6d3172c4-9142-49e3-9443-76b84479f931.png)

**SMS Statuses**
- Pending = SMS is awaiting Delivery Report (SMS may have already been sent)
- Fail = SMS failed to deliver
- Success = SMS delivered

## Whitelist IP Address

For added security, you should whitelist `192.168.4.1` IP address in your [MoceanAPI Dashboard](https://dashboard.moceanapi.com)

To do so, follow these steps

1. Go to [MoceanAPI Dashboard](https://dashboard.moceanapi.com/user/apisetting)
2. Navigate to **API Account** 
3. Key in **`192.168.4.1`** into **Allow IP** field

![image](https://user-images.githubusercontent.com/24620178/200761674-1ccb6e6c-2d7b-499d-bef6-ee47a3e2a624.png)

## FAQ
1. Can I get Test Credits ?

You can get 20 FREE credits and credits are valid for 14 days. Subject to approval.

2. Can I send international messages?

Yes. We are an international SMS provider. You can send out SMS both locally and internationally based on our price list.

3. What is the maximum characters per SMS I can put into the message?

160 characters for a normal text message, 70 characters for a Unicode text message (Arabic, Chinese, and etc)

4. Is there a limit to how many numbers I can send at one time?

There is no limit on numbers to be sent in one go.

5. What format does my phone number need to be in?

Mobile phone numbers need to be entered in international formatting with the country code and without spaces, plus signs or leading zeros.

**Did not find what you're looking for ?**

Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feature Request
Do raise a support ticket with our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).

## Feedback
Send feedback to our Support Team at [support@moceanapi.com](mailto:support@moceanapi.com).
