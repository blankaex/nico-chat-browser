# nico-chat-browser
A web app that you can use as a browser source with your favourite streaming software to get nico nico style comments. [Original by Kuromachii](https://github.com/Blackksoulls/nico-chat-browser).

I made a fork so that I could run it locally, partially to ease the load on his server but mostly so that I could edit the css. Also partially so that you can do the same without doing all the work I did but mmostly so that I can do the same without having to do all the work I did again when I inevitably lose the files. 

## Preview

See `preview.webm`.

## Usage
Go [here](http://nico.kuro.ml/) to authorize the app and get your token, then edit `/js/kuro.js` and set the `token` var to be equal to a string containing that value (you can probably use twitch's oauth thing but I couldn't be bothered checking). Then just load up `chat.html` and you should be good. I assume if you want to modify this then you know what you're doing.