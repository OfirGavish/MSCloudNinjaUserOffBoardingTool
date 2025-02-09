# MS Cloud Ninja User Offboarding Tool

A powerful and user-friendly Windows desktop application designed to streamline the process of offboarding users from Microsoft 365 environments. Built with .NET 8.0 and Microsoft Graph API, this tool provides a comprehensive solution for IT administrators to manage user offboarding tasks efficiently.

## Features

- **User Management**
  - Search and filter users from your Microsoft 365 environment
  - Select multiple users for batch processing
  - Modern dark-themed UI for comfortable usage

- **Offboarding Actions**
  - Disable user accounts
  - Remove users from Global Address List (GAL)
  - Remove users from all groups
  - Remove user licenses
  - Update manager for reporting employees
  - Revoke user sign-in sessions

- **Security & Compliance**
  - Secure authentication using Microsoft Graph API
  - Detailed logging of all operations
  - Error handling and operation status tracking
  - Progress tracking for batch operations

## Prerequisites

- Windows operating system
- .NET 8.0 Runtime
- Microsoft 365 administrator account with appropriate permissions (User Administrator Role will do)

## Installation

To get started with the MS Cloud Ninja User Offboarding Tool:

1. Download installer from:
   https://storage.mscloudninja.com/MSCNUserOffBoardingTool_Installer.exe
2. Execute the installer and follow the guided installation process
3. Launch the application from your Start Menu or Desktop shortcut

Note: The tool requires .NET 8.0 Runtime and a Windows operating system. Administrator privileges are recommended for installation.

## Usage

1. **Authentication**
   - Launch the application
   - Click on the authentication button to sign in with your Microsoft 365 administrator account
   - Grant the necessary permissions when prompted

2. **User Selection**
   - Use the search box to find specific users
   - Select one or multiple users from the grid
   - Users can be sorted by clicking on column headers

3. **Action Selection**
   - Choose the desired offboarding actions using the checkboxes:
     - Disable User Account
     - Remove from GAL
     - Remove from Groups
     - Remove Licenses
     - Update Manager
     - Revoke Sign-in

4. **Execution**
   - Click the "Execute" button to start the offboarding process
   - Monitor progress through the progress bar
   - View status updates in real-time
   - Check the logs for detailed operation information

## Logging

The application maintains detailed logs of all operations for auditing and troubleshooting purposes. Log files are stored in:
```
%LocalAppData%\MSCloudNinja\Logs\app_YYYYMMDD.log
```
Where:
- `%LocalAppData%` is your Windows local app data folder (typically `C:\Users\<YourUsername>\AppData\Local`)
- `YYYYMMDD` is the current date (e.g., `app_20250130.log`)

Each log entry includes:
- Timestamp with millisecond precision
- Operation details
- Error information (if applicable)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

## Support

For support, please open an issue in the GitHub repository or contact the development team.

## Acknowledgments

- Built using Microsoft Graph API
- Powered by .NET 8.0
- Created by MS Cloud Ninja
