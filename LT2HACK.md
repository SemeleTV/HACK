-- Gui to Lua
-- Version: 3.2

-- Instances:Made By Semele TV

local ScreenGui = Instance.new("ScreenGui")
local MAIN = Instance.new("Frame")
local DESIGN = Instance.new("Frame")
local LumberJoke = Instance.new("TextButton")
local Zypher = Instance.new("TextButton")
local Ferry = Instance.new("TextButton")
local TpBypass = Instance.new("TextButton")
local TEXT1 = Instance.new("TextLabel")
local TEXT2 = Instance.new("TextLabel")
local SPEEDMAIN = Instance.new("TextButton")
local SPEED = Instance.new("TextBox")
local JUMPMAIN = Instance.new("TextButton")
local JUMP = Instance.new("TextBox")
local NoClip = Instance.new("TextButton")
local Fly = Instance.new("TextButton")
local Infinitejump = Instance.new("TextButton")
local AntiBlacklistAll = Instance.new("TextButton")
local BlacklistAll = Instance.new("TextButton")
local WipeBase = Instance.new("TextButton")
local Paint = Instance.new("TextButton")
local NoFog = Instance.new("TextButton")
local Close = Instance.new("TextButton")
local OPENMAIN = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

MAIN.Name = "MAIN"
MAIN.Parent = ScreenGui
MAIN.Active = true
MAIN.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
MAIN.BorderColor3 = Color3.fromRGB(255, 0, 255)
MAIN.Position = UDim2.new(0.28353399, 0, 0.258964151, 0)
MAIN.Size = UDim2.new(0, 442, 0, 242)
MAIN.Visible = false
MAIN.Active = true
MAIN.Draggable = true

DESIGN.Name = "DESIGN"
DESIGN.Parent = MAIN
DESIGN.BackgroundColor3 = Color3.fromRGB(255, 0, 255)
DESIGN.Position = UDim2.new(0.319004536, 0, 0, 0)
DESIGN.Size = UDim2.new(0, 2, 0, 242)

LumberJoke.Name = "LumberJoke"
LumberJoke.Parent = MAIN
LumberJoke.BackgroundColor3 = Color3.fromRGB(255, 170, 255)
LumberJoke.Position = UDim2.new(0.0271493215, 0, 0.0330578536, 0)
LumberJoke.Size = UDim2.new(0, 119, 0, 43)
LumberJoke.Font = Enum.Font.SciFi
LumberJoke.Text = "Lumber Joke"
LumberJoke.TextColor3 = Color3.fromRGB(0, 0, 0)
LumberJoke.TextSize = 14.000
LumberJoke.MouseButton1Click:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/PdKzxqvn", true))()
end)

Zypher.Name = "Zypher"
Zypher.Parent = MAIN
Zypher.BackgroundColor3 = Color3.fromRGB(255, 170, 255)
Zypher.Position = UDim2.new(0.0271493196, 0, 0.272727281, 0)
Zypher.Size = UDim2.new(0, 119, 0, 43)
Zypher.Font = Enum.Font.SciFi
Zypher.Text = "Zypher"
Zypher.TextColor3 = Color3.fromRGB(0, 0, 0)
Zypher.TextSize = 14.000
Zypher.MouseButton1Click:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/xTheAlex14/zypher/master/zypherupdatednew'),true))()
end)

Ferry.Name = "Ferry"
Ferry.Parent = MAIN
Ferry.BackgroundColor3 = Color3.fromRGB(255, 170, 255)
Ferry.Position = UDim2.new(0.0271493196, 0, 0.516528904, 0)
Ferry.Size = UDim2.new(0, 119, 0, 43)
Ferry.Font = Enum.Font.SciFi
Ferry.Text = "Ferry"
Ferry.TextColor3 = Color3.fromRGB(0, 0, 0)
Ferry.TextSize = 14.000
Ferry.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/WfpzEV2d", true))()
end)

