# Whatsapp Bulk Messages Sender With Python
Send bulk WhatsApp messages for marketing without any API for free.

### Join My Discrod Server: [https://discord.gg/yfKCmR7S](https://discord.gg/yfKCmR7S)

## How To Use

### 1. Install Packages
Must install these two packages to start.
- `pip install selenium`
- `pip install webdriver_manager`

### 2. Write Message
Write the message in the `message.txt` file.

### 3. Create Numbers List
Add numbers in the `numbers.txt` file. Add each number in a new line. There is no limit to numbers.

### 4. Change Configs
Change configs on lines `11` to `14` in the `main.py` file
- `login_time` - Time for login (in seconds)
- `new_msg_time` - Time for a new message (in seconds)
- `send_msg_time` - Time for sending a message (in seconds)
- `country_code` - Set your country code
- `action_time` -  Set time for button click action
- `image_path` - Absolute path to you image (Set `None` for text only.)

### 5. Run
Run the `main.py` file.
A chrome browser window will open with a WhatsApp login page. Quickly log in to Whatsapp and sending process will start after a few seconds.

## Note
- I'm not responsible if your WhatsApp account will affect or blocked in any way for this code.
- Please do not use this code to spam or scam people.

## LICENSE
[MIT License](LICENSE)
