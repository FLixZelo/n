-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("ImageLabel")
local CloseButton = Instance.new("TextButton")
local TextButton_Roundify_12px = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local Homebutton = Instance.new("TextButton")
local TextButton_Roundify_10px = Instance.new("ImageLabel")
local TextLabel_2 = Instance.new("TextLabel")
local Credits1 = Instance.new("TextLabel")
local Credits1_2 = Instance.new("TextLabel")
local AnticheatKiller = Instance.new("TextButton")
local TextButton_Roundify_10px_2 = Instance.new("ImageLabel")
local AntiCheat = Instance.new("TextLabel")
local Name = Instance.new("TextLabel")
local GodCrafter = Instance.new("TextButton")
local TextButton_Roundify_10px_3 = Instance.new("ImageLabel")
local GodCrafter_2 = Instance.new("TextLabel")
local EmeraldCrafter = Instance.new("TextButton")
local TextButton_Roundify_10px_4 = Instance.new("ImageLabel")
local TextLabel_3 = Instance.new("TextLabel")
Main.Draggable = true
--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Main.Name = "Main"
Main.Parent = ScreenGui
Main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Main.BackgroundTransparency = 1.000
Main.BorderSizePixel = 0
Main.Position = UDim2.new(0.517355442, 0, 0.160798162, 0)
Main.Size = UDim2.new(0, 451, 0, 360)
Main.Image = "rbxassetid://3570695787"
Main.ImageColor3 = Color3.fromRGB(30, 30, 30)
Main.ScaleType = Enum.ScaleType.Slice
Main.SliceCenter = Rect.new(100, 100, 100, 100)
Main.SliceScale = 0.050

CloseButton.Name = "Close Button"
CloseButton.Parent = Main
CloseButton.BackgroundColor3 = Color3.fromRGB(252, 2, 227)
CloseButton.BackgroundTransparency = 1.000
CloseButton.BorderSizePixel = 0
CloseButton.Position = UDim2.new(0.902050138, 0, 0, 0)
CloseButton.Size = UDim2.new(0, 43, 0, 36)
CloseButton.Font = Enum.Font.SourceSans
CloseButton.Text = "x"
CloseButton.TextColor3 = Color3.fromRGB(0, 0, 0)
CloseButton.TextSize = 14.000
CloseButton.MouseButton1Down:connect(function()
CloseButton.Visible = true
Main.Visible = false
end)
TextButton_Roundify_12px.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px.Parent = CloseButton
TextButton_Roundify_12px.Active = true
TextButton_Roundify_12px.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px.BackgroundTransparency = 1.000
TextButton_Roundify_12px.Position = UDim2.new(0.639534831, 0, 0.416666657, 0)
TextButton_Roundify_12px.Selectable = true
TextButton_Roundify_12px.Size = UDim2.new(0.441860467, 0, 0.555555582, 0)
TextButton_Roundify_12px.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px.ImageColor3 = Color3.fromRGB(3, 165, 252)
TextButton_Roundify_12px.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px.SliceScale = 0.120

TextLabel.Parent = CloseButton
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(-0.0465116277, 0, -0.416666657, 0)
TextLabel.Size = UDim2.new(0, 59, 0, 57)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "x"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 14.000

Homebutton.Name = "Home button"
Homebutton.Parent = Main
Homebutton.BackgroundColor3 = Color3.fromRGB(3, 165, 252)
Homebutton.BackgroundTransparency = 1.000
Homebutton.BorderSizePixel = 0
Homebutton.Position = UDim2.new(0.00455580885, 0, 0.0666667223, 0)
Homebutton.Size = UDim2.new(0, 200, 0, 49)
Homebutton.Font = Enum.Font.SourceSans
Homebutton.TextColor3 = Color3.fromRGB(0, 0, 0)
Homebutton.TextSize = 14.000

TextButton_Roundify_10px.Name = "TextButton_Roundify_10px"
TextButton_Roundify_10px.Parent = Homebutton
TextButton_Roundify_10px.Active = true
TextButton_Roundify_10px.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_10px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_10px.BackgroundTransparency = 1.000
TextButton_Roundify_10px.Position = UDim2.new(0.414428771, 0, 0.622448921, 0)
TextButton_Roundify_10px.Selectable = true
TextButton_Roundify_10px.Size = UDim2.new(0.761142552, 0, 0.551019788, 0)
TextButton_Roundify_10px.Image = "rbxassetid://3570695787"
TextButton_Roundify_10px.ImageColor3 = Color3.fromRGB(3, 165, 252)
TextButton_Roundify_10px.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_10px.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_10px.SliceScale = 0.100