TpBypass.Name = "TpBypass"
TpBypass.Parent = MAIN
TpBypass.BackgroundColor3 = Color3.fromRGB(255, 170, 255)
TpBypass.Position = UDim2.new(0.0271493196, 0, 0.776859462, 0)
TpBypass.Size = UDim2.new(0, 119, 0, 43)
TpBypass.Font = Enum.Font.SciFi
TpBypass.Text = "TP ByPass"
TpBypass.TextColor3 = Color3.fromRGB(0, 0, 0)
TpBypass.TextSize = 14.000
TpBypass.MouseButton1Click:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/XXMMfhXW", true))()
end)

TEXT1.Name = "TEXT1"
TEXT1.Parent = MAIN
TEXT1.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
TEXT1.BorderColor3 = Color3.fromRGB(255, 0, 255)
TEXT1.Position = UDim2.new(0, 0, 1, 0)
TEXT1.Size = UDim2.new(0, 442, 0, 22)
TEXT1.Font = Enum.Font.SciFi
TEXT1.Text = "THIS GUI MADE BY SEMELE TV "
TEXT1.TextColor3 = Color3.fromRGB(255, 85, 255)
TEXT1.TextScaled = true
TEXT1.TextSize = 14.000
TEXT1.TextWrapped = true

TEXT2.Name = "TEXT2"
TEXT2.Parent = MAIN
TEXT2.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
TEXT2.BorderColor3 = Color3.fromRGB(255, 0, 255)
TEXT2.Position = UDim2.new(0, 0, -0.0909090936, 0)
TEXT2.Size = UDim2.new(0, 442, 0, 22)
TEXT2.Font = Enum.Font.SciFi
TEXT2.Text = "LUMBER TYCOON GUI V1"
TEXT2.TextColor3 = Color3.fromRGB(255, 85, 255)
TEXT2.TextScaled = true
TEXT2.TextSize = 14.000
TEXT2.TextWrapped = true

SPEEDMAIN.Name = "SPEEDMAIN"
SPEEDMAIN.Parent = MAIN
SPEEDMAIN.BackgroundColor3 = Color3.fromRGB(255, 170, 255)
SPEEDMAIN.Position = UDim2.new(0.341628969, 0, 0.0537190065, 0)
SPEEDMAIN.Size = UDim2.new(0, 88, 0, 33)
SPEEDMAIN.Font = Enum.Font.SciFi
SPEEDMAIN.Text = "SPEED"
SPEEDMAIN.TextColor3 = Color3.fromRGB(0, 0, 0)
SPEEDMAIN.TextSize = 14.000
SPEEDMAIN.TextWrapped = true
SPEEDMAIN.MouseButton1Down:connect(function()
game:GetService("RunService").RenderStepped :connect(function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = tonumber(SPEED.Text)
end)
end)

SPEED.Name = "SPEED"
SPEED.Parent = MAIN
SPEED.BackgroundColor3 = Color3.fromRGB(91, 91, 91)
SPEED.Position = UDim2.new(0.554298639, 0, 0.0537190065, 0)
SPEED.Size = UDim2.new(0, 42, 0, 33)
SPEED.Font = Enum.Font.SourceSans
SPEED.PlaceholderText = "16"
SPEED.Text = ""
SPEED.TextColor3 = Color3.fromRGB(0, 0, 0)
SPEED.TextSize = 14.000

JUMPMAIN.Name = "JUMPMAIN"
JUMPMAIN.Parent = MAIN
JUMPMAIN.BackgroundColor3 = Color3.fromRGB(255, 170, 255)
JUMPMAIN.Position = UDim2.new(0.341628969, 0, 0.247933879, 0)
JUMPMAIN.Size = UDim2.new(0, 87, 0, 33)
JUMPMAIN.Font = Enum.Font.SourceSans
JUMPMAIN.Text = "JUMP"
JUMPMAIN.TextColor3 = Color3.fromRGB(0, 0, 0)
JUMPMAIN.TextSize = 14.000
JUMPMAIN.MouseButton1Down:connect(function()
game:GetService("RunService").RenderStepped :connect(function()
game.Players.LocalPlayer.Character.Humanoid.JumpPower = tonumber(JUMP.Text)
end)
end)

