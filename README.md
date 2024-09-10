# MageBytes Base Module

## Overview

`MageBytes_Base` is a foundational module created by MageBytes that provides essential functionalities required by other MageBytes modules. This module serves as a base dependency for various MageBytes extensions, ensuring compatibility and shared resources across different modules.

## Features

- Provides foundational code and utilities used by other MageBytes modules.
- Centralized configuration and common functionalities for consistent integration with MageBytes extensions.
- Ensures smooth interoperability and compatibility with other MageBytes modules.

## Requirements

- **Magento Version**: 2.x
- **PHP Version**: Compatible with your Magento version (PHP 7.4, 8.1, 8.2 or 8.3)

## Installation

### Manual Installation

Follow these steps to install the MageBytes_Base module manually:

1. **Download the Module:**

   Download the latest version of the `MageBytes_Base` module from the MageBytes repository.

2. **Extract the Files:**

   Extract the downloaded files and place them in the `app/code/MageBytes/Base` directory of your Magento installation.

3. **Enable the Module:**

   Run the following commands in the Magento root directory to enable the module:

   ```bash
   php bin/magento module:enable MageBytes_Base
   php bin/magento setup:upgrade
   php bin/magento setup:static-content:deploy
   php bin/magento cache:clean
   php bin/magento cache:flush
   ```
   4. **Support**
- For any issues or support requests, please contact MageBytes:
- **Email:** info@magebytes.com
- **Website:** [MageBytes](https://www.magebytes.com)
