local ScreenGui = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local TextButton_2 = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local TextButton_4 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local TextButton_5 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local MainButton = Instance.new("TextButton")
local ImageLabel_2 = Instance.new("ImageLabel")
local UICorner_6 = Instance.new("UICorner")
local UICorner_7 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

MainFrame.Name = "MainFrame"
MainFrame.Parent = ScreenGui
MainFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MainFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
MainFrame.BorderSizePixel = 0
MainFrame.Position = UDim2.new(0.117746696, 0, 0.0149225043, 1)
MainFrame.Size = UDim2.new(0, 475, 0, 311)
MainFrame.Visible = false

ImageLabel.Parent = MainFrame
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Size = UDim2.new(0, 475, 0, 311)
ImageLabel.Image = "http://www.roblox.com/asset/?id=11203191520"
ImageLabel.ImageColor3 = Color3.fromRGB(255, 41, 226)

TextLabel.Parent = MainFrame
TextLabel.BackgroundColor3 = Color3.fromRGB(168, 19, 255)
TextLabel.BackgroundTransparency = 0.800
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Size = UDim2.new(0, 475, 0, 32)
TextLabel.Font = Enum.Font.Bodoni
TextLabel.Text = "gouq_hub Tg@Satyrn002"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 26.000

TextButton.Parent = MainFrame
TextButton.BackgroundColor3 = Color3.fromRGB(130, 8, 110)
TextButton.BackgroundTransparency = 0.100
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0253411308, 0, 0.12328767, 0)
TextButton.Size = UDim2.new(0, 200, 0, 50)
TextButton.Font = Enum.Font.Bodoni
TextButton.Text = "ESP"
TextButton.TextColor3 = Color3.fromRGB(150, 2, 255)
TextButton.TextSize = 24.000

UICorner.Parent = TextButton

TextButton_2.Parent = MainFrame
TextButton_2.BackgroundColor3 = Color3.fromRGB(130, 8, 110)
TextButton_2.BackgroundTransparency = 0.100
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.025341155, 0, 0.324353635, 0)
TextButton_2.Size = UDim2.new(0, 200, 0, 50)
TextButton_2.Font = Enum.Font.Bodoni
TextButton_2.Text = "AIM BOT"
TextButton_2.TextColor3 = Color3.fromRGB(150, 2, 255)
TextButton_2.TextSize = 24.000

UICorner_2.Parent = TextButton_2

TextButton_3.Parent = MainFrame
TextButton_3.BackgroundColor3 = Color3.fromRGB(130, 8, 110)
TextButton_3.BackgroundTransparency = 0.100
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.025341155, 0, 0.526256442, 0)
TextButton_3.Size = UDim2.new(0, 200, 0, 50)
TextButton_3.Font = Enum.Font.Bodoni
TextButton_3.Text = "Custom Day"
TextButton_3.TextColor3 = Color3.fromRGB(150, 2, 255)
TextButton_3.TextSize = 24.000

UICorner_3.Parent = TextButton_3

TextButton_4.Parent = MainFrame
TextButton_4.BackgroundColor3 = Color3.fromRGB(130, 8, 110)
TextButton_4.BackgroundTransparency = 0.100
TextButton_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0.025341155, 0, 0.739708424, 0)
TextButton_4.Size = UDim2.new(0, 200, 0, 50)
TextButton_4.Font = Enum.Font.Bodoni
TextButton_4.Text = "Day"
TextButton_4.TextColor3 = Color3.fromRGB(150, 2, 255)
TextButton_4.TextSize = 24.000

UICorner_4.Parent = TextButton_4

TextButton_5.Parent = MainFrame
TextButton_5.BackgroundColor3 = Color3.fromRGB(130, 8, 110)
TextButton_5.BackgroundTransparency = 0.100
TextButton_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0.51165694, 0, 0.123287678, 0)
TextButton_5.Size = UDim2.new(0, 200, 0, 50)
TextButton_5.Font = Enum.Font.Bodoni
TextButton_5.Text = "infinityJump"
TextButton_5.TextColor3 = Color3.fromRGB(150, 2, 255)
TextButton_5.TextSize = 24.000

