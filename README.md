# OCR Bot [@Image To Text Bot](https://t.me/ST_IMAGETOTEXTBOT)

> A star ⭐ from you means a lot to us!

<p align="center"><a href="https://www.github.com/STBOTZ/OCRBot"><img src="https://telegra.ph/file/821adfb267fcd7c5e6b5b.jpg" width="5000"></a></p>

Telegram bot to extract text from image

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/STBOTZ)

## Usage

### Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/STBOTZ/OCRBot)

1. Tap on above button and fill `API_ID`, `API_HASH`, `BOT_TOKEN`.
2. Then tap "Deploy App" below it. Wait till deploying is complete (will take atmost 2 minutes).
3. After deploying is complete, tap on "Manage App"
4. Check the logs to see if your bot is ready!

### Local Deploying

1. Clone the repo
   ```markdown
   git clone https://github.com/STBOTZ/OCRBot
   ```

2. Now head to [this page](https://github.com/UB-Mannheim/tesseract/wiki) and install Tesseract installer. 
   
3. Use it to  install Tesseract and copy the PATH to where it is installed. 

4. Now uncomment out [this line](https://github.com/STBOTZ/OCRBot/blob/master/OCRBot/ocr.py#L8). Fill the inverted commas with your own PATH.
   
5. Edit `Config.py` and fill the needed variables

6. Enter the directory
   ```markdown
   cd OCRBot
   ```
  
7. Install all requirements using pip.
   ```markdown
   pip3 install -r requirements.txt
   ```

8. Run the file
   ```markdown
   python3 main.py
   ```

## Environment Variables

#### Mandatory Vars

- `API_ID` - Get this from [my.telegram.org](https://my.telegram.org/auth)
- `API_HASH` - Get this from [my.telegram.org](https://my.telegram.org/auth)
- `BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather)

## Functions

> More features soon, this is a minimal example :)

1) Extract text from image
2) Send any amount of images at once, and it will work the same.

## To-Do

> That's on you mainly...

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

## Credits

- [Dan Tès](https://github.com/delivrance) for his [Pyrogram](https://docs.pyrogram.org) Library

## Support

Channel :- [@STBOTZ](https://t.me/STBOTZ)

Group Chat :- [@STBOTZ SUPPORT](https://t.me/ST_BOTZ)

