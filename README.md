# Automatic_B-dayEmailSender


This is a Python project that uses the standard smtplib, EmailMessage, and datetime modules, in addition to pandas and openpyxl (these need to be pip installed, as shown below) to send automated birthday emails.

This program reads from an excel sheet that contains all of your friends’ details (see excel sheet format in source code below). It then sends them an email if today is their big day, before making a note in your spreadsheet to say they’ve received their email.

We’ve used the smtplib and EmailMessage modules to create an SSL connection to our email account and message. We’ve then used a pandas dataframe to store spreadsheet-style data within the Python program (an essential skill for data scientists). Finally, we used date formatting with the datetime module’s .strftime() function.
