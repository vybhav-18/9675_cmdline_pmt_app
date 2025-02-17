# 9675_cmdline_pmt_app

this repository is for commandline payments application.
## Requirements: Create design (class diagram and schema design) and write working code for a command-line payment application that supports the following use cases.



### Allow users to view transaction history.
>**ViewTransactionsHistory** _[user_id]_
 *Get Transaction Details*: `GetTransactionDetails` `[transaction_id]`

*Cancel Transaction*: `CancelTransaction` `[transaction_id]`

 *Update Payment Method*: `UpdatePaymentMethod` `[transaction_id] [new_payment_method]`

*Get User Account Balance*: `GetUserAccountBalance` `[user_id]`

*Transfer Funds*: `TransferFunds` `[from_user_id] [to_user_id] [amount]`