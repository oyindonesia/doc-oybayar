# OY! Dashboard Tutorial

## Login

To be able to login to Dashboard;
1. Make sure the username and password that you input are correct
2. Click 'Request OTP' button and input the OTP in the PIN Authentication field. The OTP will be sent to the email associated with your username.

![Login OTP](images/Login_OTP.jpg)

![Email OTP](images/email_otp.png)

If you tick the 'Remember this device' option, you are not required to input an OTP when you log back in next time. Hence, point 2 is required only when you login for the first time after you create your account.



## User Management

If you have a Super Admin role, you are able to add account for your team members and define the role for them.

These are the following steps to add new users;
1.  Login to Dashboard
2.  Go to Accounts -> User Management

![User Management 1](images/user_management_1.png)

3.  Click the 'Create User' button 
4.  Fill in the full name, username, email, phone number (optional), and password

![User Management 2](images/user_management_2.png)

5.  Choose the role that you want to assign your team member(s) to. You can choose one from the following available role:

- Admin: Has access to all menu, create and approve bulk disbursement and request, view active feature report, manage user list.
- Sub Account (Approver): Has access to approve disbursement and request, and view active feature report.
- Sub Account (Maker): Has access to create disbursement and request, and view active feature report

Aside from adding new users, a Super Admin is also able to edit and delete their existing users through clicking edit/delete button on the User List table.

## 2-Factor Authentication

To increase the security of your account, you can set up 2-factor Authentication. Currently, the security method that OY provides is through an authenticator app

These are the following steps to set up the 2-factor authentication;
1. Login to Dashboard
2. Go to Accounts -> Authenticator OTP
3. Download Authenticator App in your smartphone (from Play Store/App Store) or PC (you can download an extension for your browser). Examples of the app: Google Authenticator, Microsoft Authenticator, Authy, etc
4. Scan the barcode displayed on your OY Dashboard with your Authenticator App OR enter the setup key displayed next to it on your Authenticator App
5. Please type in the 6-numerical code displayed on your Authenticator App in the 'Authenticator OTP' on OY Dashboard

## Top Up

Top up is used to add balance to your OY account. 

Here's how you can access the top-up menu on your dashboard;  
1.  Login to Dashboard. 
2.  Go to Transaction Report -> Account Statement. 
3.  Click the 'How To Top Up' button. 

There are 2 ways in which you can top up your OY account:
- Top Up via Virtual Account
The Virtual Account number information can be found on 'How to Top Up Balance via VA' tab once you click the 'How To Top Up' button. If you choose to top up via VA, the topped up amount will be credited into your account real-time and you do not need to send any manual confirmation to OY 

![VA Topup](images/va_topup.png)
 
- Manual Top Up via Bank Transfer
Aside from Virtual Account, you can also transfer the top up money to OY's giro account. If you choose to top up via this method, you need to perform a manual confirmation in order that your money can be credited into your account.

After you have completed the fund transfer to OY! Indonesia, you need to perform the following steps;

1. Click the 'Manual Top Up Confirmation' tab on the top-up menu

![Manual Topup](images/manual_topup.png)

2. Fill in the fields with the following information;

Field Name | Description|
------ | ----------- | 
Amount | The amount that you have topped up (as per written in the Bukti Transfer)
Beneficiary Bank| A dropdown where you can choose to which bank you have transferred the top up amount to
Transfer Receipt| Click the upload button to upload the Bukti Transfer obtained after you have successfully performed the transfer. Can be in PDF, PNG, or JPEG format, with max. file size 10 MB
Transfer Receipt Type| Transfer Receipt with Reference Number --> If your uploaded transfer receipt displays the reference number, you need to choose this option.     Transfer Receipt without Reference Number --> If your uploaded transfer receipt doesn't display the reference number, you need to choose this option and fill in the date & timestamp according to your Bukti Transfer.

3. Click 'Submit Now'
4. You will receive a receipt of your transaction in your email, stating that your transaction is currently being processed

![Topup Confirmation Dashboard](images/topup_confirmation_dashboard.png)

![Topup Confirmation Email](images/topup_confirmation_email.png)

5. You will receive an email confirming whether your top up is success or failed

![Success Failed Confirmation](images/success_failed_confirmation.png)


## Withdrawal

When you want to withdraw, do the following steps:

1.  Go to Transaction Report -> Account Statement
2.  Click Withdraw
3.  Fill in the amount that you want to withdraw

![Withdrawal Top Up](images/withdrawal_topup.png)

4.  Choose your withdrawal type. You can pick one from the following options:

	- Instant with admin fee -> This means that your withdrawal will be processed and arrive into your receiving bank real-time. If the amount to be withdrawn is <= IDR 50 million and the receiving banks are BCA, BRI, BNI, Mandiri, Permata, DBS and CIMB Niaga, you can choose this option. You will be charged an admin fee if you choose this option
	
	- Manual -> This means that your withdrawal will be processed up to 2 business days. If the amount to be withdrawn is > IDR 50 million OR the receiving banks are not BCA, BRI, BNI, Mandiri, Permata, DBS or CIMB Niaga, you have to choose this option. You will NOT be charged an admin fee if you choose this option.

### Setting Up Auto Withdrawal Process

If you want to set up an **Auto Withdrawal** periodically, go to Settings -> Auto Withdrawal.

