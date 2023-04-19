# MMM-ZAPTEC 

This is a Magic Mirror module for connecting to the ZAPTEC API
and showing information on your Mirror.



[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J3J2EARPK)


Irritation 1: Show zaptec chargers and the status of them.

![image](https://user-images.githubusercontent.com/8579922/233061820-5e3606fb-693b-4d10-bdaf-df3b4048f9a5.png)


To get your api token go [here](https://api.zaptec.com/help/index.html)
the authorize
and go to /api/chargers and > try it out > execute 
you will get an curl line with an Bearer: copy that token.


How to install:
```
cd MagicMirror/modules
```
```
git clone https://github.com/PierreGode/MMM-ZAPTEC.git
```
In MagicMirror/config/config.js



```
{
  module: "MMM-ZAPTEC",
  position: "bottom_right",
  header: "Zaptec Laddare",
  config: {
    bearerToken: "API TOKEN",
    updateInterval: 60000 // update every minute
  }
},