JUMP.Name = "JUMP"
JUMP.Parent = MAIN
JUMP.BackgroundColor3 = Color3.fromRGB(91, 91, 91)
JUMP.Position = UDim2.new(0.554298759, 0, 0.247933879, 0)
JUMP.Size = UDim2.new(0, 42, 0, 33)
JUMP.Font = Enum.Font.SourceSans
JUMP.PlaceholderText = "16"
JUMP.Text = ""
JUMP.TextColor3 = Color3.fromRGB(0, 0, 0)
JUMP.TextSize = 14.000

NoClip.Name = "NoClip"
NoClip.Parent = MAIN
NoClip.BackgroundColor3 = Color3.fromRGB(255, 170, 255)
NoClip.Position = UDim2.new(0.377828062, 0, 0.475206614, 0)
NoClip.Size = UDim2.new(0, 55, 0, 31)
NoClip.Font = Enum.Font.SciFi
NoClip.Text = "NoClip"
NoClip.TextColor3 = Color3.fromRGB(0, 0, 0)
NoClip.TextSize = 14.000

Fly.Name = "Fly"
Fly.Parent = MAIN
Fly.BackgroundColor3 = Color3.fromRGB(255, 170, 255)
Fly.Position = UDim2.new(0.377828062, 0, 0.69421488, 0)
Fly.Size = UDim2.new(0, 55, 0, 31)
Fly.Font = Enum.Font.SciFi
Fly.Text = "FLY"
Fly.TextColor3 = Color3.fromRGB(0, 0, 0)
Fly.TextSize = 14.000

Infinitejump.Name = "Infinitejump"
Infinitejump.Parent = MAIN
Infinitejump.BackgroundColor3 = Color3.fromRGB(255, 170, 255)
Infinitejump.Position = UDim2.new(0.579185545, 0, 0.475206614, 0)
Infinitejump.Size = UDim2.new(0, 55, 0, 31)
Infinitejump.Font = Enum.Font.SciFi
Infinitejump.Text = "Infinite Jump"
Infinitejump.TextColor3 = Color3.fromRGB(0, 0, 0)
Infinitejump.TextScaled = true
Infinitejump.TextSize = 10.000
Infinitejump.TextWrapped = true

AntiBlacklistAll.Name = "AntiBlacklistAll"
AntiBlacklistAll.Parent = MAIN
AntiBlacklistAll.BackgroundColor3 = Color3.fromRGB(255, 170, 255)
AntiBlacklistAll.Position = UDim2.new(0.579185545, 0, 0.69421488, 0)
AntiBlacklistAll.Size = UDim2.new(0, 55, 0, 31)
AntiBlacklistAll.Font = Enum.Font.SciFi
AntiBlacklistAll.Text = "AntiblackList"
AntiBlacklistAll.TextColor3 = Color3.fromRGB(0, 0, 0)
AntiBlacklistAll.TextScaled = true
AntiBlacklistAll.TextSize = 14.000
AntiBlacklistAll.TextWrapped = true

BlacklistAll.Name = "BlacklistAll"
BlacklistAll.Parent = MAIN
BlacklistAll.BackgroundColor3 = Color3.fromRGB(255, 170, 255)
BlacklistAll.Position = UDim2.new(0.794117689, 0, 0.475206614, 0)
BlacklistAll.Size = UDim2.new(0, 55, 0, 31)
BlacklistAll.Font = Enum.Font.SciFi
BlacklistAll.Text = "Black List All"
BlacklistAll.TextColor3 = Color3.fromRGB(0, 0, 0)
BlacklistAll.TextScaled = true
BlacklistAll.TextSize = 14.000
BlacklistAll.TextWrapped = true

