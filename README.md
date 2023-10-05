local DrRayLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/DrRay-UI-Library/main/DrRay.lua"))()
local window = DrRayLibrary:Load("Tekknoparrot😈", "Default")

local tab = DrRayLibrary.newTab("Thanatophobia", "ImageIdHere")

tab.newButton("God mode", "Makes Monster not Chase able!", function()
    
end)

tab.newToggle("Toggle", "Toggle! (prints the state)", true, function(toggleState)
    if toggleState then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new()
    else
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new()
    end
end)

tab.newToggle("Toggle", "Toggle! (prints the state)", true, function(toggleState)
    if toggleState then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new()
    else
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new()
    end
end)

tab.newToggle("Toggle", "Toggle! (prints the state)", true, function(toggleState)
    if toggleState then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new()
    else
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new()
    end
end)

tab.newToggle("Toggle", "Toggle! (prints the state)", true, function(toggleState)
    if toggleState then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new()
    else
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new()
    end
end)

tab.newSlider("Slider", "Epic slider", 1000, false, function(num)
    print(num)
end)
