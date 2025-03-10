# Base

## Overview

The `base` app is designed to contain essential configuration data for your website. This app simplifies the management of configuration settings, ensuring that all necessary parameters are easily accessible and editable. Key components include environment variables stored in the `.env` file and customizable settings defined in `settings.py`.

- **Environment Configuration**: Store sensitive data such as email passwords, database URLs, and other configuration variables securely in the `.env` file.
- **Editable Settings**: Modify the `settings.py` file to adjust various parameters according to the specific needs of each app.
- **Centralized Management**: All configuration data is centralized in the `base` app, making it easy to manage and update.

## Installation

To install the `base` app, follow these steps:

1. Add Submodule:
    ```bash
    git submodule add https://github.com/Yaso2Go/base.git base/
    ```

2. Initialize the submodule:
    ```bash
    git submodule init
    ```

3. Configure your environment variables in the `.env` file.

4. Update the `settings.py` file to reflect your website's configuration.

### Compatibility
The `base` app is designed to be compatible with all components of your project. It does not conflict with any existing configurations or applications, as it solely contains configuration data. Other apps can easily place their configuration information within the `base` app, ensuring a seamless integration across your project.
