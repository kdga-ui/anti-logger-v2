This script is meant to be used in a roblox executor, it protects you against ip logging scripts, obfuscated because of how long it took me and I dont want it to be skidded, hopefully you can understand

# RUN THIS BEFORE ANY OTHER SCRIPTS
## if you do not run it before the ip logger, it will not work
### for more customization, use this script
```lua
getfenv().Custom_Blacklist = {
    -- example "https://hi.com"
} 

getfenv().whitelist = {} -- example "https://google.com
getfenv()._blockwebhook = true
getfenv().DEBUG = false

loadstring(game:HttpGet("https://raw.githubusercontent.com/kdga-ui/anti-logger-v2/refs/heads/main/Anti%20logging.lua"))()```
