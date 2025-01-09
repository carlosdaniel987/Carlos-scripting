-- carregar biblioteca
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

-- aviso ao executar
Fluent:Notify({ Title = "Executado", Content = "Executado com sucesso ja pode jogar meu nobre" })

local Window = Fluent:CreateWindow({
    Title = "CARL HUB O MELHOR Test" .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
})

local Tabs = {
    Main = Window:AddTab({ Title = "Main" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}
-- parágrafos
Tabs.Main:AddParagraph({ Title = "Carl hub test", Content = "CARL" })

-- botões
Tabs.Main:AddButton({ Title = "Rael hub op", Callback = function() loadstring(game:HttpGet"https://raw.githubusercontent.com/Laelmano24/Rael-Hub/main/main.txt")() end})
Tabs.Main:AddButton({ Title = "speed wave", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/speedwavevip/scriptspeed/refs/heads/main/Brookhaven_lraq"))() end })
Tabs.Main:AddButton({ Title = "Button", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/NocturneMoDz/BROOKHAVEN-GUI-/main/METAB", true))() end })
Tabs.Main:AddButton({ Title = "Button", Callback = function() loadstring(game:HttpGet("https://pastebin.com/raw/eQA4nfcw"))() end })
Tabs.Main:AddButton({ Title = "Button", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/JSFKGBASDJKHIOAFHDGHIUODSGBJKLFGDKSB/fe/refs/heads/main/AKBYPASSER"))() end })
Tabs.Main:AddButton({ Title = "Button", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/ScriptCentral-br/SCU/refs/heads/main/sc.md",true))() end })
Tabs.Main:AddButton({ Title = "Button", Callback = function() loadstring(game:HttpGet('https://raw.githubusercontent.com/kigredns/SanderXV4.2.2/refs/heads/main/NormalSS.lua'))() end })
Tabs.Main:AddButton({ Title = "Button", Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/gclich/GHUBV14XZ/main/Ghub_Main_Loader.txt"))() end })
Tabs.Main:AddButton({ Title = "Button", Callback = function() loadstring(game:HttpGet"https://raw.githubusercontent.com/carlosdaniel987/Carl-hub-novo/refs/heads/main/README.md")() end })