WipeBase.Name = "WipeBase"
WipeBase.Parent = MAIN
WipeBase.BackgroundColor3 = Color3.fromRGB(255, 170, 255)
WipeBase.Position = UDim2.new(0.794117689, 0, 0.69421488, 0)
WipeBase.Size = UDim2.new(0, 55, 0, 31)
WipeBase.Font = Enum.Font.SciFi
WipeBase.Text = "Wipe Base"
WipeBase.TextColor3 = Color3.fromRGB(0, 0, 0)
WipeBase.TextScaled = true
WipeBase.TextSize = 14.000
WipeBase.TextWrapped = true

Paint.Name = "Paint"
Paint.Parent = MAIN
Paint.BackgroundColor3 = Color3.fromRGB(255, 170, 255)
Paint.Position = UDim2.new(0.794117689, 0, 0.256198347, 0)
Paint.Size = UDim2.new(0, 55, 0, 31)
Paint.Font = Enum.Font.SciFi
Paint.Text = "Paint"
Paint.TextColor3 = Color3.fromRGB(0, 0, 0)
Paint.TextSize = 14.000

NoFog.Name = "NoFog"
NoFog.Parent = MAIN
NoFog.BackgroundColor3 = Color3.fromRGB(255, 170, 255)
NoFog.Position = UDim2.new(0.794117689, 0, 0.0619834661, 0)
NoFog.Size = UDim2.new(0, 55, 0, 31)
NoFog.Font = Enum.Font.SciFi
NoFog.Text = "NoFog"
NoFog.TextColor3 = Color3.fromRGB(0, 0, 0)
NoFog.TextSize = 14.000

Close.Name = "Close"
Close.Parent = MAIN
Close.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
Close.BorderColor3 = Color3.fromRGB(255, 85, 255)
Close.Position = UDim2.new(0.414027154, 0, 0.896694243, 0)
Close.Size = UDim2.new(0, 200, 0, 17)
Close.Font = Enum.Font.SourceSansSemibold
Close.Text = "CLICK TO CLOSE"
Close.TextColor3 = Color3.fromRGB(255, 0, 0)
Close.TextScaled = true
Close.TextSize = 14.000
Close.TextWrapped = true
Close.MouseButton1Down:connect(function()
MAIN.Visible = false
OPENMAIN.Visible = true
end)

OPENMAIN.Name = "OPENMAIN"
OPENMAIN.Parent = ScreenGui
OPENMAIN.BackgroundColor3 = Color3.fromRGB(62, 62, 62)
OPENMAIN.BorderColor3 = Color3.fromRGB(255, 0, 255)
OPENMAIN.Position = UDim2.new(0.0444779992, 0, 0.906374574, 0)
OPENMAIN.Size = UDim2.new(0, 122, 0, 46)
OPENMAIN.Font = Enum.Font.SciFi
OPENMAIN.Text = "OPEN"
OPENMAIN.TextColor3 = Color3.fromRGB(255, 85, 255)
OPENMAIN.TextSize = 33.000
OPENMAIN.TextWrapped = true
OPENMAIN.Active = true
OPENMAIN.Draggable = true
OPENMAIN.MouseButton1Down:connect(function()
OPENMAIN.Visible = false
MAIN.Visible = true
end)

--Fly

