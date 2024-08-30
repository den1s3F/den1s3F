im bored so here is a new script

local DrRayLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/DrRay-UI-Library/main/DrRay.lua"))()

local window = DrRayLibrary:Load("DENAZ HUB TROLL", "Default")

local tab = DrRayLibrary.newTab("Walkspeed", "ImageIdHere")

tab.newButton("Walkspeed 100", "Change Your Walkspeed", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
end)

tab.newButton("Walkspeed 50", "Change Your Walkspeed", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 50
end)

tab.newButton("Walkspeed 30", "Change Your Walkspeed", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 30
end)

tab.newButton("Ordinary Walkspeed", "Change Your Walkspeed", function()
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
end)

local tab = DrRayLibrary.newTab("Jumppower", "ImageIdHere")

tab.newButton("Jumppower 100", "Change Your Jumppower", function()
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = 100
end)

tab.newButton("Jumppower 70", "Change Your Jumppower", function()
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = 70
end)

tab.newButton("Ordinary Jumppower", "Change Your Jumppower", function()
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
end)

local tab = DrRayLibrary.newTab("Scripts", "ImageIdHere")

tab.newButton("Game Hub V3", "gamehubv3", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/GamerScripter/Game-Hub/main/loader"))()
end)

tab.newButton("Gigachad Hub", "gigachadhub", function() loadstring(game:HttpGet('https://raw.githubusercontent.com/OWJBWKQLAISH/GigaChad-Hub/main/Gigachad%20Hub%20V4'))()
end)

tab.newButton("Infinite Yield V6", "infiniteyield", function()    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

tab.newButton("Fly Gui", "flygui", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FlyGuiV3/main/FlyGuiV3.txt"))()
end)

tab.newButton("Anti Fling", "script that makes you unflingable", function()
    _G.AntiFlingConfig = {
    -- this will remove your rotational velocity every frame
    disable_rotation = true;
   
    -- this slows you down if you're moving too fast, works well but can give you a low gravity effect
    limit_velocity = true;
    limit_velocity_sensitivity = 150; -- how fast you have to be moving before you get slowed down
    limit_velocity_slow = 0; -- the amount of velocity you keep; a lower number increases how much you slow down by
   
    -- stops you from ragdolling or falling over and losing control
    anti_ragdoll = true;
   
    -- completely freezes you if someone gets too close to you  
    anchor = false;
    smart_anchor = true; -- only anchors if someone is considered flinging, this likely won't detect many flings
    anchor_dist = 30; -- how close someone has to be to trigger anchor
   
    -- teleport away if someone gets too close
    teleport = false;
    smart_teleport = true; -- only teleports if someone is considered flinging, this likely won't detect many flings
    teleport_dist = 30; -- how close someone has to be to teleport you
}
-- run _G.disable() to disable the script completely

loadstring(game:HttpGet('https://raw.githubusercontent.com/topitbopit/rblx/main/extra/better_antifling.lua'))()
end)

tab.newButton("Pendulum Hub", "There is backshotting movements😏", function()  loadstring(game:HttpGet("https://raw.githubusercontent.com/Tescalus/Pendulum-Hubs-Source/main/Pendulum%20Hub%20V5.lua"))()
end)

local tab = DrRayLibrary.newTab("Blade Ball", "ImageIdHere")

tab.newButton("PC Auto Parry", "xd", function()
    loadstring(game:HttpGet("https://scriptblox.com/raw/UPD-Blade-Ball-op-autoparry-with-visualizer-8652"))()
end)

tab.newButton("Bedol", "yeah bedol", function()
 _G.UI_Size = 200 -- config ui size
loadstring(game:HttpGet("https://raw.githubusercontent.com/3345-c-a-t-s-u-s/-beta-/main/AutoParry.lua"))()
end)

tab.newButton("Chaotic", "best script ever", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/Mc4121ban/trashscript/main/chaotic.lua"))()
end)

tab.newButton("close combat", "Close -YOUR DOORS-", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/kidshop4/scriptbladeballk/main/bladeball.lua"))()
end)

local tab = DrRayLibrary.newTab("MM2", "ImageIdHere")

tab.newButton("Ghost Hub", "THERE IS GHOST1!!1!1", function() loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub'))()
end)

tab.newButton("Symphony Hub", "lelele", function() loadstring(game:HttpGet('https://raw.githubusercontent.com/ThatSick/ArrayField/main/SymphonyHub.lua'))()
end)

tab.newButton("Eclipseth Hub", "waawawa", function()
    getgenv().mainKey = "nil";

local a,b,c,d,e=loadstring,request or http_request or (http and http.request) or (syn and syn.request),assert,tostring,"https\58//api.eclipsehub.xyz/auth";c(a and b,"Executor not Supported")a(b({Url=e.."\?\107e\121\61"..d(mainKey),Headers={["User-Agent"]="Eclipse"}}).Body)() 
end)

tab.newButton("Nexus Admin Panel", "ther is odmenne!!", function() loadstring(game:HttpGet('https://pastebin.com/raw/e89Mn4Ec'))()
end)

tab.newButton("Nexusazth", "Be a cheater xd", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/s-0-a-b/nexus/main/loadstring"))()
end)

local tab = DrRayLibrary.newTab("Blox Fruits", "ImageIdHere")

tab.newButton("MTriet Hub", "ehheheh", function()  loadstring(game:HttpGet("https://raw.githubusercontent.com/Minhtriettt/Free-Script/main/MTriet-Hub.lua"))()
end)

tab.newButton("Ats-Ware Hub", "Message for Russians: я гей", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/1f0yt/community/master/hxllow"))()
end)

tab.newButton("Demon Hub", "Lolol", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/farrelghibran/demon/main/source.app"))()
end)

tab.newButton("Youm Hub", "yum hub...?", function() loadstring(game:HttpGet("https://raw.githubusercontent.com/Jadelly261/BloxFruits/main/YoumHub", true))()
end)