TextLabel_2.Parent = TextButton_Roundify_10px
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.0511430688, 0, 0.148148313, 0)
TextLabel_2.Size = UDim2.new(0, 135, 0, 17)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Home"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 14.000

Credits1.Name = "Credits 1"
Credits1.Parent = Main
Credits1.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Credits1.BackgroundTransparency = 1.000
Credits1.Position = UDim2.new(0.699316502, 0, 0.897222221, 0)
Credits1.Size = UDim2.new(0, 126, 0, 15)
Credits1.Font = Enum.Font.SourceSans
Credits1.Text = "Made by: xqusp#4767"
Credits1.TextColor3 = Color3.fromRGB(255, 255, 255)
Credits1.TextSize = 12.000

Credits1_2.Name = "Credits 1"
Credits1_2.Parent = Main
Credits1_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Credits1_2.BackgroundTransparency = 1.000
Credits1_2.Position = UDim2.new(0.699316502, 0, 0.938888848, 0)
Credits1_2.Size = UDim2.new(0, 126, 0, 15)
Credits1_2.Font = Enum.Font.SourceSans
Credits1_2.Text = "Made by: Pandy#2773"
Credits1_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Credits1_2.TextSize = 12.000

AnticheatKiller.Name = "Anticheat Killer"
AnticheatKiller.Parent = Main
AnticheatKiller.BackgroundColor3 = Color3.fromRGB(3, 165, 252)
AnticheatKiller.BackgroundTransparency = 1.000
AnticheatKiller.BorderSizePixel = 0
AnticheatKiller.Position = UDim2.new(0.564920247, 0, 0.761111081, 0)
AnticheatKiller.Size = UDim2.new(0, 200, 0, 49)
AnticheatKiller.Font = Enum.Font.SourceSans
AnticheatKiller.TextColor3 = Color3.fromRGB(0, 0, 0)
AnticheatKiller.TextSize = 14.000

TextButton_Roundify_10px_2.Name = "TextButton_Roundify_10px"
TextButton_Roundify_10px_2.Parent = AnticheatKiller
TextButton_Roundify_10px_2.Active = true
TextButton_Roundify_10px_2.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_10px_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_10px_2.BackgroundTransparency = 1.000
TextButton_Roundify_10px_2.Position = UDim2.new(0.644999981, 0, 0.479591846, 0)
TextButton_Roundify_10px_2.Selectable = true
TextButton_Roundify_10px_2.Size = UDim2.new(0.479999989, 0, 0.346938789, 0)
TextButton_Roundify_10px_2.Image = "rbxassetid://3570695787"
TextButton_Roundify_10px_2.ImageColor3 = Color3.fromRGB(3, 165, 252)
TextButton_Roundify_10px_2.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_10px_2.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_10px_2.SliceScale = 0.100

AntiCheat.Name = "AntiCheat"
AntiCheat.Parent = AnticheatKiller
AntiCheat.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AntiCheat.BackgroundTransparency = 1.000
AntiCheat.Position = UDim2.new(0.174999997, 0, 0.163265303, 0)
AntiCheat.Size = UDim2.new(0, 188, 0, 30)
AntiCheat.Font = Enum.Font.SourceSans
AntiCheat.Text = "Anticheat Killer"
AntiCheat.TextColor3 = Color3.fromRGB(255, 255, 255)
AntiCheat.TextSize = 14.000

Name.Name = "Name"
Name.Parent = Main
Name.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Name.BackgroundTransparency = 1.000
Name.Position = UDim2.new(0, 0, 0.0138889002, 0)
Name.Size = UDim2.new(0, 62, 0, 20)
Name.Font = Enum.Font.SourceSans
Name.Text = "Vigilante "
Name.TextColor3 = Color3.fromRGB(255, 255, 255)
Name.TextSize = 14.000

GodCrafter.Name = "God Crafter"
GodCrafter.Parent = Main
GodCrafter.BackgroundColor3 = Color3.fromRGB(3, 165, 252)
GodCrafter.BackgroundTransparency = 1.000
GodCrafter.BorderSizePixel = 0
GodCrafter.Position = UDim2.new(-0.0524546355, 0, 0.713695407, 0)
GodCrafter.Size = UDim2.new(0, 200, 0, 49)
GodCrafter.Font = Enum.Font.SourceSans
GodCrafter.TextColor3 = Color3.fromRGB(0, 0, 0)
GodCrafter.TextSize = 14.000