local toggle = false
	Fly.MouseButton1Click:Connect(function()
		toggle = not toggle
		Fly.TextColor3 = (toggle and Color3.fromRGB(85, 255, 127) or Color3.fromRGB(255,255,255))
		if toggle then
			flying = not flying
	repeat wait()
	until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
	local mouse = game.Players.LocalPlayer:GetMouse()
	repeat wait() until mouse
	local plr = game.Players.LocalPlayer
	local torso = plr.Character.Torso
	local deb = true
	local ctrl = {f = 0, b = 0, l = 0, r = 0}
	local lastctrl = {f = 0, b = 0, l = 0, r = 0}
	local maxspeed = 200
	local speed = 0
	if flying then
	end
	 
	function FlyFunction()
	local bg = Instance.new("BodyGyro", torso)
	bg.P = 9e4
	bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
	bg.cframe = torso.CFrame
	local bv = Instance.new("BodyVelocity", torso)
	bv.velocity = Vector3.new(0,0.1,0)
	bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
	repeat wait()
	plr.Character.Humanoid.PlatformStand = true
	if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
	speed = speed+.5+(speed/maxspeed)
	if speed > maxspeed then
	speed = maxspeed
	end
	elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
	speed = speed-1
	if speed < 0 then
	speed = 0
	end
	end
	if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
	elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	else
	bv.velocity = Vector3.new(0,0.1,0)
	end
	bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
	until not flying
	ctrl = {f = 0, b = 0, l = 0, r = 0}
	lastctrl = {f = 0, b = 0, l = 0, r = 0}
	speed = 0
	bg:Destroy()
	bv:Destroy()
	plr.Character.Humanoid.PlatformStand = false
	end
	mouse.KeyDown:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 1
	elseif key:lower() == "s" then
	ctrl.b = -1
	elseif key:lower() == "a" then
	ctrl.l = -1
	elseif key:lower() == "d" then
	ctrl.r = 1
	 
	end
	end)
	mouse.KeyUp:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 0
	elseif key:lower() == "s" then
	ctrl.b = 0
	elseif key:lower() == "a" then
	ctrl.l = 0
	elseif key:lower() == "d" then
	ctrl.r = 0
	end
	end)
	FlyFunction()
		else
			flying = not flying
	repeat wait()
	until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
	local mouse = game.Players.LocalPlayer:GetMouse()
	repeat wait() until mouse
	local plr = game.Players.LocalPlayer
	local torso = plr.Character.Torso
	local deb = true
	local ctrl = {f = 0, b = 0, l = 0, r = 0}
	local lastctrl = {f = 0, b = 0, l = 0, r = 0}
	local maxspeed = 200
	local speed = 0
	if flying then
	end
	 
	function FlyFunction()
	local bg = Instance.new("BodyGyro", torso)
	bg.P = 9e4
	bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
	bg.cframe = torso.CFrame
	local bv = Instance.new("BodyVelocity", torso)
	bv.velocity = Vector3.new(0,0.1,0)
	bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
	repeat wait()
	plr.Character.Humanoid.PlatformStand = true
	if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
	speed = speed+.5+(speed/maxspeed)
	if speed > maxspeed then
	speed = maxspeed
	end
	elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
	speed = speed-1
	if speed < 0 then
	speed = 0
	end
	end
	if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
	elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
	bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
	else
	bv.velocity = Vector3.new(0,0.1,0)
	end
	bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
	until not flying
	ctrl = {f = 0, b = 0, l = 0, r = 0}
	lastctrl = {f = 0, b = 0, l = 0, r = 0}
	speed = 0
	bg:Destroy()
	bv:Destroy()
	plr.Character.Humanoid.PlatformStand = false
	end
	mouse.KeyDown:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 1
	elseif key:lower() == "s" then
	ctrl.b = -1
	elseif key:lower() == "a" then
	ctrl.l = -1
	elseif key:lower() == "d" then
	ctrl.r = 1
	 
	end
	end)
	mouse.KeyUp:connect(function(key)
	if key:lower() == "w" then
	ctrl.f = 0
	elseif key:lower() == "s" then
	ctrl.b = 0
	elseif key:lower() == "a" then
	ctrl.l = 0
	elseif key:lower() == "d" then
	ctrl.r = 0
	end
	end)
	FlyFunction()
		end
	end)

--Infinite Jump

local toggle = false
	Infinitejump.MouseButton1Click:Connect(function()
		toggle = not toggle
		Infinitejump.TextColor3 = (toggle and Color3.fromRGB(85, 255, 127) or Color3.fromRGB(255,255,255))
		if toggle then
			InfiniteJumpEnabled = true
		game:GetService("UserInputService").JumpRequest:connect(function()
		if InfiniteJumpEnabled then
			game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
			InfiniteJumpEnabled = true
		end
	end)
	
		else
				InfiniteJumpEnabled = false
	       game:GetService("UserInputService").JumpRequest:connect(function()
		if InfiniteJumpEnabled then
			game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
			
		end
	end)
		end
	end)

