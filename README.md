# CDN for George GO and Saifu plugins

This is a simple CDN solution. 
It's used to serve latest builds of react native plugins (extensions) via github pages.  
These plugins are part of Saifu and George GO mobile banking applications.

Phase I - temporary CDN

Phase II - administration via Erste Hub portal, configuration, release management, review ... 


### Plugin descriptor

Each plugin is described in `plugin-descriptor.json` and put to separate folder. 
This descriptor is downloaded by mobile applications and used to provide available plugins.

Steps to update plugin:
- new distribution has to be put to plugin folder
- in `plugin-descriptor.json` increase plugin version and update path if changed
