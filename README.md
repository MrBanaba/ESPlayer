--ESP player
for i,v in pairs(game.Players:GetChildren()) do	
	
	local Username = Instance.new("BillboardGui")
	local Name = Instance.new("TextLabel")

	Username.Name = "Username"
	Username.Parent = v.Character.Head
	Username.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
	Username.Active = true
	Username.AlwaysOnTop = true
	Username.LightInfluence = 1.000
	Username.Size = UDim2.new(0, 200, 0, 50)
	Username.StudsOffset = Vector3.new(0, 2, 0)

	Name.Name = "Name"
	Name.Parent = Username
	Name.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
	Name.BackgroundTransparency = 1.000
	Name.Size = UDim2.new(0, 200, 0, 50)
	Name.Font = Enum.Font.Unknown
	Name.Text = v.Name
	Name.TextColor3 = Color3.fromRGB(41, 0, 203)
	Name.TextSize = 22.000
	Name.TextStrokeColor3 = Color3.fromRGB(7, 0, 81)
	Name.TextTransparency = 0.400
	Name.TextWrapped = true

end