--No Clip

	_G.noclip = false
	game:GetService('RunService').Stepped:connect(function()
	if noclip then
	game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
	NoClip.TextColor3 = Color3.fromRGB(85, 255, 127)
	end
	end)
	NoClip.MouseButton1Down:connect(function()
	noclip = not noclip
	NoClip.TextColor3 = Color3.fromRGB(255, 255, 255)
	end)

--No Fog

NoFog.MouseButton1Down:connect(function()
	--Fog.BackgroundColor3 = Color3.new(0, 0, 0)
                      NoFog.TextColor3 = Color3.new(1, 1, 1)
game.Lighting.Changed:connect(function()
	game.Lighting.TimeOfDay = "12:00:00"
	game.Lighting.FogEnd = 9999
	game.Lighting.Brightness = 2
end)
end)

--Paint

Paint.MouseButton1Click:connect(function()
	loadstring(game:HttpGet('https://pastebin.com/raw/3Bk4KVYq',true))()
end)

--Anti Blacklist All

AntiBlacklistAll.MouseButton1Click:Connect(function()
	local plr = game.Players.LocalPlayer
	    local cframe
	    for i,v in next, workspace:GetDescendants() do
	        if v:IsA("SpawnLocation") then
	            v.Touched:Connect(function(h)
	            if h.Parent == plr.Character and cframe then
	                plr.Character:SetPrimaryPartCFrame(cframe)
	                end
	            end)
	        end
	    end
	 
	    game:GetService("RunService"):BindToRenderStep("NO HACKS",Enum.RenderPriority.Last.Value,function()
	    if game.Players.LocalPlayer.Character.PrimaryPart then
	        cframe = game.Players.LocalPlayer.Character.PrimaryPart.CFrame
	        end
	    end)
	 
	    for i,v in next, debug.getregistry() do
	        if type(v)=='function' and debug.getupvalues(v).lastUpdate then
	            debug.setupvalue(v,"lastUpdate",math.huge)
	            break
	        end
	    end
	 
	    for i,v in next, workspace.Effects:GetChildren() do
	        if v:IsA("BasePart") and v.Name == "BlacklistWall" then
	            v:Destroy()
	        end
	    end
	end)

--Blacklist All

BlacklistAll.MouseButton1Click:Connect(function()
		Client = game.ReplicatedStorage.Interaction.ClientSetListPlayer
	players = game.Players
	for i, v in pairs(players:GetPlayers()) do
	    if v.Name ~= players.LocalPlayer.Name then
	        Client:InvokeServer(players.LocalPlayer.BlacklistFolder, v, true)
	    end
	end
	players.PlayerAdded:connect(function(plr)
	    Client:InvokeServer(players.LocalPlayer.BlacklistFolder, plr, true)
	end)
	end)

--Wipe Base

WipeBase.MouseButton1Click:Connect(function()
		local plr = game.Players.LocalPlayer
	local torso = plr.Character.HumanoidRootPart
	
	local delaybeweenchecks = 0.5
	local opendistance = 10
	
	for i, v in pairs(game:GetService("Workspace").Stores.ShopItems:GetChildren()) do
	local A_1 = v
	local Event = game:GetService("ReplicatedStorage").Interaction.ClientIsDragging
	Event:FireServer(A_1)
	end
end)

--Infinite Jump

local toggle = false
	InfJump.MouseButton1Click:Connect(function()
		toggle = not toggle
		InfJump.TextColor3 = (toggle and Color3.fromRGB(85, 255, 127) or Color3.fromRGB(255,255,255))
		if toggle then
			InfiniteJumpEnabled = true
		game:GetService("UserInputService").JumpRequest:connect(function()
		if InfiniteJumpEnabled then
			game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
			InfiniteJumpEnabled = true
		end
	end)
	
		else
				InfiniteJumpEnabled = false
	       game:GetService("UserInputService").JumpRequest:connect(function()
		if InfiniteJumpEnabled then
			game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
			
		end
	end)
		end
	end)
