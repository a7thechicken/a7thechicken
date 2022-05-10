local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("scripts", "Ocean")

local sc = Window:NewTab("scripts")

local Section = sc:NewSection("all sscripts")

Section:NewButton("basbousa", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Basbousa1/my-roblox-scripts/main/Roblox-PopItTrading%20script.lua"))()
end)

Section:NewButton("AntiAfk", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/KazeOnTop/Rice-Anti-Afk/main/Wind", true))()
end)

local p = Window:NewTab("player")

local Section = p:NewSection("player stuff")

Section:NewSlider("walkspeed", "SliderInfo", 250, 30, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

local st = Window:NewTab("settings")

local Section = st:NewSection("all settings")

Section:NewKeybind("toggle UI", "KeybindInfo", Enum.KeyCode.F, function()
	Library:ToggleUI()
end)




