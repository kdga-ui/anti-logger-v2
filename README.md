This script is meant to be used in a roblox executor, it protects you against ip logging scripts, obfuscated because of how long it took me and I dont want it to be skidded, hopefully you can understand

# RUN THIS BEFORE ANY OTHER SCRIPTS
obviously if you run something with a logger before the thing that Stops the logger, its not gonna stop it

## if you do not run it before the ip logger, it will not work
```lua
getfenv()._blockwebhook = false
getfenv().DEBUG = false

loadstring(game:HttpGet("https://kdga-ui.github.io/scripts/anti-logger.lua"))()
```