![Auto Withdrawal](images/auto_withdrawal.png)

Here's how you can configure the auto withdrawal settings;

Field Name | Description|
------ | ----------- | 
Auto Withdrawal Schedule | The schedule of your auto withdrawal. Options available: Daily, Weekly, Bi-Weekly, Monthly
Start Date | Start date of your auto withdrawal schedule
Ends| Options available: Never -> if the auto withdrawal will go on for an indefinite time, By Date -> if the auto withdrawal will end on a specific date. If you choose this option, you need to fill in the date on which you plan to end the auto withdrawal process
Amount | Amount to be automatically withdrawn. Options available: Maximum amount -> Withdraw the maximum available balance, Specified Amount -> custom specified amount. Note: Maximum Amount is recommended for Auto Withdrawal transactions as withdrawals will not be processed if the specified amount is greater than the OY balance when the withdraw scheduler runs
Withdrawal Type | Options available: 1) Instant, or 2) Manual. 
Email | An email we will send the notification to. Use (;) between email to differentiate them (Max. 5 emails can be inputted)

## Transaction Report - Settlement Report

Settlement Report stores the list of transactions corresponding to payment methods that are not settled on a real-time basis (delayed settlement). For example, if for VA BCA the settlement time is H+2, each new VA BCA transaction performed by your customers will appear on the Settlement Report.

To access the Settlement report;
- Login to Dashboard
- Go to Transaction Report -> Settlement Report

![Settlement Report](images/settlement_report.png)

The Settlement Report consists of the following information;

- Total Amount to be Settled Today: This tells you the sum of amount scheduled to be settled to your account statement balance today
- Total Delayed Settlement Amount: This tells you the sum of amount not yet settled to your account statement. (the settlement status is still not SUCCESS)
- The Settlement Transaction List Table

Field Name | Description | Example
------ | ----------- | -----------
Transaction Date | The date on which your customer performs the transaction| 11 May 2021
Transaction Time | The time at which your customer performs the transaction| 17:44:09
Transaction ID | A unique transaction ID given by OY |   d4b26687-34b9-43d3-9d08-af440bcbaca7
Partner Transaction ID | A unique transaction ID that is assigned by you for a given transaction | TXID_001
Product | The product associated with a given transaction. This will be filled with VIRTUAL_ACCOUNT if the transaction comes from Virtual Account Aggregator product, or PAYMENT_CHECKOUT if the transaction comes from Payment Checkout product | VIRTUAL_ACCOUNT
Payment Method | The payment method associated with a given transaction. Possible values: VA [Bank Name], CARDS, QRIS, EWALLET SHOPEEPAY| VA BCA
Transfer Amount| The transaction amount (before getting deducted with admin fee | +Rp 10.000
Admin Fee| The admin fee associated with a given transaction | -Rp 1.000 
Total Amount| The transaction amount that has been deducted with admin fee | +9,000 
Settlement Date| The scheduled settlement date for a given transaction | 12 May 2021 
Settlement Time| The scheduled settlement timestamp for a given transaction | 15:00:00
Settlement Status| The settlement status for a given transaction. Possible values: WAITING (if the amount is not yet settled to your account statement balance), SUCCESS (if the amount has been settled to your account statement balance). | SUCCESS

If the Settlement Status of a transaction is still WAITING, it will not yet appear as a row in your Account Statement report and the amount will not yet be added in your Account Statement balance.

If the Settlement Status of a transaction is already SUCCESS, it will appear as a row in your Account Statement report and the amount will be added in your Account Statement balance.

### Callback for Delayed Settlement (Non-Real Time Settlement)

If your settlement is non-real time, for every transaction whose payment method is settled H+>0, you will receive two callbacks with details as follows:

1. 1st Callback -> To be sent after your customer successfully executes the transaction. For example, if your customer executes the transaction on 11 May 2021 at 14:00:00, that is also when we send the 1st Callback to you. In the 1st callback, the settlement status is set to WAITING (because it is not yet settled to your Account Statement balance)
2. 2nd Callback -> To be sent after the settlement status is changed from WAITING into SUCCESS. For example, if the settlement status is changed into SUCCESS on 12 May 2021 at 15:00:00, that is also when we send the 2nd Callback to you. In the 2nd callback, the settlement status is SUCCESS

### Capability to Export and Filter the Settlement Report

Export: You are able to export/download the settlement report in CSV, PDF, and XLSX.

Filter: You are able to filter the settlement report by transaction date (range), product, payment method, settlement date (range), and settlement status

## Notification

You can enable or disable notification settings for disbursement products if you have a super admin or admin role: 
1. Login to dashboard https://business.oyindonesia.com/
2. Go to Settings -> Notification 
![Notif Disbursement - 1  Initial](https://user-images.githubusercontent.com/79620482/126457509-ca20c24b-9277-4be4-943e-801b79806e65.png)

1. Choose whether or not you want notifications enabled or disabled for Bulk, API, or scheduled disbursements.	
   a. Enable Notification: Email notification will be sent for pending, failed and success transactions. 
   b. Disable Success Notification: email notification will only be sent for pending and failed transactions.
2. The email field:  allows the user to add, remove, and edit email notification receivers in this column, which can hold up to three email addresses.
3. Click ‘Save Changes’

