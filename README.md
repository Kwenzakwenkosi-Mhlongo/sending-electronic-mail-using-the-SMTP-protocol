# sending-electronic-mail-using-the-SMTP-protocol
Project Description

This project focuses on understanding and implementing the Simple Mail Transfer Protocol (SMTP) by developing a custom e-mail client. Although many modern communication platforms exist today, e-mail remains a widely used and essential method of communication. The aim of this practical is to explore how the underlying protocol used to send e-mail operates at a technical level.

The project involves creating a GUI-based Java application that functions as an SMTP mail client. When the application starts, the user is presented with a graphical user interface that allows them to enter the SMTP server host name and port number they wish to connect to. The interface also includes labeled text fields for the sender’s name, recipient’s name, and a text area for the email message content. A Send button is provided to initiate the email transmission.

When the user clicks the Send button, the application communicates directly with the SMTP server by following the SMTP protocol commands implemented from scratch. The application then displays a status message to inform the user whether the email was sent successfully or if an error occurred. All errors are handled and presented in a user-friendly manner to ensure clarity and ease of use.

For testing purposes, the application can be used with SMTP testing servers such as SMTPBucket or Papercut SMTP, although using these tools is not mandatory. A key requirement of this project is that the JavaMail API (javax.mail package) is not used. The SMTP protocol must be implemented manually, demonstrating a clear understanding of how email transmission works at the protocol level.
