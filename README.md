# BetterMadeSecurity
Currently in **BETA (v1.0.2)**.

## Booting BetterMadeSecurity
```lua
local BMS = loadstring(game:HttpGet("https://raw.githubusercontent.com/DarkDrake666/BetterSecurity/MadeByMe/MainModule.lua"))()
```



## Activating
```lua
local Settings = {
    BlockScriptLogging = true,
    HideUsernameFromScripts = true,
    BlockScriptKicks = true,
    BlockGameKicks = true,
    BlockScriptChatRequests = true,
    
    -- BROKEN: 
    
    ConfirmScriptFileMaking = false, -- this could break a little amount of scripts as it uses a function that yields.
    ConfirmScriptFileDeleting = false, -- this could break a little amount of scripts as it uses a function that yields.
    ConfirmScriptFileAppending = false -- this could break a little amount of scripts as it uses a function that yields.
}

BMS.fire(Settings)
```

## Stopping
```lua
-- In a new script, still booting BetterMadeSecurity
BMS.stop()
```

## Resuming
```lua
-- In a new script, still booting BetterMadeSecurity
BMS.resume()
```

# Thats all!
