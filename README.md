# ConnectBoxDOCSIS-3.0

The Connect Box is the worldwide most compact EuroDOCSIS 3.0 Voice Gateway which provides the ideal all-in-one wired and wireless solution, designed for your home, home office, or small business/enterprise.

It can be used in households with one or more computers capable of wireless connectivity for remote access to the wireless gateway.

================================================================

Exploiting Router Connect Box EuroDOCSIS 3.0 Voice Gateway

This is a Proof of Concept on how to get the Connect Box DOCSIS 3.0 Voice Gateway router admin credentials when sniffing the HTTP traffic packets.
This is router that it was tested is in Poland by UPC internet service provider but we know this company provides service in many outher country in EU.

Using Wireshark for packet capture and a Firefox browser to access the router management panel, it was possible to realize that admin credentials were passed in clear text, and not applied nothing of security, we could said the simple Basic Authentication (ie.Base64-encoded), as shown in the images below:

![Victim1](https://user-images.githubusercontent.com/31785433/71374644-bf7d6680-25bb-11ea-853f-44db27933398.png)


