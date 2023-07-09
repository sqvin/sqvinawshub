local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("AWS Script Hub │ Made By Sqvin", "Synapse")


--Main 

local Tab = Window:NewTab("Scripts")
local Section = Tab:NewSection("Scripts")

Section:NewButton("Best Script For AWS", "Has 8 Egg Open Feature ETC!", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Kenniel123/Arm-Wrestle-Simulator-Script/main/Arm-Wrestle-Simulator-Script",true))();
end)

Section:NewButton("Second Best Script For AWS", "Event Farms, Visuals ETC", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/limaspeedy/limaspeedy/main/HubLDS"))()
end)
