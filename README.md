
# MTN momo API Integration(Sandbox)

## Overview

This project demonstrates integration with the MTN Sandbox API for mobile money transactions. It covers various functionalities such as creating API users, generating API keys, requesting payments, checking payment status, and handling callbacks.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Usage](#usage)
3. [Files and Functions](#files-and-functions)
4. [License](#license)

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/LeloKarma/Mtn-momo-api.git
   ```

2. Ensure you have PHP installed on your system.

3. Obtain an MTN Sandbox subscription key and replace the `$secodary_key` variable in the PHP files with your subscription key.

4. Run each PHP file in sequence to perform various actions with the MTN Sandbox API.

## Usage

The project includes several PHP files, each serving a specific purpose:

- `createapiuser.php`: Creates an API user with the MTN Sandbox API.
- `createapikey.php`: Generates an API key for the created API user.
- `createaccesstoken.php`: Generates an access token required for making requests to the MTN API.
- `requesttopay.php`: Initiates a payment request to a specified phone number.
- `getbalance.php`: Retrieves the balance information.
- `requesttopaystatus.php`: Checks the status of a payment request.
- `callback.php`: Handles callbacks from the MTN API.

Each file includes instructions on how to use it within its comments.

## Files and Functions

- **createapiuser.php**: Contains the function `generate_uuid()` to create a UUID for the API user creation request.
- **createapikey.php**: Includes the function to obtain the API key after creating the API user.
- **createaccesstoken.php**: Handles the generation of the access token required for authorization.
- **requesttopay.php**: Initiates a payment request to the specified phone number.
- **getbalance.php**: Retrieves the balance information for the account.
- **requesttopaystatus.php**: Checks the status of a payment request.
- **callback.php**: Handles callback requests from the MTN API.

## License

This project is licensed under the [MIT License](LICENSE).
