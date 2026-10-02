-- Tạo giao diện hình vuông trên màn hình
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")

ScreenGui.Parent = game:GetService("CoreGui") or game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui")

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(30, 30, 30) -- Màu xám đen
Frame.Position = UDim2.new(0.4, 0, 0.4, 0)         -- Vị trí giữa màn hình
Frame.Size = UDim2.new(0, 150, 0, 150)             -- Kích thước hình vuông (150x150)
Frame.Active = true
Frame.Draggable = true                             -- Cho phép kéo thả
