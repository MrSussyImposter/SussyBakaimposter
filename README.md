local UFFLNoCDScript = Instance.new("ScreenGui")
local Sus = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local TextButton_3 = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")


UFFLNoCDScript.Name = "UFFL NoCD Script"
UFFLNoCDScript.Parent = game.Workspace



Sus.Name = "Sus"
Sus.Parent = UFFLNoCDScript
Sus.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Sus.Position = UDim2.new(0.0700000003, 0, 0.109809667, 0)
Sus.Size = UDim2.new(0, 191, 0, 456)
Sus.Active = true
Sus.Draggable = true


TextLabel.Parent = Sus
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.Size = UDim2.new(0, 191, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "sans move phase1"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 14.000

TextButton.Parent = Sus
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.Position = UDim2.new(0, 0, 0.230644554, 0)
TextButton.Size = UDim2.new(0, 191, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "move1"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000
TextButton.MouseButton1Down:connect(function()
	local Event = game:GetService("ReplicatedStorage").Sans1
	Event:FireServer()

end)

TextButton_2.Parent = Sus
TextButton_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.Position = UDim2.new(0, 0, 0.383771926, 0)
TextButton_2.Size = UDim2.new(0, 191, 0, 50)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "move2"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 14.000
TextButton_2.MouseButton1Down:connect(function()
	local Event = game:GetService("ReplicatedStorage").Sans2
	Event:FireServer()

end)


TextButton_3.Parent = Sus
TextButton_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.Position = UDim2.new(0, 0, 0.529589355, 0)
TextButton_3.Size = UDim2.new(0, 191, 0, 50)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "move3"
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextSize = 14.000
TextButton_3.MouseButton1Down:connect(function()
	local Event = game:GetService("ReplicatedStorage").Sans3
	Event:FireServer()

end)

TextButton_4.Parent = Sus
TextButton_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.Position = UDim2.new(0, 0, 0.672451019, 0)
TextButton_4.Size = UDim2.new(0, 191, 0, 50)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = "move4"
TextButton_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.TextSize = 14.000
TextButton_4.MouseButton1Down:connect(function()
	local Event = game:GetService("ReplicatedStorage").Sans4
	Event:FireServer()

end)
