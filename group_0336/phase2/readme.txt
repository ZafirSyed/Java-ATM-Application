This is a simulation of an Automated Teller Machine (ATM).

The path to get to the main class to run the program: phase2\main\ATM\MainOperation\ATM.java

In the main folder, in the MainOperation package, ATM.java class. Right click, Run main().





The following is a documentation of the ATM.

When the program starts:
You will be introduced to the start of the program and prompted to enter your credentials.
There are 3 ways to login and make the ATM run a certain way, the three are below and explained:

Note: When the ATM's time reaches midnight the program update the date.
Note: When the end of the month is reached your savings account will incur by a factor of 0.1
Note: All accounts have a 4 year activated period, after which you must renew the appropriate account

1) Logging in as the Bank Manager
Username: bm    Password: bm
    A bank manager is of highest authority of the ATM. A bank manager has 4 options: Manage Account, Manage User,
    Undo Transaction, and Restock ATM.

    Features include, being able to undo any transaction for any user. Creating joint accounts. Creating new
    users as well as new accounts. Also, can promote a bank user to a bank worker, or demote a bank worker to a
    bank user. The bank manager can also restock the ATM's bills when they are to low (refer to the note at the bottom).
    Lastly, a bank manager can renew, deactivate, or activate any account for any user on the system.

    In real life a person would meet at a bank and request for a new account or user login so we designed it for the
    BankManager to do, there is no option in the user main menu.

    Note: When a new user is created that user will only have a chequing account available to start and will be able
    to add any account in the future.

    Note: The BankManager will also be alerted through the alerts.txt file as well as indications of low bills when any user
    transactions occur. Can be thought of as, the User interacts with the ATM and the ATM talks to the BankManager.

    Note: Any transaction includes a paid bill, withdrawal, deposit, transfer, and anything bought from the online store.

2) Logging in as Valid User
    As a valid user you will be brought to the main menu that allows you to withdraw, deposit, pay bills,
    transfer funds, access the online store, exchange currency through the exchange booth, buy and sell stocks when
    managing your portfolio, manage your account(s), and view the FAQ.

        1. Paying Bills: When you want to pay bills a list of your accounts and their names will be displayed.
        Then following the prompts enter the name of the account you want to pay bills for, the name of the recipient
        (who you are paying bills to, third party), and the amount that has to be paid. This transaction will be recorded
        in the transaction.txt file

        2. Transferring Funds: When you want to transfer funds you are given two options, between your accounts, and to another
        user from the main menu.
            Transfer to your Account:
            When you want to transfer funds between accounts, you will be given the list of your accounts. Then following
            the prompts enter the name of the account you are transferring funds FROM, the account name of the account you want
            to transfer funds INTO, and the transfer amount.

            Note: if you need another account, the BankManager or a bank worker can create a new account for you.

            Transfer to Other User:
            When you want to transfer funds to another user, you will be given a list of all valid users in the system. Then
            following the prompts enter the name of the user you want to send funds TO, the name of your account you want to
            transfer funds FROM and the transfer amount.

        3. Withdrawing Funds: When you want to withdraw funds, you will be given a list of your accounts you want to withdraw
        funds from. Following the prompts, you will enter the name of the account you want to withdrawal from, the amount
        of funds to withdraw ($20, $50, $100, $200, or $500), and the bill type you want the funds in (5, 10, 20, 50).
        If there are not enough funds in the specified account or enough of the bill types specified you will notified
        by the system.

        4. Depositing Funds: When you want to deposit funds, you will be given a list of your accounts you want to deposit
        into. Following the prompts, enter the name of the account you want to deposit into and the amount you want to
        deposit.

        Note: only multiples of $5 will be accepted, you will be notified by the system otherwise, and your
        primary chequing account will be the account that the funds will be deposited into. Refer to the Manage Accounts
        options to see how to set which chequing account you want as your primary chequing account.

        Note: For the above operations, if you want a new account type, the BankManager or a bank worker
        will be able to create a new account for you.

        5. Managing Account: When you want to manage your account you can select from a drop-down list of your
        accounts where you can view your net total, balances, transactions for the specified account and change
        which of your chequing accounts is your primary chequing account. You can also change your password for
        your credentials login.

        6. Store: The online store is where you can shop for items. Your default chequing account is how you pay for
        items.

        Note: All items bought in store are recorded as a pay bill transaction in the transaction.txt file.

        7. Manage Portfolio: You are able to transfer funds into your portfolio from your default chequing account. With
        your funds you are able to buy stocks from 100 tickers. The shares update every 10 seconds. You can also sell your
        shares and then able to transfer an amount of money back into your default chequing account from your portfolio.

        8. Currency Exchange: Designed as a third party exchange booth, you can select from your accounts you want to
        exchange funds FROM, the amount you want to exchange, and the currency type you want to exchange into. The base
        currency that all exchanges are rated from is the Canadian Dollar. All exchanges are recorded in the outgoing.txt file

        9. FAQ: Frequently asked questions -- more on what to do while using the ATM

3)Logging in as a Bank Worker
    A bank worker is user that can be promoted from a user or demoted to a user.
    A bank worker has all the same options as a normal user but with an added option, Bank Options, that can only
    be accessed by a bank worker.

    The bank options can allow a bank worker to create a new user for the ATM or any account for a user.