UICorner_5.Parent = TextButton_5

MainButton.Name = "MainButton"
MainButton.Parent = ScreenGui
MainButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MainButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
MainButton.BorderSizePixel = 0
MainButton.Position = UDim2.new(0.930137515, 0, 0.0157384984, 0)
MainButton.Size = UDim2.new(0, 55, 0, 50)
MainButton.Font = Enum.Font.SourceSans
MainButton.TextColor3 = Color3.fromRGB(0, 0, 0)
MainButton.TextSize = 14.000

ImageLabel_2.Parent = MainButton
ImageLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_2.BorderSizePixel = 0
ImageLabel_2.Size = UDim2.new(0, 58, 0, 50)
ImageLabel_2.Image = "http://www.roblox.com/asset/?id=11203191520"
ImageLabel_2.ImageColor3 = Color3.fromRGB(255, 20, 232)

UICorner_6.Parent = ImageLabel_2

UICorner_7.Parent = MainButton

TextLabel_2.Parent = MainButton
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Size = UDim2.new(0, 58, 0, 50)
TextLabel_2.Font = Enum.Font.FredokaOne
TextLabel_2.Text = "X"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 28.000

-- Scripts:

local function SYUT_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		while wait(0.5) do
			for i, childrik in ipairs(workspace:GetDescendants()) do
				if childrik:FindFirstChild("Humanoid") then
					if not childrik:FindFirstChild("EspBox") then
						if childrik ~= game.Players.LocalPlayer.Character then
							local esp = Instance.new("BoxHandleAdornment",childrik)
							esp.Adornee = childrik
							esp.ZIndex = 0
							esp.Size = Vector3.new(4, 5, 1)
							esp.Transparency = 0.50
							esp.Color3 = Color3.fromRGB(193, 8, 255)
							esp.AlwaysOnTop = true
							esp.Name = "EspBox"
						end
					end
				end
			end
		end
	end)
end
coroutine.wrap(SYUT_fake_script)()
local function ZEOWH_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Click:Connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/Exunys/Aimbot-V3/main/src/Aimbot.lua"))()()
	end)
end
coroutine.wrap(ZEOWH_fake_script)()
local function PBTGQ_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Click:Connect(function()
		game.Lighting.Ambient = Color3.fromRGB(234, 0, 255)
		game.Lighting.TimeOfDay = "20:30:00"
	end)
end
coroutine.wrap(PBTGQ_fake_script)()
local function USOQ_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	script.Parent.MouseButton1Click:Connect(function()
		game.Lighting.Ambient = Color3.fromRGB(234, 0, 255)
		game.Lighting.TimeOfDay = "15:30:00"
	end)
end
coroutine.wrap(USOQ_fake_script)()
local function OWQJOLH_fake_script() -- TextButton_5.LocalScript 
	local script = Instance.new('LocalScript', TextButton_5)

	script.Parent.MouseButton1Click:Connect(function()
		local Player = game:GetService'Players'.LocalPlayer;
		local UIS = game:GetService'UserInputService';
	
		_G.JumpHeight = 50;
	
		function Action(Object, Function) if Object ~= nil then Function(Object); end end
	
		UIS.InputBegan:connect(function(UserInput)
			if UserInput.UserInputType == Enum.UserInputType.Keyboard and UserInput.KeyCode == Enum.KeyCode.Space then
				Action(Player.Character.Humanoid, function(self)
					if self:GetState() == Enum.HumanoidStateType.Jumping or self:GetState() == Enum.HumanoidStateType.Freefall then
						Action(self.Parent.HumanoidRootPart, function(self)
							self.Velocity = Vector3.new(0, _G.JumpHeight, 0);
						end)
					end
				end)
			end
		end)
	
	end)
end
coroutine.wrap(OWQJOLH_fake_script)()
local function KFHBP_fake_script() -- MainButton.LocalScript 
	local script = Instance.new('LocalScript', MainButton)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.Parent.MainFrame.Visible == false then
			script.Parent.Parent.MainFrame.Visible = true
		else
			script.Parent.Parent.MainFrame.Visible = false
		end
	end)
end
coroutine.wrap(KFHBP_fake_script)()