TextButton_Roundify_10px_3.Name = "TextButton_Roundify_10px"
TextButton_Roundify_10px_3.Parent = GodCrafter
TextButton_Roundify_10px_3.Active = true
TextButton_Roundify_10px_3.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_10px_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_10px_3.BackgroundTransparency = 1.000
TextButton_Roundify_10px_3.Position = UDim2.new(0.557499945, 0, 0.734693885, 0)
TextButton_Roundify_10px_3.Selectable = true
TextButton_Roundify_10px_3.Size = UDim2.new(0.774999976, 0, 0.53061223, 0)
TextButton_Roundify_10px_3.Image = "rbxassetid://3570695787"
TextButton_Roundify_10px_3.ImageColor3 = Color3.fromRGB(3, 165, 252)
TextButton_Roundify_10px_3.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_10px_3.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_10px_3.SliceScale = 0.100

GodCrafter_2.Name = "God Crafter"
GodCrafter_2.Parent = TextButton_Roundify_10px_3
GodCrafter_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GodCrafter_2.BackgroundTransparency = 1.000
GodCrafter_2.BorderSizePixel = 0
GodCrafter_2.Position = UDim2.new(0.0129032284, 0, 0.210407257, 0)
GodCrafter_2.Size = UDim2.new(0, 143, 0, 15)
GodCrafter_2.Font = Enum.Font.SourceSans
GodCrafter_2.Text = "God Crafter"
GodCrafter_2.TextColor3 = Color3.fromRGB(255, 255, 255)
GodCrafter_2.TextSize = 14.000

EmeraldCrafter.Name = "Emerald Crafter"
EmeraldCrafter.Parent = Main
EmeraldCrafter.BackgroundColor3 = Color3.fromRGB(3, 165, 252)
EmeraldCrafter.BackgroundTransparency = 1.000
EmeraldCrafter.BorderSizePixel = 0
EmeraldCrafter.Position = UDim2.new(-0.0435557403, 0, 0.888888896, 0)
EmeraldCrafter.Size = UDim2.new(0, 200, 0, 51)
EmeraldCrafter.Font = Enum.Font.SourceSans
EmeraldCrafter.Text = ""
EmeraldCrafter.TextColor3 = Color3.fromRGB(0, 0, 0)
EmeraldCrafter.TextSize = 14.000

TextButton_Roundify_10px_4.Name = "TextButton_Roundify_10px"
TextButton_Roundify_10px_4.Parent = EmeraldCrafter
TextButton_Roundify_10px_4.Active = true
TextButton_Roundify_10px_4.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_10px_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_10px_4.BackgroundTransparency = 1.000
TextButton_Roundify_10px_4.Position = UDim2.new(0.53099972, 0, 0.0921750665, 0)
TextButton_Roundify_10px_4.Selectable = true
TextButton_Roundify_10px_4.Size = UDim2.new(0.774999976, 0, 0.493064731, 0)
TextButton_Roundify_10px_4.Image = "rbxassetid://3570695787"
TextButton_Roundify_10px_4.ImageColor3 = Color3.fromRGB(3, 165, 252)
TextButton_Roundify_10px_4.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_10px_4.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_10px_4.SliceScale = 0.100

TextLabel_3.Parent = TextButton_Roundify_10px_4
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.0091676414, 0, 0.113134384, 0)
TextLabel_3.Size = UDim2.new(0, 155, 0, 18)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Emerald Crafter"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 14.000

-- Scripts:

local function ITQO_fake_script() -- CloseButton.LocalScript 
	local script = Instance.new('LocalScript', CloseButton)

	script.Parent.MouseButton1Click:Connect(function()
	game.Players.LocalPlayer.PlayerGui.ScreenGui.Main.Visible = false
	end)
end
coroutine.wrap(ITQO_fake_script)()
local function OQIROZY_fake_script() -- ScreenGui.LocalScript 
	local script = Instance.new('LocalScript', ScreenGui)

	frame = script.Parent.Main 
	frame.Draggable = true
	frame.Active = true
	frame.Selectable = true
end
coroutine.wrap(OQIROZY_fake_script)()
