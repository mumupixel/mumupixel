# Mumupixel

# Feature

- [x] Auto Claim Point
- [x] Auto Claim Daily Reward
- [x] Suppport Multi Account
- [x] Input data manually (no login require)
- [x] Auto Upgrade Pets (Optional)
- [x] Auto Claim Cipher/Daily Combo
- [x] Auto Buy New Pet

# How to Use

1. Make sure your computer was installed python and git.

2. Clone this repository

3. Go to pixelverse
   ```
   cd pixelverse
   ```
4. Install python library

   Windows

   ```
   pip install -r requirements.txt
   ```

   or

   ```
   python -m pip install -r requirements.txt
   ```

   Linux

   ```
   pip3 install -r requirements.txt
   ```

   or

   ```
   python3 -m pip install -r requirements.txt
   ```

5. Get Telegram data

   1. Active web inspecting in telegram app, How to activate follow the video
   2. Goto pixeltap bot and open the apps
   3. Press `F12` on your keyboard to open devtool or right click on app and select `Inspect`
   4. Goto `console` menu and copy [javascript code](#javascript-command-to-get-telegram-data-for-desktop) then paste on `console` menu
   5. If you don't receive error message, it means you successfully copy telegram data then paste on `data.txt` (1 line for 1 telegram data)

   Example telegram data

   ```
   query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
   ```

   6. If you want to add more account. Just paste telegram second account data in line number 2.

   Maybe like this sample in below

   ```
   1.query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
   2.query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
   ```

6. Run the bot

   Windows

   ```shell
   python bot.py
   ```

   Linux

   ```shell
   python3 bot.py
   ```

## Contact

- [Twitter](https://x.com/mumupixel)
