    -- RGT gui
    -- credits: nottefd / xHeptc (kavo library) / ahmadd#4096 (Anti-Stage Script)

    print ("credits: nottefd / xHeptc (kavo library) / ahmadd#4096 (Anti-Stage Script)")
    wait (0.1)
    print ("checking placeId...")

if game.placeId == 10851599 then
        print("You're in RGT game!")
        print("Discord (soon)")
        local Sound = Instance.new("Sound",game:GetService("SoundService"))
        Sound.SoundId = "rbxassetid://232127604"
        Sound:Play()
        local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
        local Window = Library.CreateLib("RGT GUI", "Midnight")
        --MAIN
        local Main = Window:NewTab("Main")
        local MainSection = Main:NewSection("Main")
        MainSection:NewButton("Anti-Stage Script (YOU MUST BE R6!)", "Excute Anti-Stage Script by ahmadd#4096", function()
        local AntiStage = loadstring(game:HttpGet("https://raw.githubusercontent.com/hamooodii/WEIROWIER/main/werwer"))()
        end)
        MainSection:NewButton("infinite yield Script", "Excute Admin Script", function()
        local AdminScript = loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
        end)
        MainSection:NewKeybind("Open GUI", "Gui bind", Enum.KeyCode.E, function()
            Library:ToggleUI()
        end)
        local FarmSection = Main:NewSection("Farm")
        FarmSection:NewToggle("Auto farm Rep", "Make you AFK farm Rep!", function(f)
            getgenv().autofarm = f
            while true do
                if not getgenv().autofarm then return end
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-29.1610119, 139.231445, -563.787109, 0.175039172, -0.006600108, -0.98453933, -9.09244324e-09, 0.999977529, -0.00670360355, 0.984561443, 0.00117340207, 0.175035238)
                wait (0.39)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(115.934738, 138.297745, -550.600342, 0.870275795, -0.00381850102, -0.492549956, -8.59481641e-09, 0.999969959, -0.00775229745, 0.492564768, 0.00674664089, 0.870249629)
                wait (0.69)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(81.1989363, 138.805573, -550.688049, 0.506184518, 0.0212831534, 0.86216253, -1.17096519e-08, 0.99969542, -0.0246782526, -0.862425208, 0.0124917403, 0.506030381)
                wait (0.41)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(115.934738, 138.297745, -550.600342, 0.870275795, -0.00381850102, -0.492549956, -8.59481641e-09, 0.999969959, -0.00775229745, 0.492564768, 0.00674664089, 0.870249629)
                wait (0.69)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(195.143893, 118.697705, -195.103867, 0.879229724, -0.0193597823, 0.476004511, -6.19801988e-09, 0.999173939, 0.0406378433, -0.476398021, -0.0357300006, 0.878503442)
                wait (0.45)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(115.934738, 138.297745, -550.600342, 0.870275795, -0.00381850102, -0.492549956, -8.59481641e-09, 0.999969959, -0.00775229745, 0.492564768, 0.00674664089, 0.870249629)
                wait (0.69)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(459.399536, 163.401871, -852.358521, 0.00959476829, 0.0527288541, -0.998562753, 8.02366262e-09, 0.998608768, 0.0527312793, 0.999953985, -0.000505952456, 0.00958141964)
                wait (0.44)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(115.934738, 138.297745, -550.600342, 0.870275795, -0.00381850102, -0.492549956, -8.59481641e-09, 0.999969959, -0.00775229745, 0.492564768, 0.00674664089, 0.870249629)
                wait (0.69)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(371.191132, 152.594757, -725.930359, 0.15353471, 0.119699843, -0.980866492, 9.16571796e-09, 0.992635906, 0.121136129, 0.988143265, -0.0185986087, 0.15240407)
                wait (0.50)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(115.934738, 138.297745, -550.600342, 0.870275795, -0.00381850102, -0.492549956, -8.59481641e-09, 0.999969959, -0.00775229745, 0.492564768, 0.00674664089, 0.870249629)
                wait (120.69)
            end
        end)
    --Player
    local Player = Window:NewTab("Player")
    local PlayerSection = Player:NewSection("Player")
    PlayerSection:NewSlider("Walkspeed", "Changes your walkspeed !", 250, 16, function(v)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = v
    end)
    PlayerSection:NewSlider("JumpPower", "Changes your JumpPower !", 250, 50, function(v)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = v
    end)



    -- YL Script
    -- credits: nottefd / xHeptc (kavo library) / Ezpi#0474 (AUTO CLICK Script)
