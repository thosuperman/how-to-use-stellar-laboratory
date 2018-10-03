################################################################################
Accounts
################################################################################

Create an account
--------------------------------------------------------------------------------

https://www.stellar.org/laboratory/#account-creator This is a web tool that allows you to create and fund accounts. It will also allow you to fund that account on the testnet.

Click to **Generate keypair**:

..  image:: ./img/generate-keypairs.png
    :align: center

An account is just a **public/private** keypair, like so:

..  image:: ./img/account.png
    :align: center

Account access is controlled by public/private key cryptography. For an account to perform a transaction–e.g., make a payment–the transaction must be signed by the private key that corresponds to that account’s public key.

Friendbot: fund a test network account
--------------------------------------------------------------------------------

Make sure that you have “test” selected in the upper right. This is critical!

..  image:: ./img/network-options.png
    :height: 66px
    :align: center

Then fund it, like so:

..  image:: ./img/friendbot.png
    :align: center

Check balances of an account
--------------------------------------------------------------------------------

Go to `Endpoint Explorer <https://www.stellar.org/laboratory/#explorer?resource=accounts&endpoint=single&network=test>`_

..  image:: ./img/endpoint_balance.png
    :align: center

..  image:: ./img/endpoint_balance_result.png
    :align: center
