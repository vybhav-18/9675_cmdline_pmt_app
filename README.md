# 9675_cmdline_pmt_app

this repository is for commandline payments application.
## Requirements: Create design (class diagram and schema design) and write working code for a command-line payment application that supports the following use cases.

### Allow users to create accounts via their phone number and password.
>**RegisterUser** _[phone_number] [password]_

### Allow users to update their profile details.
>**UpdateUser** _[user_id] [name] [email] [phone_number]_

### Send money to another user of the application. (Send money to another phone number)
**CreateTransaction PAYTM** _[from_user_id] [to_user_id] [amount]_

### Send money to a bank account.
>**CreateTransaction BANK** _[from_user_id] [account_number] [ifsc_code] [amount]_

### Allow users to make payment for the transaction via Card/ UPI/ Netbanking
>**MakePayment** _[transaction_id] [payment_method] [... details related to payment method ...]_

### Allow users to refund a transaction. The refund amount will go to the original source.
>**RefundTransaction** _[transaction_id]_

### Allow users to view transaction history.
>**ViewTransactionsHistory** _[user_id]_
