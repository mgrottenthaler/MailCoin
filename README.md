# MailCoin

MailCoin is a master thesis about extending email with blockchain functionality.

## Abstract

The email system lacks functionality compared to the traditional postal system. This project extends the functionality of email by uniquely linking emails with cryptocurrency transactions. In doing so, various functionalities can be implemented. One possibility is the introduction of email stamps. Like postage stamps they increase the price per email, discouraging spammers from sending spam because it is too expensive. Another system allows non-optional receive confirmations for emails, similar to the service “Einschreiben” by the Austrian “Post AG”. Through this system, the receiver must confirm the reception of an email, to be able to read it. These methods were implemented and then analyzed through self-assessment and third-party feedback. The anti-spam use case has strong requirements and there are too many problems in the current system for it to be successful. The receive confirmations built on this system have lower requirements and are more promising. The solutions developed in this thesis provide a good basis for user-oriented implementations and further research.

## Acknowledgments
This project uses code from:
* btcsuite (https://github.com/btcsuite/)
* soroushjp (https://github.com/soroushjp/go-bitcoin-multisig)