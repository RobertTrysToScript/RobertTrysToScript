-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local ON1 = Instance.new("TextButton")
local OFF2 = Instance.new("TextButton")
local ON2 = Instance.new("TextButton")
local OFF1 = Instance.new("TextButton")
local ON3 = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.Position = UDim2.new(0, 0, 0.64907974, 0)
Frame.Size = UDim2.new(0, 196, 0, 286)
Frame.Active = true
Frame.Draggable = true

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(107, 191, 255)
TextLabel.Size = UDim2.new(0, 53, 0, 22)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Speed"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 14.000

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(107, 191, 255)
TextLabel_2.Position = UDim2.new(0, 0, 0.13636364, 0)
TextLabel_2.Size = UDim2.new(0, 53, 0, 22)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "JumpPower"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 11.000

TextLabel_3.Parent = Frame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(107, 191, 255)
TextLabel_3.Position = UDim2.new(0, 0, 0.269230783, 0)
TextLabel_3.Size = UDim2.new(0, 53, 0, 22)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "InfJump"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000

ON1.Name = "ON1"
ON1.Parent = Frame
ON1.BackgroundColor3 = Color3.fromRGB(164, 84, 255)
ON1.Position = UDim2.new(0.278947383, 0, 0, 0)
ON1.Size = UDim2.new(0, 30, 0, 22)
ON1.Font = Enum.Font.SourceSans
ON1.Text = "On"
ON1.TextColor3 = Color3.fromRGB(0, 0, 0)
ON1.TextSize = 14.000
ON1.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
end)

OFF2.Name = "OFF2"
OFF2.Parent = Frame
OFF2.BackgroundColor3 = Color3.fromRGB(164, 84, 255)
OFF2.Position = UDim2.new(0.436842114, 0, 0.13636364, 0)
OFF2.Size = UDim2.new(0, 30, 0, 22)
OFF2.Font = Enum.Font.SourceSans
OFF2.Text = "Off"
OFF2.TextColor3 = Color3.fromRGB(0, 0, 0)
OFF2.TextSize = 14.000
OFF2.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
end)

ON2.Name = "ON2"
ON2.Parent = Frame
ON2.BackgroundColor3 = Color3.fromRGB(164, 84, 255)
ON2.Position = UDim2.new(0.278947383, 0, 0.13636364, 0)
ON2.Size = UDim2.new(0, 30, 0, 22)
ON2.Font = Enum.Font.SourceSans
ON2.Text = "On"
ON2.TextColor3 = Color3.fromRGB(0, 0, 0)
ON2.TextSize = 14.000
ON2.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.Humanoid.JumpPower = 250
end)

OFF1.Name = "OFF1"
OFF1.Parent = Frame
OFF1.BackgroundColor3 = Color3.fromRGB(164, 84, 255)
OFF1.Position = UDim2.new(0.436842114, 0, 0, 0)
OFF1.Size = UDim2.new(0, 30, 0, 22)
OFF1.Font = Enum.Font.SourceSans
OFF1.Text = "Off"
OFF1.TextColor3 = Color3.fromRGB(0, 0, 0)
OFF1.TextSize = 14.000
OFF1.MouseButton1Down:connect(function()
	game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
end)

ON3.Name = "ON3"
ON3.Parent = Frame
ON3.BackgroundColor3 = Color3.fromRGB(164, 84, 255)
ON3.Position = UDim2.new(0.278947383, 0, 0.269230783, 0)
ON3.Size = UDim2.new(0, 30, 0, 22)
ON3.Font = Enum.Font.SourceSans
ON3.Text = "On"
ON3.TextColor3 = Color3.fromRGB(0, 0, 0)
ON3.TextSize = 14.000
ON3.MouseButton1Down:connect(function()
	local InfiniteJumpEnabled = true
	game:GetService("UserInputService").JumpRequest:connect(function()
		if InfiniteJumpEnabled then
			game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
		end
	end)
end)
