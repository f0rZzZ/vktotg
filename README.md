# vktotg/vktolocal
Sends all your vk.com music to telegram channel or save it to local folder

# Run

>**Hint:** If you'll use mobile phone as login when launching for the first time,
       you can just enter mobile phone and leave password empty in your next logins.
       User's info saved to vk_config.v2.json

 - Windows: 
For save music to Telegram channel
 open `vktotg.exe`
 
 - Linux: 
For save music to Telegram channel
 ```bash
 pip3 install bs4 vk_api telethon request
 python3 vktotg.py
 ```
 For save music to local folder:
  ```bash
 pip3 install bs4 vk_api
 python3 vktolocal.py
 ```

Vk to Telegram description:
Downloads all your music locally to folder `Music <your_id>` and send to private Telegram channel.
You can provide specific `user_id` as argument when launching from command line to dowload audio of this user. Just be sure that you have access to them

Example:
 `python3 vktotg.py 28452705`

Vk to local description:
Similar you can save your music ONLY locally. Use for this vktolocal.py with same options.

Example:
 `python3 vktolocal.py 28452705`
