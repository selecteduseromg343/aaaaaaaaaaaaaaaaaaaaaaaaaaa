-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local gui1 = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local gui2 = Instance.new("TextButton")
local gui3 = Instance.new("TextButton")
local TextButton = Instance.new("TextButton")
local ImageLabel = Instance.new("ImageLabel")

--Properties:

ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(72, 72, 72)
main.Position = UDim2.new(0.577011466, 0, 0.499212593, 0)
main.Size = UDim2.new(0, 279, 0, 278)

gui1.Name = "gui1"
gui1.Parent = main
gui1.BackgroundColor3 = Color3.fromRGB(98, 98, 98)
gui1.Position = UDim2.new(0, 0, 0.205035955, 0)
gui1.Size = UDim2.new(0, 64, 0, 35)
gui1.Font = Enum.Font.SourceSans
gui1.Text = "InfYield"
gui1.TextColor3 = Color3.fromRGB(0, 0, 0)
gui1.TextSize = 14.000
gui1.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)


TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(77, 77, 77)
TextLabel.Size = UDim2.new(0, 279, 0, 32)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Bloppa Hub 5.0"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

TextLabel_2.Parent = main
TextLabel_2.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
TextLabel_2.Position = UDim2.new(0.136200711, 0, 0.877697825, 0)
TextLabel_2.Size = UDim2.new(0, 148, 0, 34)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Welcome, Paiduser#0001"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 14.000

gui2.Name = "gui2"
gui2.Parent = main
gui2.BackgroundColor3 = Color3.fromRGB(70, 70, 70)
gui2.Position = UDim2.new(0, 0, 0.33093524, 0)
gui2.Size = UDim2.new(0, 64, 0, 34)
gui2.Font = Enum.Font.SourceSans
gui2.Text = "Prison X"
gui2.TextColor3 = Color3.fromRGB(0, 0, 0)
gui2.TextSize = 14.000
gui2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/selecteduseromg343/pricccccccccccccccceeeeeeeeeeeee5/main/README.md'),true))()
end)


gui3.Name = "gui3"
gui3.Parent = main
gui3.BackgroundColor3 = Color3.fromRGB(77, 77, 77)
gui3.Position = UDim2.new(0, 0, 0.453237414, 0)
gui3.Size = UDim2.new(0, 64, 0, 33)
gui3.Font = Enum.Font.SourceSans
gui3.Text = "AnimalGui"
gui3.TextColor3 = Color3.fromRGB(0, 0, 0)
gui3.TextSize = 14.000
gui3.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://cheatersoul.click/animalsimx1"))()
end)


TextButton.Parent = main
TextButton.BackgroundColor3 = Color3.fromRGB(94, 94, 94)
TextButton.Position = UDim2.new(0.293906808, 0, 0.205035985, 0)
TextButton.Size = UDim2.new(0, 64, 0, 29)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "FEWizzard"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

ImageLabel.Parent = main
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.Position = UDim2.new(0, 0, 0.877697825, 0)
ImageLabel.Size = UDim2.new(0, 42, 0, 40)
ImageLabel.Image = "rbxassetid://5162713334"
