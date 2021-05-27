Happy Birthday

A Happy Birthday animation design in CSS3, HTML5.

URL: http://ayusharma.github.io/birthday/

Technology Used: HTML5 CSS3 jQuery  GNU/Linux Digital Ocean as VPS GIMP

# Setup

## If you have python installed:
```
cd Birthday
```

&& 
### Python2-
```
python -m SimpleHTTPServer 8081
```
### Python3-
```
python -m http.server 8081
```

visit http://localhost:8081 in your browser.
<br>
To stop server press Ctrl+C in Keyboard

## If you have nodejs installed
```
npm install
```
&&

```
npm run server-node
```
visit http://localhost:8081 in your browser.

> <b>Modify the configuration of config.js to make a super creative web page for your beloved. Happy birthday, if you like, fork or star~</b>


## TODO
* [x] Each line of blessing text can be accompanied by a picture
* [] Pictures support rotation

### config.js description
> Reminder: Every sentence, every picture address, every button text line must end with **English comma** at the end!
```text
var config = {
 // The length of the sentence can be any, you can write ten sentences, 20 sentences are fine
 // Try not to exceed 15 words in each sentence, otherwise the display effect may not be very good
 texts: [
 "Give it to me",
 "Beloved Little Cutie",
 "Today is your birthday",
 "This is where we are together",
 "It's the third birthday",
 "Last year's birthday",
 "Remember what I ate at Wang Po Chuan Chuan",
 "I want to eat well this year",
 "I want to feed my cute pigs",
 "Then take away",
 "YAMI~~",
 ],
 /**
 * imgs can be left blank, but if you want to fill in, you must follow the format below
 * "Correspond to the above text, it must be exactly the same": "Picture address, you can put the picture in the imgs folder"
 * E.g
 * "Beloved little cute": "./imgs/xiaokeai.jpg"
 *
 * If you don’t want a picture, just write two slash comments at the beginning of each line. For example, the picture below "Today is your birthday" will not be displayed :)
 * Tip: The picture is best to use a square or close to a square, it looks better
 */
 imgs: {
 "Beloved little cute": "./imgs/xyz.png",
 // "Today is your birthday": "./imgs/xyz.jpg",
 },
 // Button text description, the following is the default button text, in English, you can change it to your favorite text
 desc: {
 turn_on: "Start",
 play: "Music",
 bannar_coming: "Color",
 balloons_flying: "It seems that there are few things",
 cake_fadein: "Cake?",
 light_candle: "Candle?",
 wish_message: "Happy Birthday",
 story: "A MESSAGE FOR YOU",
 }
};
```



## QA
> How to modify the music?
> 
> Answer: Overwrite the `hbd.mp3` under the `assets` directory with your own mp3 music files, remember to have the same name after overwriting!
