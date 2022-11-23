local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

local Window = Library.CreateLib("Tom X Hub", "Synapse")

local Tab = Window:NewTab("Scripts ")

local Section = Tab:Scripts("Keyboard")

Section:UpdateSection("Credits")

Section:Credits("Made by UndeRRBLX SCRIPTS")

Section:Scripts("Pendulum Hub", "Many scripts", function()

    print("Clicked")

end)

button:UpdateSection("Test")

Section:Pendulum(Executed", "ToggleInfo", function(state)

    if state then

        print("Toggle On")

    else

        print("Toggle Off")

    end

end)

Section:NewKeybind("KeybindText", "KeybindInfo", Enum.KeyCode.F, function()

	print("You just clicked the bind")

end)

Section:NewKeybind("KeybindText", "KeybindInfo", Enum.KeyCode.F, function()

	Library:ToggleUI()

end)

local colors = {

    SchemeColor = Color3.fromRGB(0,255,255),

    Background = Color3.fromRGB(0, 0, 0),

    Header = Color3.fromRGB(0, 0, 0),

    TextColor = Color3.fromRGB(255,255,255),

    ElementColor = Color3.fromRGB(20, 20, 20)

}

local Window = Library.CreateLib("H", colors)


