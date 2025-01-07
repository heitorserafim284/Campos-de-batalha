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
      		    game:GetService("Players").LocalPlayer:WaitForChild("Event"):FireServer()      
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
