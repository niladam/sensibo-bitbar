# Sensibo QuickControl Bitbar Plugin

### This plugin provides a quick access to your [Sensibo](https://sensibo.com/) Pods. The plugin requires [jq](https://github.com/stedolan/jq) and obviously, [Bitbar](https://getbitbar.com/).

An API key is required in order for this plugin to function. Your API key can be set using the **API_KEY** variable inside the plugin and you're good to go.

And because i know that an image is worth a thousand words, here's how it looks in your menubar:

<p align="center">
<img src="https://i.imgur.com/PyEYqGK.png" alt="Sensibo Bitbar Preview" />
</p>

The plugin automatically lists all your available PODS with the option to turn/schedule them on or off.

The data currently shown:

 - status [ <strong>ON :white_check_mark: / OFF :red_circle:</strong> ]
 - current temperature <strong>25.3 &deg;C / F</strong> (whichever is set) (starting from **1.2.1** the Fahrenheit is correctly displayed thanks to [@RobertD502](https://github.com/RobertD502))
 - humidity [ <strong>💧 43.5%</strong> ]
 - swing [ <strong>stopped</strong> ]
 - fan level [ <strong>auto</strong> ]

### Installing
#### The easiest option is to install it via the [official plugins site](https://getbitbar.com/), but for the ones who need this -- you can quickly read below.

 * Download and install the latest [bitbar](https://getbitbar.com/) app.
 * Set your **plugins folder.**
 * Download [sensibo.60s.sh](https://raw.githubusercontent.com/niladam/sensibo-bitbar/master/sensibo.60s.sh) and place it in your **plugins folder**
 * **Refresh** your Bitbar (or restart) - enjoy.

For a more detailed explanation about plugins, please visit [the official bitbar repo (installing plugins)](https://github.com/matryer/bitbar#installing-plugins)
### Thanks
I'd like to extend a really grateful thank you to the following:

 - Mat Ryer ([@matryer](https://github.com/matryer)) for his amazing work on [bitbar](https://github.com/matryer/bitbar)
 - Stephen Dolan ([@stedolan](https://github.com/stedolan)) for his amazing work on [jq](https://github.com/stedolan/jq) which i use in many of my own personal scripts.
 - Raymond Kuiper ([@q1x](https://github.com/q1x)) for creating his [netinfo](https://github.com/matryer/bitbar-plugins/blob/master/Network/netinfo.60s.sh) plugin allowing me to inspire this current plugin from his :)
 - Omer Enbar ([@omere2](https://github.com/omere2)) for providing the undocumented (yet) functionality of the timer/scheduler
 - [@RobertD502](https://github.com/RobertD502) for the Fahrenheit addition and the Climate React.
