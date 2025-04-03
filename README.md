--carregar biblioteca
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()


local Window = Fluent:CreateWindow({

    Title = "urso hub beta " .. Fluent.Version,

    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"

})

--notificação

Fluent:Notify({ Title = "urso hub", Content = " obrigado por executar urso hub" })

local Tabs = {

    Main = Window:AddTab({ Title = "scripts" }),
     Itens = Window:AddTab({ Title = "Itens" }),
     Players = Window:AddTab({ Title = "Players" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })

}
--parágrafos
Tabs.Main:AddParagraph({ Title = "Urso hub", Content = "scripts" })

--botões
Tabs.Main:AddButton({ Title = "Rael hub", Callback = function() 
loadstring(game:HttpGet"https://raw.githubusercontent.com/Laelmano24/Rael-Hub/main/main.txt")()
 end })
 
 Tabs.Main:AddButton({ Title = "Systembroken", Callback = function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/H20CalibreYT/SystemBroken/main/script"))()
 end })
 
 Tabs.Main:AddButton({ Title = "Fly", Callback = function() 
loadstring(game:HttpGet("https://raw.githubusercontent.com/XNEOFF/FlyGuiV3/main/FlyGuiV3.txt"))()
 end })
 
Tabs.Itens:AddButton({ Title = "jerk (r15)", Callback = function() 
loadstring(game:HttpGet("https://pastefy.app/YZoglOyJ/raw"))()
 end })
 
 Tabs.Itens:AddButton({ Title = "telecinese", Callback = function()
 loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Fe-Telekinesis-V5-21542"))()
end })

Tabs.Players:AddButton({ Title = "teleporte", Callback = function()
 loadstring(game:HttpGet("https://raw.githubusercontent.com/Toolbox231/Toolbox231/refs/heads/main/xz.txt"))()
end })
