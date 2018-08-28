# Sensibo Bitbar Plugin

### This plugin provides a quick access to your [Sensibo](https://sensibo.com/) Pods. The plugin requires [jq](https://github.com/stedolan/jq) and obviously, [Bitbar](https://getbitbar.com/).

An API key is required in order for this plugin to function. Your API key can be set using the **API_KEY** variable inside the plugin and you're good to go.

And because i know that an image is worth a thousand words, here's how it looks in your menubar:

<p align="center">
<img src="https://i.imgur.com/uy3ynSp.png" alt="Sensibo Bitbar Preview" />
</p>

The plugin automatically lists all your available PODS with an option turn it on and off.

The data currently shown:

 - current temperature
 - humidity
 - swing
 - fan level

### Installing (*manually* for now until the plugin is accepted into their official repo)

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
