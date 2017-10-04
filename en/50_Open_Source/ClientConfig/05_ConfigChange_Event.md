ClientConfig exposes a system event `ClientConfig_ConfigChange` event since v1.4. 

It's fired when a setting is edited or removed. 

It can be used to listen to changes in the configuration to regenerate caches, or things like CSS files that incorporate values from ClientConfig.
