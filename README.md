local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Script [Campos de Batalha AnM]", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
local Tab = Window:MakeTab({
	Name = "Yuta Ultimate",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Section = Tab:AddSection({
	Name = "Rika"
})
Tab:AddButton({
	Name = "Puro amor",
	Callback = function()
      		game:GetService("ReplicatedStorage"):WaitForChild("Yuta"):WaitForChild("love"):FireServer()
  	end    
})
Tab:AddButton({
	Name = "Expansão de domínio",
	Callback = function()
      		game:GetService("ReplicatedStorage"):WaitForChild("Yuta"):WaitForChild("ytd"):FireServer()
  	end    
})
Tab:AddButton({
	Name = "Imitação",
	Callback = function()
      		    game:GetService("Players").LocalPlayer.Character.Mimicry.Script.Event:FireServer()
  	end    
})
Tab:AddButton({
	Name = "Fala Amaldiçoada",
	Callback = function()
      		game:GetService("Players").LocalPlayer:WaitForChild("Mimicry"):FireServer()  
  	end    
})
local Tab = Window:MakeTab({
	Name = "Gojo Ultimate",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Section = Tab:AddSection({
	Name = "Seis Olhos"
})
Tab:AddButton({
	Name = "Void infinito 0.2s",
	Callback = function()
      		 game:GetService("Players").LocalPlayer.Character:FindFirstChild("Unlimited Void 0,2s").Domain.Event:FireServer()
  	end    
})
Tab:AddButton({
	Name = "Vazio Roxo",
	Callback = function()
      		game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("Purple"):FireServer()
  	end    
})
Tab:AddButton({
	Name = "Void Infinito (normal)",
	Callback = function()
      		game:GetService("Players").LocalPlayer:WaitForChild("InfinityVoid"):FireServer()
  	end    
})
Tab:AddButton({
	Name = "Maximo Vazio Roxo",
	Callback = function()
      		game:GetService("Players").LocalPlayer.Character:FindFirstChild("Maximum Hollow Purple").Skill.Event:FireServer()
  	end    
})
Tab:AddButton({
	Name = "Nuke Hollow Purple",
	Callback = function()
      		local args = {
    [1] = "FinalHollowPurple"
}

game:GetService("ReplicatedStorage"):WaitForChild("Events"):WaitForChild("Abilitys"):WaitForChild("Gojo"):FireServer(unpack(args))
  	end    
})
Tab:AddButton({
	Name = "Energia Reversa",
	Callback = function()
      		game:GetService("Players").LocalPlayer.Character:FindFirstChild("Reverse Cursed Technique").Script.Event:FireServer()
  	end    
})
Tab:AddButton({
	Name = "Um Seis Olhos",
	Callback = function()
      		game:GetService("Players").LocalPlayer.Character:FindFirstChild("One Six Eyes").Script.Event:FireServer()
  	end    
})
Tab:AddButton({
	Name = "Seis Olhos",
	Callback = function()
      		getNil("Event", "RemoteEvent"):FireServer()
  	end    
})
local Tab = Window:MakeTab({
	Name = "Itadori Ultimate",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Section = Tab:AddSection({
	Name = "Rei dos Flashs Negros"
})
Tab:AddButton({
	Name = "Flash Negro",
	Callback = function()
      		game:GetService("Players").LocalPlayer.Character:FindFirstChild("Black Flash").BlackFlash.Event:FireServer()
  	end    
})
Tab:AddButton({
	Name = "Arena de Boxe",
	Callback = function()
      		game:GetService("Players").LocalPlayer.Character:FindFirstChild("Boxing Arena").Skill.RingOfDeath:FireServer()
  	end    
})
local Tab = Window:MakeTab({
	Name = "Sukuna V1",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Section = Tab:AddSection({
	Name = "Rei das Maldições médio"
})
Tab:AddButton({
	Name = "Transformação",
	Callback = function()
      		game:GetService("ReplicatedStorage"):WaitForChild("Remotes"):WaitForChild("KingofCurses"):FireServer()
  	end    
})
Tab:AddButton({
	Name = "Corrida",
	Callback = function()
      		game:GetService("ReplicatedStorage"):WaitForChild("sukuna"):WaitForChild("remotes"):WaitForChild("rush"):FireServer()
  	end    
})
Tab:AddButton({
	Name = "Flecha de Fogo",
	Callback = function()
      		game:GetService("Players").LocalPlayer.Character:FindFirstChild("Flame Arrow").fire.event:FireServer()
  	end    
})
Tab:AddButton({
	Name = "Santuário Malevolente",
	Callback = function()
      		game:GetService("ReplicatedStorage"):WaitForChild("RyomenSukuna"):WaitForChild("MalevolentShrine"):WaitForChild("Gaymalev"):FireServer()
  	end    
})
local Tab = Window:MakeTab({
	Name = "Megumi",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Section = Tab:AddSection({
	Name = "Poder das Sombras"
})
Tab:AddButton({
	Name = "Elefante",
	Callback = function()
      		game:GetService("Players").LocalPlayer.Character:FindFirstChild("Max Elephant"):FindFirstChild("Max Elephant Strike")
  	end    
})
Tab:AddButton({
	Name = "Jardim das sombras",
	Callback = function()
      		game:GetService("Players").LocalPlayer.Character:FindFirstChild("Chimera Shadow Garden").Use.RemoteEvent:FireServer()
  	end    
})
local Tab = Window:MakeTab({
	Name = "Mahoraga",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Section = Tab:AddSection({
	Name = "Divino General"
})
Tab:AddButton({
	Name = "Mahoraga [Spawn]",
	Callback = function()
      		game:GetService("Players").LocalPlayer.Character.Mahoraga.Mahoraga.RemoteEvent:FireServer()
  	end    
})
Tab:AddButton({
	Name = "Corte do Mundo",
	Callback = function()
      		game:GetService("Players").LocalPlayer.Character:FindFirstChild("World Slash").LocalScript.RemoteEvent:FireServer()
  	end    
})
local Tab = Window:MakeTab({
	Name = "Sukuna V2",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Section = Tab:AddSection({
	Name = "Real Rei das Maldições"
})
Tab:AddButton({
	Name = "Transformação",
	Callback = function()
      		game:GetService("Players").LocalPlayer.Character:FindFirstChild("Mukbang Finger").Script.Event:FireServer()
  	end    
})
Tab:AddButton({
	Name = "Corte que corta o Mundo",
	Callback = function()
      		game:GetService("Players").LocalPlayer.Character:FindFirstChild("World Slash").LocalScript.RemoteEvent:FireServer()
  	end    
})
Tab:AddButton({
	Name = "Santuário Mais Malevolente",
	Callback = function()
      		local args = {
    [1] = {
        ["Function"] = "Fire",
        ["rootcf"] = CFrame.new(-4.287243366241455, 19.82301139831543, -107.4084701538086, -0.0625310018658638, -1.9844860959002125e-16, -0.9980430006980896, -1.7734168674496696e-16, 1, -1.877266415505497e-16, 0.9980430006980896, 1.6525588978129758e-16, -0.0625310018658638),
        ["Name"] = "MalevolentShrine"
    }
}

game:GetService("ReplicatedStorage"):WaitForChild("Server"):InvokeServer(unpack(args))
  	end    
})
Tab:AddButton({
	Name = "Spawnar Mahoraga",
	Callback = function()
      		local args = {
    [1] = Vector3.new(-23.44859504699707, 16.823013305664062, -121.48372650146484)
}

game:GetService("Players").LocalPlayer.Character:FindFirstChild("Summon Mahoraga").Use.RemoteEvent:FireServer(unpack(args))
  	end    
})
local Tab = Window:MakeTab({
	Name = "Saitama",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
local Section = Tab:AddSection({
	Name = "Raiva de Mosquito"
})
Tab:AddButton({
	Name = "Soco Sério",
	Callback = function()
      		game:GetService("Players").LocalPlayer.Character:FindFirstChild("Serious Punch").Punch.Event:FireServer()
  	end    
})
Tab:AddButton({
	Name = "Omnidirecional",
	Callback = function()
      		local args = {
    [1] = {
        ["Function"] = "Fire",
        ["Name"] = "OmniDirectionalPunch",
        ["rootpos"] = CFrame.new(391.7187805175781, 17.912107467651367, -91.8853759765625, -0.1877077966928482, -2.0872051309517303e-10, 0.9822249412536621, -7.71685215728013e-11, 1, 1.9775041326663967e-10, -0.9822249412536621, -3.867754727604478e-11, -0.1877077966928482)
    }
}

game:GetService("ReplicatedStorage"):WaitForChild("Server"):InvokeServer(unpack(args))
  	end    
})
