# Python-Capstone-Project
Random OTP Generator
OTP Generator and Email Sender
This Python script generates a 6-digit One-Time Password (OTP), sends it to a specified email address, and verifies the OTP entered by the user. It is useful for implementing basic authentication workflows.

Features
Generate OTP: Creates a random 6-digit OTP.

Send OTP via Email: Sends the generated OTP to the user's email address using SMTP.

Verify OTP: Allows users to enter the OTP and verifies it against the sent one.

Retry Mechanism: Users have up to 3 attempts to enter the correct OTP.

Prerequisites
Before running this script, ensure you have:

Python installed on your system (version >= 3.6).

Access to a Gmail account with "App Passwords" enabled for SMTP authentication.

Learn how to set up App Passwords.

The following Python libraries:

random

string

smtplib

These libraries are part of Python's standard library and do not require external installation.
