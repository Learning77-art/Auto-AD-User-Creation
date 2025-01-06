# Auto-AD-User-Creation

**Auto-AD-User-Creation** is a PowerShell script designed to automate the process of creating user accounts in **Active Directory**. It streamlines user account management for IT administrators by allowing for the creation of individual or bulk user accounts with predefined attributes, including usernames, passwords, email addresses, and more.

This script helps to reduce manual overhead, ensuring faster and error-free user account creation in enterprise environments.

## Features

- Automates the creation of user accounts in **Active Directory**.
- Customizable user attributes such as **Username**, **Password**, **First Name**, **Last Name**, **Display Name**, and **Email Address**.
- Supports **bulk user creation**, saving time when managing a large number of users.
- **Ensures consistency** in user attributes by following predefined templates.
- **Easy to modify** and extend for various user account management needs.

## Prerequisites

Before running this script, ensure you have the following:

- **Active Directory** installed and configured.
- **Windows Server** or **Windows 10** machine with **PowerShell**.
- The **Active Directory Module for PowerShell** installed. If not, you can install it with the following command:

  ```powershell
  Install-WindowsFeature RSAT-AD-PowerShell
