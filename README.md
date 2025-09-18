# Instagram Booster
<p align="center">
  <img src="https://github.com/user-attachments/assets/e5dd1d56-9879-49a2-9015-5d39c41deb2f" alt="Insta Booster Logo" width="300" height="300">
</p>

<p align="center">
  <strong>A powerful tool to boost your Instagram presence.</strong>
</p>

###

[![GitHub license](https://img.shields.io/github/license/EZIOxtn/Insta-Booster-)](https://github.com/EZIOxtn/Insta-Booster-/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/EZIOxtn/Insta-Booster-)](https://github.com/EZIOxtn/Insta-Booster-/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/EZIOxtn/Insta-Booster-)](https://github.com/EZIOxtn/Insta-Booster-/pulls)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

Instagram Booster is a powerful tool designed to enhance the visibility and engagement of Instagram accounts. It provides automated solutions to increase followers, views, likes, and comments on your Instagram content. This tool is ideal for content creators, influencers, and businesses looking to grow their Instagram presence quickly and efficiently.
![goodprv](https://github.com/user-attachments/assets/e508915a-7e16-4ea2-bc2c-e8ad2c2b57bf)
![Screenshot 2025-03-27 184209](https://github.com/user-attachments/assets/0f52b2f8-f362-404d-839b-f7aeffeecf3f)

## Features

- **Increase Followers**: Automatically add new followers to your account.
- **Boost Post Views**: Increase views on your Instagram posts and stories.
- **Enhance Engagement**: Boost likes and comments on your posts.
- **Customizable Settings**: Tailor the tool to your specific needs with various configuration options.
- **User-Friendly Interface**: Easy to use and navigate, even for beginners.
- **Detailed Reporting**: Track the progress and performance of your campaigns.

## Installation

everything should be installed automatically on start 


```python
   modules = [
    "threading", "time", "requests", "datetime", "os", "base64", "tempfile", 
    "re", "chardet", "typing", "urllib.parse", "prettytable", "concurrent.futures", 
    "httpx", "json", "colorama"
]
for module in modules:
    try:
        __import__(module)
    except ImportError:
        try:
            import os
            os.system(f"pip install {module + "--break-system-packages" if platform.system() == 'Linux' else module}")
        except Exception as e:
            print(f"Failed to install module {module}: {e}")
```



### Prerequisites

- Python 3.x


### Installation Steps

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/instagram-booster.git
   cd instagram-booster
   python3 instabooster.py```

### Advanced Usage

   - you should enter the FAKE insta account , it will be banned  , the target is your main insta account

   -Command-Line Arguments:
   
   --Use the --start flag to start the process directly without modifying the JSON file.
   
   --Set specific fields in the JSON file using command-line arguments:
   
   --python instaboost.py --username your_username --password your_password --target_account target_username --debug
   
   ![startth](https://github.com/user-attachments/assets/4f2171eb-66f0-475c-8bc5-f9cae9a2f5d4)

### Configuration

   -The config.json file contains the following configuration options:
  -username: Your Instagram username.
  -password: Your Instagram password.
  -target_account: The target Instagram account to boost.
  -actions: A dictionary to enable or disable specific actions (follow, like, comment, view).
  -debug: Set to true to enable debug mode for detailed logging.


###
<div align="center">
  <p>
    <img src="https://img.shields.io/badge/Attention-Warning-red" alt="Warning">
  </p>
  <p>
    <strong>Warning:</strong> your instagram account should be Public , and the review flag should be turned off 
  </p>
</div>

###

![pictures](https://github.com/user-attachments/assets/be4ec404-8f4b-4e12-9db9-d8eba52669d3)

 ## Contributing 
 
-We welcome contributions from the community! If you have ideas for new features or improvements, please feel free to open an issue or submit a pull request.


## License

-This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

-For any questions or support, please contact us at:


GitHub: EZIOxtn
Thank you for using Instagram Booster! We hope it helps you achieve your Instagram goals. 🚀