elseif game.placeId == 8982709021 then
    print("You're in YL game!")
    print("Discord: (soon)")
    local Sound = Instance.new("Sound",game:GetService("SoundService"))
    Sound.SoundId = "rbxassetid://232127604"
    Sound:Play()
    local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
    local Window = Library.CreateLib("YL GUI", "DarkTheme")
    --MAIN
    local Main = Window:NewTab("Main")
    local MainSection = Main:NewSection("Main")
    MainSection:NewButton("ANTI AFK", "yes it is by me LOL", function()
        game:service'Players'.LocalPlayer.Idled:connect(function()
        bb:CaptureController()bb:ClickButton2(Vector2.new())
        ab.Text="You went idle and ROBLOX tried to kick you but we reflected it!"wait(2)ab.Text="Script Re-Enabled"end)
    end)

    local MainSection = Main:NewSection("Farm")
    MainSection:NewButton("Vlogging auto Clicker (by Ezpi#0474) ", "useful for AFK VLOGGONG!", function(v)

          print ("on")
        --// Credits \\--
--[[ Ezpi#0474 - Creator of this script ]]--

--// Services \\--
local CoreGui = game:GetService("CoreGui")
local Players = game:GetService("Players")
local VirtualInputManager = game:GetService("VirtualInputManager")

--// Variables \\--
local Player = Players.LocalPlayer
local Enabled = false
local Mouse = Player:GetMouse()
local X, Y = 0, 0
local LastC = Color3.new(1, 0, 0)
local LastU = tick()

--// Exploit Fix \\--
if not pcall(function() return syn.protect_gui end) then
    syn = {}
    syn.protect_gui = function(A_1)
        A_1.Parent = CoreGui
    end
end

--// UI Library \\--
local Library = loadstring(game:HttpGetAsync('https://pastebin.com/raw/edJT9EGX'))()
local Window = Library:CreateWindow("AutoClicker by Ezpi")
Enabled_1 = Window:AddColor({
    text = 'Status:',
    flag = "Ezpi_1",
    color = Color3.new(1, 0, 0),
    callback = function(A_1)
        -- "Enabled" Color
        local NewColor = Color3.new(0, 1, 0)
        if Enabled == false then
            NewColor = Color3.new(1, 0, 0)
        end
        if NewColor ~= Last or A_1 ~= NewColor then
            Last = NewColor
            Enabled_1:SetColor(NewColor)
        end
    end
})
Window:AddBind({
    text = 'Toggle',
    callback = function()
        -- Toggle
        Enabled = not Enabled
        -- "Enabled" Color
        local NewColor = Color3.new(0, 1, 0)
        if Enabled == false then
            NewColor = Color3.new(1, 0, 0)
        end
        if NewColor ~= Last then
            Last = NewColor
            Enabled_1:SetColor(NewColor)
        end
        -- Click Position
        if Enabled then
            -- Update Mouse Pos
            X, Y = Mouse.X, Mouse.Y + 10
            -- Update Box
            Box_1:SetValue()
        else
            X, Y = 0, 0
            Box_1:SetValue()
        end
        -- AutoClick
        while Enabled do
            VirtualInputManager:SendMouseButtonEvent(X, Y, 0, true, game, 1)
            VirtualInputManager:SendMouseButtonEvent(X, Y, 0, false, game, 1)
            wait(Library.flags.Interval)
        end
    end
})
Window:AddSlider({
    text = 'Interval',
    min = 0.01,
    max = 2,
    value = 1,
    float = 0.01
})
Box_1 = Window:AddBox({
    text = "AutoClick Position:",
    value = "X: " .. X .. ", Y: " .. Y,
    callback = function()
        if tick()-LastU > 0.1 then
            LastU = tick()
            Box_1:SetValue("X: " .. X .. ", Y: " .. Y)
        end
    end
})
Library:Init()
        end)
--Player
    local Player = Window:NewTab("Player")
    local PlayerSection = Player:NewSection("Player")
    PlayerSection:NewSlider("Walkspeed", "Changes your walkspeed !", 250, 16, function(v)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = v
    end)
    PlayerSection:NewSlider("JumpPower", "Changes your JumpPower !", 250, 50, function(v)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = v
    end)
    local credits = Window:NewTab("Credits")
    local creditsSection = credits:NewSection("Dev: nottefd")
    local creditsSection = credits:NewSection("Auto clicker script: Ezpi#0474")
    local creditsSection = credits:NewSection("UI: xHeptc (kavo library)")
    local creditsSection = credits:NewSection("The ui :https://xheptcofficial.gitbook.io/kavo-library")
    ---
else
    print("mode: universal")
    print("Discord: (soon)")
    print ("supported games are...")
    print("Game id :10851599")
    print("Game id :8982709021")
    local Sound = Instance.new("Sound",game:GetService("SoundService"))
    Sound.SoundId = "rbxassetid://232127604"
    Sound:Play()
    --Player
    local Player = Window:NewTab("Player")
    local PlayerSection = Player:NewSection("Player")
    PlayerSection:NewSlider("Walkspeed", "Changes your walkspeed !", 250, 16, function(v)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = v
    end)
    PlayerSection:NewSlider("JumpPower", "Changes your JumpPower !", 250, 50, function(v)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = v
    end)
    local credits = Window:NewTab("Credits")
    local creditsSection = credits:NewSection("Dev: nottefd")
    local creditsSection = credits:NewSection("UI: xHeptc (kavo library)")
    local creditsSection = credits:NewSection("The ui :https://xheptcofficial.gitbook.io/kavo-library")
end
