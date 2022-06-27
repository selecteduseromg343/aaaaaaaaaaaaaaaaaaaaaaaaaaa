
local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local guiyield = Instance.new("TextButton")
local gui = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local pb = Instance.new("TextButton")
local lg = Instance.new("TextButton")
local aimbot = Instance.new("TextButton")

ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(0, 85, 255)
main.Position = UDim2.new(0.553232014, 0, 0.541732252, 0)
main.Size = UDim2.new(0, 439, 0, 260)
main.Active = true
main.Draggable = true

TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(85, 85, 255)
TextLabel.Size = UDim2.new(0, 439, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Bloppa Paid Hub 4.0 Orginal"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

guiyield.Name = "guiyield"
guiyield.Parent = main
guiyield.BackgroundColor3 = Color3.fromRGB(85, 170, 127)
guiyield.Position = UDim2.new(0.0273348521, 0, 0.288461536, 0)
guiyield.Size = UDim2.new(0, 66, 0, 24)
guiyield.Font = Enum.Font.SourceSans
guiyield.Text = "infyield"
guiyield.TextColor3 = Color3.fromRGB(0, 0, 0)
guiyield.TextSize = 14.000
guiyield.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)

gui.Name = "gui"
gui.Parent = main
gui.BackgroundColor3 = Color3.fromRGB(85, 170, 0)
gui.Position = UDim2.new(0.2118451, 0, 0.288461536, 0)
gui.Size = UDim2.new(0, 69, 0, 24)
gui.Font = Enum.Font.SourceSans
gui.Text = "animalgui"
gui.TextColor3 = Color3.fromRGB(0, 0, 0)
gui.TextSize = 14.000
gui.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://cheatersoul.click/animalsimx1"))()
end)

TextLabel_2.Parent = main
TextLabel_2.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
TextLabel_2.Position = UDim2.new(0.751708388, 0, 0.903846145, 0)
TextLabel_2.Size = UDim2.new(0, 109, 0, 25)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "by SerVenTos#3992"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 14.000

TextLabel_3.Parent = main
TextLabel_3.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
TextLabel_3.Position = UDim2.new(0, 0, 0.850000143, 0)
TextLabel_3.Size = UDim2.new(0, 104, 0, 39)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Your Status: Paid"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000

pb.Name = "pb"
pb.Parent = main
pb.BackgroundColor3 = Color3.fromRGB(85, 170, 127)
pb.Position = UDim2.new(0.421412289, 0, 0.288461536, 0)
pb.Size = UDim2.new(0, 69, 0, 24)
pb.Font = Enum.Font.SourceSans
pb.Text = "prisonkills"
pb.TextColor3 = Color3.fromRGB(0, 0, 0)
pb.TextSize = 14.000
pb.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/selecteduseromg343/prisonbreakerv.1.4/main/README.md?token=GHSAT0AAAAAABV6TU2RNDHBHCSS3LKRGSGCYVWX6JQ'),true))()
end)

lg.Name = "lg"
lg.Parent = main
lg.BackgroundColor3 = Color3.fromRGB(85, 170, 127)
lg.Position = UDim2.new(0.605922699, 0, 0.296153843, 0)
lg.Size = UDim2.new(0, 96, 0, 20)
lg.Font = Enum.Font.SourceSans
lg.Text = "legendadmin"
lg.TextColor3 = Color3.fromRGB(0, 0, 0)
lg.TextSize = 14.000
lg.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/selecteduseromg343/legendaryadmin43/main/README.md?token=GHSAT0AAAAAABV6TU2QFPC4LT4FK5BEYQE2YVWVQMQ'),true))()
end)

aimbot.Name = "aimbot"
aimbot.Parent = main
aimbot.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
aimbot.Position = UDim2.new(0.0273348521, 0, 0.507692337, 0)
aimbot.Size = UDim2.new(0, 81, 0, 26)
aimbot.Font = Enum.Font.SourceSans
aimbot.Text = "Owlhub"
aimbot.TextColor3 = Color3.fromRGB(0, 0, 0)
aimbot.TextSize = 14.000
aimbot.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
end)

----------------] Copyright By serventos
