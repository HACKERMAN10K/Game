local Player = game.Players.LocalPlayer

Player.Chatted:connect(function(cht)
	if cht:match(";autorefresh") then
spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[AUTO REFRESH ENABLED]"
wait(4)
message:Destroy()
end)

loadstring(game:HttpGet('https://pastebin.com/raw/VwZEwsmu'))()
	elseif cht:match(";chatlogs") then
loadstring(game:HttpGet('https://gist.githubusercontent.com/MRSBLACK999/75238caa149c55142096b5c75c7a49f4/raw/d819ba2ff929688092e6bf853e1718f59b242e2c/Chat%2520logs'))()
spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[SHOWING CHAT LOGS]"
wait(3)
message:Destroy()
end)
game:GetService("StarterGui"):SetCore("SendNotification", { 

	Title = "[Credit]";

	Text = "[To Owners]";

	Icon = "rbxthumb://type=Asset&id=https:8403291188&w=150&h=150"})

Duration = 5;  
	elseif cht:match(";chatart") then
loadstring(game:HttpGet("https://raw.githubusercontent.com/omegachadgaming/mongus/main/main.lua", true))()
spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[DO (.) THEN WORD]"
wait(4)
message:Destroy()
end)
	elseif cht:match(";clickflingtoggle") then
loadstring(game:HttpGet(('https://raw.githubusercontent.com/0Ben1/fe/main/obf_5wpM7bBcOPspmX7lQ3m75SrYNWqxZ858ai3tJdEAId6jSI05IOUB224FQ0VSAswH.lua.txt'),true))()
spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[FLING GUI LOADED]"
wait(1)
message:Destroy()
end)
	elseif cht:match(";infjump") then
local InfiniteJumpEnabled = true
game:GetService("UserInputService").JumpRequest:connect(function()
	if InfiniteJumpEnabled then
		game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
	end
end)

game:GetService("StarterGui"):SetCore("SendNotification", { 

	Title = "INF JUMP LOADED";

	Text = "JUMP TO THE STARS ,";

	Icon = "rbxthumb://type=Asset&id=https:8403291188&w=150&h=150"})

Duration = 70;
	elseif cht:match(";flytoggle") then
loadstring(game:HttpGet(('https://pastebin.com/raw/YvKv4AuY'),true))();
spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[FLY TOGGLE LOADED]"
wait(3)
message:Destroy()
end)
game:GetService("StarterGui"):SetCore("SendNotification", { 

	Title = "[Credit]";

	Text = "[To Owner]";

	Icon = "rbxthumb://type=Asset&id=https:8403291188&w=150&h=150"})

Duration = 5;  
	elseif cht:match(";antifling") then
loadstring(game:HttpGet("https://raw.githubusercontent.com/joshclark756/joshclark756-s-scripts/main/anti%20fling.lua",true))()
spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[ANTI FLING ENABLED]"
wait(3)
message:Destroy()
end)
game:GetService("StarterGui"):SetCore("SendNotification", { 

	Title = "[Info]";

	Text = "[Cant Be Flung Now]";

	Icon = "rbxthumb://type=Asset&id=https:8403291188&w=150&h=150"})

Duration = 5;  
	elseif cht:match(";invisibletool") then
loadstring(game:HttpGet("https://gist.githubusercontent.com/skid123skidlol/cd0d2dce51b3f20ad1aac941da06a1a1/raw/f58b98cce7d51e53ade94e7bb460e4f24fb7e0ff/%257BFE%257D%2520Invisible%2520Tool%2520(can%2520hold%2520tools)",true))()
spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[INVISIBLE TOOL GIVEN]"
wait(1)
message:Destroy()
end)
game:GetService("StarterGui"):SetCore("SendNotification", { 

	Title = "[Credit]";

	Text = "[To Owner]";

	Icon = "rbxthumb://type=Asset&id=https:8403291188&w=150&h=150"})

Duration = 5;
	elseif cht:match(";animation") then
loadstring(game:HttpGet('https://pastebin.com/raw/0MLPL32f'))()
spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[ANIMATION GUI LOADED]"
wait(2)
message:Destroy()
end)
	elseif cht:match(";clicktp") then
mouse = game.Players.LocalPlayer:GetMouse()
tool = Instance.new("Tool")
tool.RequiresHandle = false
tool.Name = "Equip to Click TP"
tool.Activated:connect(function()
local pos = mouse.Hit+Vector3.new(0,2.5,0)
pos = CFrame.new(pos.X,pos.Y,pos.Z)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos
end)
tool.Parent = game.Players.LocalPlayer.Backpack
	spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[CLICK TP GIVEN]"
wait(2)
message:Destroy()
end)
game:GetService("StarterGui"):SetCore("SendNotification", { 

	Title = "[Info]";

	Text = "[Give Click Tp Tools]";

	Icon = "rbxthumb://type=Asset&id=https:8403291188&w=150&h=150"})

Duration = 6;  
	elseif cht:match(";punch") then
loadstring(game:HttpGet("https://raw.githubusercontent.com/fedoratums/Base-Script/Base-Script/fedoratum punch fling",true))()
	spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[PUNCH FLING LOADED]"
wait(3)
message:Destroy()
end)
game:GetService("StarterGui"):SetCore("SendNotification", { 

	Title = "[Credit]";

	Text = "[To Owner]";

	Icon = "rbxthumb://type=Asset&id=https:8403291188&w=150&h=150"})

Duration = 5;  
	elseif cht:match(";goto random") then
for _, tool in ipairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
    if tool:IsA("Tool") then
         tool.Parent = game:GetService("Players").LocalPlayer.Character -- I didn't use Equip because the Equip function unequips any other tools in your character.
    end
end
loadstring(game:HttpGet('https://pastebin.com/raw/EHXrepL2'))()

for i,v in pairs ( game.Players:GetPlayers() ) do
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(v.Character.HumanoidRootPart.Position)
wait(0.5)
end
	spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[TELEPORT TO RANDOM]"
wait(3)
message:Destroy()
end)
game:GetService("StarterGui"):SetCore("SendNotification", { 

	Title = "[Credit]";

	Text = "[To Blackwatch Team]";

	Icon = "rbxthumb://type=Asset&id=https:8403291188&w=150&h=150"})

Duration = 5;  
	elseif cht:match(";fling others") then
spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[FLINGING ALL]"
wait(3)
message:Destroy()
end)

loadstring(game:HttpGet('https://pastebin.com/raw/7VuCuCEP'))()
game:GetService("StarterGui"):SetCore("SendNotification", { 

	Title = "[Info]";

	Text = "[Flings Everyone In Game]";

	Icon = "rbxthumb://type=Asset&id=https:8403291188&w=150&h=150"})

Duration = 6;  
	elseif cht:match(";blockhead") then
loadstring(game:HttpGet('https://pastebin.com/raw/ia9hQSTk'))()
	elseif cht:match(";lemon") then
local A_1 = "-----[Lemon Chat]----"
local A_2 = "All"
local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest
Event:FireServer(A_1, A_2)
local A_1 = "When Life Gives You Lemons What Do You Do With Them?"
local A_2 = "All"
local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest
Event:FireServer(A_1, A_2)
local A_1 = "You Pick Them Lemons Up And Squirt Them Right Back In Lifes Eyes"
local A_2 = "All"
local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest
Event:FireServer(A_1, A_2)
local A_1 = "Real Life Facts Tho"
local A_2 = "All"
local Event = game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest
Event:FireServer(A_1, A_2)
	spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[Lemon The Chat]"
wait(3)
message:Destroy()
end)
game:GetService("StarterGui"):SetCore("SendNotification", { 

	Title = "[Credit]";

	Text = "[To Mrs Black]";

	Icon = "rbxthumb://type=Asset&id=https:8403291188&w=150&h=150"})

Duration = 5;  
	elseif cht:match(";jump 50") then
		loadstring(game:HttpGet("https://pastebin.com/raw/JfCDcYFs", true))();
	elseif cht:match(";speed 100") then
		loadstring(game:HttpGet("https://pastebin.com/raw/xxsjQVVy", true))();
	elseif cht:match(";spin") then
loadstring(game:HttpGet('https://pastebin.com/raw/S5Xdbm8x'))()
spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[Spin Your Life Away]"
wait(4)
message:Destroy()
end)
	elseif cht:match(";infohub") then
loadstring(game:HttpGet(('https://pastebin.com/raw/5seCbYFa'),true))()
spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[INFO HUB LOADED]"
wait(2)
message:Destroy()
end)
game:GetService("StarterGui"):SetCore("SendNotification", { 

	Title = "[Credit]";

	Text = "[To MyWorld]";

	Icon = "rbxthumb://type=Asset&id=https:8403291188&w=150&h=150"})

Duration = 5;  
	elseif cht:match(";cmds") then
print(" [COMMAND LIST] ")
print(";invisibletool (Gives Invisible Tool)")
print(";clicktp (Gives Click Tp)")
print(";blockhead (Gives Block Head)")
print(";goto random (tp to random)")
print(";flytoggle (Gives Fly Toggle Gui)")
print(";infohub (Loads My Worlds Info Script)")
print(":clickflingtoggle (Loads Fling Gui)")
print(";fling Others (Fling Everyone)")
print(";chatlogs (Loads Chat Log Gui)")
print(";chatart (Loads Chat Art Script)")
print(";speed 100 (Gives You Speed)")
print(";jump 50 (Gives Jump Boost)")
print(";infjump (Gives Inf Jump)")
print(";antifling (Cant Be Flung)")
print(";lemon (Makes Lemon Quote)")
print(";spin (Makes You Spin)")
print(";autorefresh (Respawn Where Killed)")
print(";punch (Gives Fling Punch Tool)")
print(";animation (Loads Animation Gui)")
print(";cmds (Shows Command List)")
print("(MADE BY BLACKWATCH TEAM)")
spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[COMMAND LIST SHOWN]"
wait(2)
message:Destroy()
end)
game:GetService("StarterGui"):SetCore("SendNotification", { 

	Title = "Important Message";

	Text = "To See Command /console";

	Icon = "rbxthumb://type=Asset&id=https:8403291188&w=150&h=150"})

Duration = 20;  
elseif cht:match(";goofygui") then
loadstring(game:HttpGet('https://raw.githubusercontent.com/yeerma/1/main/the_greatest_script_ever_made'))()
 spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[Loaded Goofy Gui]"
wait(3)
message:Destroy()
end)
 end
end)

--lolll

game.StarterGui:SetCore("ChatMakeSystemMessage", {
	Text = "|[To see Command List Say ;cmds]|";
	Color = Color3.new(0, 15, 0);
	Font = Enum.Font.SourceSansBold;
	FontSize = Enum.FontSize.Size24;
})
 
game.StarterGui:SetCore("ChatMakeSystemMessage", {
	Text = "|[ONLY FOR UNSUPP GAMES!!!]|";
	Color = Color3.new(0, 18, 0);
	Font = Enum.Font.SourceSansBold;
	FontSize = Enum.FontSize.Size24;
})


spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "[GAMEKILLER loaded]"
wait(6)
message:Destroy()
end)
game:GetService("StarterGui"):SetCore("SendNotification", { 

	Title = "Info Message";

	Text = "Works for most all games";

	Icon = "rbxthumb://type=Asset&id=https:8403291188&w=150&h=150"})

Duration = 6;  

SecretServicePanel = Instance.new("ScreenGui")
HackGui = SecretServicePanel or Instance.new("ScreenGui",nil);
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local lol = Instance.new("Frame")
local unanchor = Instance.new("TextButton")
local skybox = Instance.new("TextButton")
local skybox2 = Instance.new("TextButton")
local thomas = Instance.new("TextButton")
local toad = Instance.new("TextButton")
local penicer = Instance.new("TextButton")
local luigi = Instance.new("TextButton")
local kill = Instance.new("TextButton")
local freeboo = Instance.new("TextButton")
local TextBox = Instance.new("TextBox")
local duckify = Instance.new("TextButton")
local fire = Instance.new("TextButton")
local fireparts = Instance.new("TextButton")
local freeass = Instance.new("TextButton")
local freeass2 = Instance.new("TextButton")
local decalspam = Instance.new("TextButton")
local colorall = Instance.new("TextButton")
local bighead2 = Instance.new("TextButton")
local bighead = Instance.new("TextButton")
local hub = Instance.new("TextButton")
local executor = Instance.new("TextButton")
local lol2 = Instance.new("Frame")
local execute = Instance.new("TextButton")
local TextBox_2 = Instance.new("TextBox")
local reset = Instance.new("TextButton")
local rejoin = Instance.new("TextButton")

--Properties:

HackGui.Name = "HackGui"
HackGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
HackGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
HackGui.DisplayOrder = 1999999999
HackGui.ResetOnSpawn = false

Frame.Parent = HackGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.Position = UDim2.new(0.0247272793, 0, 0.0271565504, 0)
Frame.Size = UDim2.new(0, 583, 0, 329)

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.Size = UDim2.new(0, 583, 0, 50)
TextLabel.Font = Enum.Font.Arial
TextLabel.Text = "Gamekiller executer"
TextLabel.TextColor3 = Color3.fromRGB(25, 25, 55)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextStrokeTransparency = 0.000
TextLabel.TextWrapped = true

lol.Name = "lol"
lol.Parent = Frame
lol.BackgroundColor3 = Color3.fromRGB(25, 55, 25)
lol.BackgroundTransparency = 0.800
lol.BorderColor3 = Color3.fromRGB(0, 0, 0)
lol.BorderSizePixel = 0
lol.Position = UDim2.new(0.169811636, 0, 0.249240115, 0)
lol.Size = UDim2.new(0, 429, 0, 188)
lol.Visible = false

unanchor.Name = "unanchor"
unanchor.Parent = lol
unanchor.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
unanchor.BorderColor3 = Color3.fromRGB(0, 0, 0)
unanchor.BorderSizePixel = 2
unanchor.Position = UDim2.new(0.597885311, 0, 0.26726988, 0)
unanchor.Size = UDim2.new(0, 62, 0, 44)
unanchor.Font = Enum.Font.Arial
unanchor.Text = "Destroy Server"
unanchor.TextColor3 = Color3.fromRGB(0, 0, 0)
unanchor.TextScaled = true
unanchor.TextSize = 14.000
unanchor.TextWrapped = true

skybox.Name = "skybox"
skybox.Parent = lol
skybox.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
skybox.BorderColor3 = Color3.fromRGB(0, 0, 0)
skybox.BorderSizePixel = 2
skybox.Position = UDim2.new(0.29998821, 0, 0.498272836, 0)
skybox.Size = UDim2.new(0, 62, 0, 44)
skybox.Font = Enum.Font.Arial
skybox.Text = "Coolkid SkyBox"
skybox.TextColor3 = Color3.fromRGB(0, 0, 0)
skybox.TextScaled = true
skybox.TextSize = 14.000
skybox.TextWrapped = true

skybox2.Name = "skybox2"
skybox2.Parent = lol
skybox2.BackgroundColor3 = Color3.fromRGB(25, 25, 55)
skybox2.BorderColor3 = Color3.fromRGB(0, 0, 0)
skybox2.BorderSizePixel = 2
skybox2.Position = UDim2.new(0.448154539, 0, 0.498272836, 0)
skybox2.Size = UDim2.new(0, 62, 0, 44)
skybox2.Font = Enum.Font.Arial
skybox2.Text = "Koopkid SkyBox"
skybox2.TextColor3 = Color3.fromRGB(0, 0, 0)
skybox2.TextScaled = true
skybox2.TextSize = 14.000
skybox2.TextWrapped = true

thomas.Name = "thomas"
thomas.Parent = lol
thomas.BackgroundColor3 = Color3.fromRGB(55, 25, 25)
thomas.BorderColor3 = Color3.fromRGB(0, 0, 0)
thomas.BorderSizePixel = 2
thomas.Position = UDim2.new(0.448972911, 0, 0.26726988, 0)
thomas.Size = UDim2.new(0, 62, 0, 44)
thomas.Font = Enum.Font.Arial
thomas.Text = "Thomas Engine"
thomas.TextColor3 = Color3.fromRGB(0, 0, 0)
thomas.TextScaled = true
thomas.TextSize = 14.000
thomas.TextWrapped = true

toad.Name = "toad"
toad.Parent = lol
toad.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
toad.BorderColor3 = Color3.fromRGB(0, 0, 0)
toad.BorderSizePixel = 2
toad.Position = UDim2.new(0.299502939, 0, 0.26726988, 0)
toad.Size = UDim2.new(0, 62, 0, 44)
toad.Font = Enum.Font.Arial
toad.Text = "Toad Rain"
toad.TextColor3 = Color3.fromRGB(0, 0, 0)
toad.TextScaled = true
toad.TextSize = 14.000
toad.TextWrapped = true

penicer.Name = "penicer"
penicer.Parent = lol
penicer.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
penicer.BorderColor3 = Color3.fromRGB(0, 0, 0)
penicer.BorderSizePixel = 2
penicer.Position = UDim2.new(0.597270668, 0, 0.499032676, 0)
penicer.Size = UDim2.new(0, 62, 0, 44)
penicer.Font = Enum.Font.Arial
penicer.Text = "Dick All"
penicer.TextColor3 = Color3.fromRGB(0, 0, 0)
penicer.TextScaled = true
penicer.TextSize = 14.000
penicer.TextWrapped = true

luigi.Name = "luigi"
luigi.Parent = lol
luigi.BackgroundColor3 = Color3.fromRGB(55, 25, 25)
luigi.BorderColor3 = Color3.fromRGB(0, 0, 0)
luigi.BorderSizePixel = 2
luigi.Position = UDim2.new(0.156711251, 0, 0.264756858, 0)
luigi.Size = UDim2.new(0, 62, 0, 44)
luigi.Font = Enum.Font.Arial
luigi.Text = "Luigi Rain"
luigi.TextColor3 = Color3.fromRGB(0, 0, 0)
luigi.TextScaled = true
luigi.TextSize = 14.000
luigi.TextWrapped = true

kill.Name = "kill"
kill.Parent = lol
kill.BackgroundColor3 = Color3.fromRGB(25, 25, 55)
kill.BorderColor3 = Color3.fromRGB(0, 0, 0)
kill.BorderSizePixel = 2
kill.Position = UDim2.new(0.742152214, 0, 0.26726988, 0)
kill.Size = UDim2.new(0, 62, 0, 44)
kill.Font = Enum.Font.Arial
kill.Text = "Kill All"
kill.TextColor3 = Color3.fromRGB(0, 0, 0)
kill.TextScaled = true
kill.TextSize = 14.000
kill.TextWrapped = true

freeboo.Name = "freeboo"
freeboo.Parent = lol
freeboo.BackgroundColor3 = Color3.fromRGB(25, 25, 55)
freeboo.BorderColor3 = Color3.fromRGB(0, 0, 0)
freeboo.BorderSizePixel = 2
freeboo.Position = UDim2.new(0.155721605, 0, 0.498272836, 0)
freeboo.Size = UDim2.new(0, 62, 0, 28)
freeboo.Font = Enum.Font.Arial
freeboo.Text = "Player Boobs"
freeboo.TextColor3 = Color3.fromRGB(0, 0, 0)
freeboo.TextScaled = true
freeboo.TextSize = 14.000
freeboo.TextWrapped = true

TextBox.Parent = freeboo
TextBox.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0, 0, 1, 0)
TextBox.Size = UDim2.new(0, 62, 0, 22)
TextBox.Font = Enum.Font.SourceSans
TextBox.PlaceholderText = "Player username here"
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextScaled = true
TextBox.TextSize = 14.000
TextBox.TextWrapped = true

duckify.Name = "duckify"
duckify.Parent = lol
duckify.BackgroundColor3 = Color3.fromRGB(25, 55, 25)
duckify.BorderColor3 = Color3.fromRGB(0, 0, 0)
duckify.BorderSizePixel = 2
duckify.Position = UDim2.new(0.0116561502, 0, 0.263997167, 0)
duckify.Size = UDim2.new(0, 62, 0, 44)
duckify.Font = Enum.Font.Arial
duckify.Text = "Duckify All"
duckify.TextColor3 = Color3.fromRGB(0, 0, 0)
duckify.TextScaled = true
duckify.TextSize = 14.000
duckify.TextWrapped = true

fire.Name = "fire"
fire.Parent = lol
fire.BackgroundColor3 = Color3.fromRGB(55, 25, 25)
fire.BorderColor3 = Color3.fromRGB(0, 0, 0)
fire.BorderSizePixel = 2
fire.Position = UDim2.new(0.0111795347, 0, 0.503358901, 0)
fire.Size = UDim2.new(0, 62, 0, 44)
fire.Font = Enum.Font.Arial
fire.Text = "Burn All"
fire.TextColor3 = Color3.fromRGB(0, 0, 0)
fire.TextScaled = true
fire.TextSize = 14.000
fire.TextWrapped = true

fireparts.Name = "fireparts"
fireparts.Parent = lol
fireparts.BackgroundColor3 = Color3.fromRGB(25, 55, 25)
fireparts.BorderColor3 = Color3.fromRGB(0, 0, 0)
fireparts.BorderSizePixel = 2
fireparts.Position = UDim2.new(0.741681278, 0, 0.499032676, 0)
fireparts.Size = UDim2.new(0, 62, 0, 44)
fireparts.Font = Enum.Font.Arial
fireparts.Text = "Burn Parts"
fireparts.TextColor3 = Color3.fromRGB(0, 0, 0)
fireparts.TextScaled = true
fireparts.TextSize = 14.000
fireparts.TextWrapped = true

freeass.Name = "freeass"
freeass.Parent = lol
freeass.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
freeass.BorderColor3 = Color3.fromRGB(0, 0, 0)
freeass.BorderSizePixel = 2
freeass.Position = UDim2.new(0.298591375, 0, 0.0203698333, 0)
freeass.Size = UDim2.new(0, 62, 0, 44)
freeass.Font = Enum.Font.Arial
freeass.Text = "Ass All"
freeass.TextColor3 = Color3.fromRGB(0, 0, 0)
freeass.TextScaled = true
freeass.TextSize = 14.000
freeass.TextWrapped = true

freeass2.Name = "freeass2"
freeass2.Parent = lol
freeass2.BackgroundColor3 = Color3.fromRGB(55, 25, 55)
freeass2.BorderColor3 = Color3.fromRGB(0, 0, 0)
freeass2.BorderSizePixel = 2
freeass2.Position = UDim2.new(0.594662249, 0, 0.0198432431, 0)
freeass2.Size = UDim2.new(0, 62, 0, 44)
freeass2.Font = Enum.Font.Arial
freeass2.Text = "BigAss All"
freeass2.TextColor3 = Color3.fromRGB(0, 0, 0)
freeass2.TextScaled = true
freeass2.TextSize = 14.000
freeass2.TextWrapped = true

decalspam.Name = "decalspam"
decalspam.Parent = lol
decalspam.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
decalspam.BorderColor3 = Color3.fromRGB(0, 0, 0)
decalspam.BorderSizePixel = 2
decalspam.Position = UDim2.new(0.740925252, 0, 0.0198432431, 0)
decalspam.Size = UDim2.new(0, 62, 0, 44)
decalspam.Font = Enum.Font.Arial
decalspam.Text = "Rc7 SkyBox"
decalspam.TextColor3 = Color3.fromRGB(0, 0, 0)
decalspam.TextScaled = true
decalspam.TextSize = 14.000
decalspam.TextWrapped = true

colorall.Name = "colorall"
colorall.Parent = lol
colorall.BackgroundColor3 = Color3.fromRGB(55, 25, 55)
colorall.BorderColor3 = Color3.fromRGB(0, 0, 0)
colorall.BorderSizePixel = 2
colorall.Position = UDim2.new(0.442593664, 0, 0.0198432431, 0)
colorall.Size = UDim2.new(0, 62, 0, 44)
colorall.Font = Enum.Font.Arial
colorall.Text = "Rainbow All"
colorall.TextColor3 = Color3.fromRGB(0, 0, 0)
colorall.TextScaled = true
colorall.TextSize = 14.000
colorall.TextWrapped = true

bighead2.Name = "bighead2"
bighead2.Parent = lol
bighead2.BackgroundColor3 = Color3.fromRGB(25, 25, 55)
bighead2.BorderColor3 = Color3.fromRGB(0, 0, 0)
bighead2.BorderSizePixel = 2
bighead2.Position = UDim2.new(0.157055557, 0, 0.0203698333, 0)
bighead2.Size = UDim2.new(0, 62, 0, 44)
bighead2.Font = Enum.Font.Arial
bighead2.Text = "Big Head"
bighead2.TextColor3 = Color3.fromRGB(0, 0, 0)
bighead2.TextScaled = true
bighead2.TextSize = 14.000
bighead2.TextWrapped = true

bighead.Name = "bighead"
bighead.Parent = lol
bighead.BackgroundColor3 = Color3.fromRGB(25, 25, 55)
bighead.BorderColor3 = Color3.fromRGB(0, 0, 0)
bighead.BorderSizePixel = 2
bighead.Position = UDim2.new(0.0113858311, 0, 0.0203698333, 0)
bighead.Size = UDim2.new(0, 62, 0, 44)
bighead.Font = Enum.Font.Arial
bighead.Text = "BigHead All"
bighead.TextColor3 = Color3.fromRGB(0, 0, 0)
bighead.TextScaled = true
bighead.TextSize = 14.000
bighead.TextWrapped = true

hub.Name = "hub"
hub.Parent = Frame
hub.BackgroundColor3 = Color3.fromRGB(55, 55, 25)
hub.BorderColor3 = Color3.fromRGB(0, 0, 0)
hub.BorderSizePixel = 2
hub.Position = UDim2.new(990.0128557002, 0, 0.293249637, 0)
hub.Size = UDim2.new(0, 81, 0, 29)
hub.Font = Enum.Font.Arial
hub.Text = "No"
hub.TextColor3 = Color3.fromRGB(0, 0, 0)
hub.TextScaled = true
hub.TextSize = 14.000
hub.TextWrapped = true

executor.Name = "executor"
executor.Parent = Frame
executor.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
executor.BorderColor3 = Color3.fromRGB(0, 0, 0)
executor.BorderSizePixel = 2
executor.Position = UDim2.new(0.195496023, 0, 0.150392473, 0)
executor.Size = UDim2.new(0, 97, 0, 124)
executor.Font = Enum.Font.Arial
executor.Text = "Script Executer"
executor.TextColor3 = Color3.fromRGB(0, 0, 0)
executor.TextScaled = true
executor.TextSize = 14.000
executor.TextWrapped = true

lol2.Name = "lol2"
lol2.Parent = Frame
lol2.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
lol2.BackgroundTransparency = 0.800
lol2.BorderColor3 = Color3.fromRGB(0, 0, 0)
lol2.BorderSizePixel = 0
lol2.Position = UDim2.new(0.169811636, 0, 0.249240115, 0)
lol2.Size = UDim2.new(0, 429, 0, 188)

execute.Name = "execute"
execute.Parent = lol2
execute.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
execute.BorderColor3 = Color3.fromRGB(0, 0, 0)
execute.BorderSizePixel = 2
execute.Position = UDim2.new(0.852877676, 0, 0.0416464284, 0)
execute.Size = UDim2.new(0, 53, 0, 35)
execute.Font = Enum.Font.Arial
execute.Text = "execute"
execute.TextColor3 = Color3.fromRGB(0, 0, 0)
execute.TextScaled = true
execute.TextSize = 14.000
execute.TextWrapped = true

TextBox_2.Parent = lol2
TextBox_2.BackgroundColor3 = Color3.fromRGB(116, 116, 116)
TextBox_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox_2.BorderSizePixel = 0
TextBox_2.Position = UDim2.new(0.221225008, 0, 0.0372340418, 0)
TextBox_2.Size = UDim2.new(0, 380 0, 173)
TextBox_2.Font = Enum.Font.SourceSansSemibold
TextBox_2.PlaceholderText = "[Paste script here]"
TextBox_2.Text = ""
TextBox_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox_2.TextSize = 18.000
TextBox_2.TextWrapped = true
TextBox_2.TextXAlignment = Enum.TextXAlignment.Left
TextBox_2.TextYAlignment = Enum.TextYAlignment.Top

reset.Name = "reset"
reset.Parent = Frame
reset.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
reset.BorderColor3 = Color3.fromRGB(0, 0, 0)
reset.BorderSizePixel = 2
reset.Position = UDim2.new(0.0291152354, 0, 0.873796761, 0)
reset.Size = UDim2.new(0, 97, 0, 24)
reset.Font = Enum.Font.Arial
reset.Text = "Respawn"
reset.TextColor3 = Color3.fromRGB(0, 0, 0)
reset.TextScaled = true
reset.TextSize = 14.000
reset.TextWrapped = true

rejoin.Name = "rejoin"
rejoin.Parent = Frame
rejoin.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
rejoin.BorderColor3 = Color3.fromRGB(0, 0, 0)
rejoin.BorderSizePixel = 2
rejoin.Position = UDim2.new(0.221225008, 0, 0.873796761, 0)
rejoin.Size = UDim2.new(0, 97, 0, 24)
rejoin.Font = Enum.Font.Arial
rejoin.Text = "Rejoin"
rejoin.TextColor3 = Color3.fromRGB(0, 0, 0)
rejoin.TextScaled = true
rejoin.TextSize = 14.000
rejoin.TextWrapped = true

-- Module Scripts:

local fake_module_scripts = {}

do -- lol.FE_BYPASS
	local script = Instance.new('ModuleScript', lol)
	script.Name = "FE_BYPASS"
	local function module_script()
		local module = {}
		
		function module.F3xinian()
			local player = game.Players.LocalPlayer
			local char = player.Character
			local tool
			for i,v in player:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
			for i,v in game.ReplicatedStorage:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
			--craaa
			local remote = tool.SyncAPI.ServerEndpoint
			local function remoteExecute(args)
				remote:InvokeServer(unpack(args))
			end
			local function SetCollision(part,boolean)
				local args = {
					[1] = "SyncCollision",
					[2] = {
						[1] = {
							["Part"] = part,
							["CanCollide"] = boolean
						}
					}
				}
				remoteExecute(args)
			end
			local function SetAnchor(boolean,part)
				local args = {
					[1] = "SyncAnchor",
					[2] = {
						[1] = {
							["Part"] = part,
							["Anchored"] = boolean
						}
					}
				}
				remoteExecute(args)
			end
			local function CreatePart(cf,parent)
				local args = {
					[1] = "CreatePart",
					[2] = "Normal",
					[3] = cf,
					[4] = parent
				}
				remoteExecute(args)
			end
			local function DestroyPart(part)
				local args = {
					[1] = "Remove",
					[2] = {
						[1] = part
					}
				}
				remoteExecute(args)
			end
			local function MovePart(part,cf)
				local args = {
					[1] = "SyncMove",
					[2] = {
						[1] = {
							["Part"] = part,
							["CFrame"] = cf
						}
					}
				}
				remoteExecute(args)
			end
			local function Resize(part,size,cf)
				local args = {
					[1] = "SyncResize",
					[2] = {
						[1] = {
							["Part"] = part,
							["CFrame"] = cf,
							["Size"] = size
						}
					}
				}
				remoteExecute(args)
			end
			local function AddMesh(part)
				local args = {
					[1] = "CreateMeshes",
					[2] = {
						[1] = {
							["Part"] = part
						}
					}
				}
				remoteExecute(args)
			end
		
			local function SetMesh(part,meshid)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["MeshId"] = "rbxassetid://"..meshid
						}
					}
				}
				remoteExecute(args)
			end
			local function SetTexture(part, texid)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["TextureId"] = "rbxassetid://"..texid
						}
					}
				}
				remoteExecute(args)
			end
			local function SetName(part, stringg)
				local args = {
					[1] = "SetName",
					[2] = {
						[1] = part
					},
					[3] = stringg
				}
		
				remoteExecute(args)
			end
			local function MeshResize(part,size)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["Scale"] = size
						}
					}
				}
				remoteExecute(args)
			end
			local function Weld(part1, part2,lead)
				local args = {
					[1] = "CreateWelds",
					[2] = {
						[1] = part1,
						[2] = part2
					},
					[3] = lead
				}
				remoteExecute(args)
		
			end
			local function SetLocked(part,boolean)
				local args = {
					[1] = "SetLocked",
					[2] = {
						[1] = part
					},
					[3] = boolean
				}
				remoteExecute(args)
			end
			local function SetTrans(part,int)
				local args = {
					[1] = "SyncMaterial",
					[2] = {
						[1] = {
							["Part"] = part,
							["Transparency"] = int
						}
					}
				}
				remoteExecute(args)
			end
			local function CreateSpotlight(part)
				local args = {
					[1] = "CreateLights",
					[2] = {
						[1] = {
							["Part"] = part,
							["LightType"] = "SpotLight"
						}
					}
				}
				remoteExecute(args)
			end
			local function SyncLighting(part,brightness)
				local args = {
					[1] = "SyncLighting",
					[2] = {
						[1] = {
							["Part"] = part,
							["LightType"] = "SpotLight",
							["Brightness"] = brightness
						}
					}
				}
				remoteExecute(args)
			end
			local function Color(part,color)
				local args = {
					[1] = "SyncColor",
					[2] = {
						[1] = {
							["Part"] = part,
							["Color"] = color --[[Color3]],
							["UnionColoring"] = false
						}
					}
				}
				remoteExecute(args)
			end
			local function SpawnDecal(part,side)
				local args = {
					[1] = "CreateTextures",
					[2] = {
						[1] = {
							["Part"] = part,
							["Face"] = side,
							["TextureType"] = "Decal"
						}
					}
				}
		
				remoteExecute(args)
			end
			local function AddDecal(part,asset,side)
				local args = {
					[1] = "SyncTexture",
					[2] = {
						[1] = {
							["Part"] = part,
							["Face"] = side,
							["TextureType"] = "Decal",
							["Texture"] = "rbxassetid://".. asset
						}
					}
				}
				remoteExecute(args)
			end
			local febypass = {}
		
			febypass.SetCollision = SetCollision
			febypass.SetAnchor = SetAnchor
			febypass.CreatePart = CreatePart
			febypass.DestroyPart = DestroyPart
			febypass.MovePart = MovePart
			febypass.Resize = Resize
			febypass.AddMesh = AddMesh
			febypass.SetMesh = SetMesh
			febypass.SetTexture = SetTexture
			febypass.SetName = SetName
			febypass.MeshResize = MeshResize
			febypass.Weld = Weld
			febypass.SetLocked = SetLocked
			febypass.SetTrans = SetTrans
			febypass.CreateSpotlight = CreateSpotlight
			febypass.SyncLighting = SyncLighting
			febypass.Color = Color
			febypass.SpawnDecal = SpawnDecal
			febypass.AddDecal = AddDecal
			febypass.remoteExecute = remoteExecute
		
			return febypass
		end
		
		return module
	end
	fake_module_scripts[script] = module_script
end
do -- lol2.FE_BYPASS
	local script = Instance.new('ModuleScript', lol2)
	script.Name = "FE_BYPASS"
	local function module_script()
		local module = {}
		
		function module.F3xinian()
			local player = game.Players.LocalPlayer
			local char = player.Character
			local tool
			for i,v in player:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
			for i,v in game.ReplicatedStorage:GetDescendants() do
				if v.Name == "SyncAPI" then
					tool = v.Parent
				end
			end
			--craaa
			local remote = tool.SyncAPI.ServerEndpoint
			local function remoteExecute(args)
				remote:InvokeServer(unpack(args))
			end
			local function SetCollision(part,boolean)
				local args = {
					[1] = "SyncCollision",
					[2] = {
						[1] = {
							["Part"] = part,
							["CanCollide"] = boolean
						}
					}
				}
				remoteExecute(args)
			end
			local function SetAnchor(boolean,part)
				local args = {
					[1] = "SyncAnchor",
					[2] = {
						[1] = {
							["Part"] = part,
							["Anchored"] = boolean
						}
					}
				}
				remoteExecute(args)
			end
			local function CreatePart(cf,parent)
				local args = {
					[1] = "CreatePart",
					[2] = "Normal",
					[3] = cf,
					[4] = parent
				}
				remoteExecute(args)
			end
			local function DestroyPart(part)
				local args = {
					[1] = "Remove",
					[2] = {
						[1] = part
					}
				}
				remoteExecute(args)
			end
			local function MovePart(part,cf)
				local args = {
					[1] = "SyncMove",
					[2] = {
						[1] = {
							["Part"] = part,
							["CFrame"] = cf
						}
					}
				}
				remoteExecute(args)
			end
			local function Resize(part,size,cf)
				local args = {
					[1] = "SyncResize",
					[2] = {
						[1] = {
							["Part"] = part,
							["CFrame"] = cf,
							["Size"] = size
						}
					}
				}
				remoteExecute(args)
			end
			local function AddMesh(part)
				local args = {
					[1] = "CreateMeshes",
					[2] = {
						[1] = {
							["Part"] = part
						}
					}
				}
				remoteExecute(args)
			end
		
			local function SetMesh(part,meshid)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["MeshId"] = "rbxassetid://"..meshid
						}
					}
				}
				remoteExecute(args)
			end
			local function SetTexture(part, texid)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["TextureId"] = "rbxassetid://"..texid
						}
					}
				}
				remoteExecute(args)
			end
			local function SetName(part, stringg)
				local args = {
					[1] = "SetName",
					[2] = {
						[1] = part
					},
					[3] = stringg
				}
		
				remoteExecute(args)
			end
			local function MeshResize(part,size)
				local args = {
					[1] = "SyncMesh",
					[2] = {
						[1] = {
							["Part"] = part,
							["Scale"] = size
						}
					}
				}
				remoteExecute(args)
			end
			local function Weld(part1, part2,lead)
				local args = {
					[1] = "CreateWelds",
					[2] = {
						[1] = part1,
						[2] = part2
					},
					[3] = lead
				}
				remoteExecute(args)
		
			end
			local function SetLocked(part,boolean)
				local args = {
					[1] = "SetLocked",
					[2] = {
						[1] = part
					},
					[3] = boolean
				}
				remoteExecute(args)
			end
			local function SetTrans(part,int)
				local args = {
					[1] = "SyncMaterial",
					[2] = {
						[1] = {
							["Part"] = part,
							["Transparency"] = int
						}
					}
				}
				remoteExecute(args)
			end
			local function CreateSpotlight(part)
				local args = {
					[1] = "CreateLights",
					[2] = {
						[1] = {
							["Part"] = part,
							["LightType"] = "SpotLight"
						}
					}
				}
				remoteExecute(args)
			end
			local function SyncLighting(part,brightness)
				local args = {
					[1] = "SyncLighting",
					[2] = {
						[1] = {
							["Part"] = part,
							["LightType"] = "SpotLight",
							["Brightness"] = brightness
						}
					}
				}
				remoteExecute(args)
			end
			local function Color(part,color)
				local args = {
					[1] = "SyncColor",
					[2] = {
						[1] = {
							["Part"] = part,
							["Color"] = color --[[Color3]],
							["UnionColoring"] = false
						}
					}
				}
				remoteExecute(args)
			end
			local function SpawnDecal(part,side)
				local args = {
					[1] = "CreateTextures",
					[2] = {
						[1] = {
							["Part"] = part,
							["Face"] = side,
							["TextureType"] = "Decal"
						}
					}
				}
		
				remoteExecute(args)
			end
			local function AddDecal(part,asset,side)
				local args = {
					[1] = "SyncTexture",
					[2] = {
						[1] = {
							["Part"] = part,
							["Face"] = side,
							["TextureType"] = "Decal",
							["Texture"] = "rbxassetid://".. asset
						}
					}
				}
				remoteExecute(args)
			end
			local febypass = {}
		
			febypass.SetCollision = SetCollision
			febypass.SetAnchor = SetAnchor
			febypass.CreatePart = CreatePart
			febypass.DestroyPart = DestroyPart
			febypass.MovePart = MovePart
			febypass.Resize = Resize
			febypass.AddMesh = AddMesh
			febypass.SetMesh = SetMesh
			febypass.SetTexture = SetTexture
			febypass.SetName = SetName
			febypass.MeshResize = MeshResize
			febypass.Weld = Weld
			febypass.SetLocked = SetLocked
			febypass.SetTrans = SetTrans
			febypass.CreateSpotlight = CreateSpotlight
			febypass.SyncLighting = SyncLighting
			febypass.Color = Color
			febypass.SpawnDecal = SpawnDecal
			febypass.AddDecal = AddDecal
			febypass.remoteExecute = remoteExecute
		
			return febypass
		end
		
		return module
	end
	fake_module_scripts[script] = module_script
end


-- Scripts:

local function EKBUF_fake_script() -- Frame.MainButtons 
	local script = Instance.new('LocalScript', Frame)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.hub.MouseButton1Click:Connect(function()
		script.Parent.lol.Visible = true
		script.Parent.lol2.Visible = false
	end)
	script.Parent.executor.MouseButton1Click:Connect(function()
		script.Parent.lol.Visible = false
		script.Parent.lol2.Visible = true
	end)
	
	script.Parent.reset.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character:FindFirstChild("Head"):Destroy()
	end)
	script.Parent.rejoin.MouseButton1Click:Connect(function()
		game:GetService'TeleportService':TeleportToPlaceInstance(game['PlaceId'],game['JobId'])
	end)
end
coroutine.wrap(EKBUF_fake_script)()
local function TFSAGP_fake_script() -- Frame.Drag 
	local script = Instance.new('LocalScript', Frame)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.Active = true
	script.Parent.Draggable = true
end
coroutine.wrap(TFSAGP_fake_script)()
local function BLRBG_fake_script() -- lol.MainButtons 
	local script = Instance.new('LocalScript', lol)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	local loader = {}
	function loader.load_febypass()
		return require(script.Parent:WaitForChild("FE_BYPASS")).F3xinian()
	end
	
	script.Parent.bighead.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
	
		local function BigHead(player)
			local chara = player.Character
			spawn(function()
				febypass.SetLocked(chara.Head,false)
				febypass.MeshResize(chara.Head,Vector3.new(10,10,10))
			end)
		end
		for i,players in game.Players:GetPlayers() do
			BigHead(players)
		end
	end)
	script.Parent.bighead2.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
	
		local function BigHead(player)
			local chara = player.Character
			spawn(function()
				febypass.SetLocked(chara.Head,false)
				febypass.MeshResize(chara.Head,Vector3.new(10,10,10))
			end)
		end
		BigHead(game.Players.LocalPlayer)
	end)
	script.Parent.freeass.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local function Bum(player)
			local char = player.Character
			for i,v in char:GetChildren() do
				pcall(function()
					febypass.SetLocked(v,false)
				end)
			end
			if player.Character:FindFirstChild("Part1") then
				return
			else
	
				febypass.SetAnchor(true,player.Character.HumanoidRootPart)
				spawn(function()
					febypass.CreatePart(player.Character:WaitForChild("Right Leg").CFrame * CFrame.new(0,1,0.6),player.Character)
					febypass.SetName(player.Character.Part,"Part1")
					febypass.CreatePart(player.Character:WaitForChild("Left Leg").CFrame * CFrame.new(0,1,0.6),player.Character)
					febypass.SetName(player.Character.Part,"Part2")
				end)
				wait(0.2)
				repeat wait() until char:FindFirstChild("Part2")
				spawn(function()
					febypass.AddMesh(char.Part1)
					febypass.AddMesh(char.Part2)
					febypass.SetMesh(char.Part1,"5697933202")
					febypass.SetMesh(char.Part2,"5697933202")
				end)
				wait(0.2)
				repeat wait() until char.Part2:FindFirstChild("Mesh")
				spawn(function()
					febypass.MeshResize(char.Part1,Vector3.new(0.5,0.5,0.5))
					febypass.MeshResize(char.Part2,Vector3.new(0.5,0.5,0.5))
				end)
				wait(0.2)
				pcall(function()
					febypass.Color(char.Part1,char:WaitForChild("Right Leg").Color)
					febypass.Color(char.Part2,char:WaitForChild("Left Leg").Color)
				end)
				wait(0.2)
				spawn(function()
					febypass.SetCollision(player.Character.Part1,false)
					febypass.SetCollision(player.Character.Part2,false)
					febypass.Weld(char.Part1,char.HumanoidRootPart,char.Part1)
					febypass.Weld(char.Part2,char.Part1,char.Part2)
				end)
				repeat wait() until char.Part2:FindFirstChild("BTWeld")
				spawn(function()
					febypass.SetAnchor(false,char.HumanoidRootPart)
					febypass.SetAnchor(false,char.Part1)
					febypass.SetAnchor(false,char.Part2)
				end)
				repeat wait()
					febypass.SetAnchor(false,char.HumanoidRootPart)
					febypass.SetAnchor(false,char.Part1)
					febypass.SetAnchor(false,char.Part2)
				until char.Part2.Anchored == false
			end
		end
		for i, players in next, game.Players:players() do
			spawn(function()
				Bum(players)
			end)
		end
	end)
	script.Parent.freeass2.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local function Bum(player)
			local char = player.Character
			for i,v in char:GetChildren() do
				pcall(function()
					febypass.SetLocked(v,false)
				end)
			end
			if player.Character:FindFirstChild("Part1") then
				return
			else
	
				febypass.SetAnchor(true,player.Character.HumanoidRootPart)
				spawn(function()
					febypass.CreatePart(player.Character:WaitForChild("Right Leg").CFrame * CFrame.new(0,1,0.6),player.Character)
					febypass.SetName(player.Character.Part,"Part1")
					febypass.CreatePart(player.Character:WaitForChild("Left Leg").CFrame * CFrame.new(0,1,0.6),player.Character)
					febypass.SetName(player.Character.Part,"Part2")
				end)
				wait(0.2)
				repeat wait() until char:FindFirstChild("Part2")
				spawn(function()
					febypass.AddMesh(char.Part1)
					febypass.AddMesh(char.Part2)
					febypass.SetMesh(char.Part1,"5697933202")
					febypass.SetMesh(char.Part2,"5697933202")
				end)
				wait(0.2)
				repeat wait() until char.Part2:FindFirstChild("Mesh")
				spawn(function()
					febypass.MeshResize(char.Part1,Vector3.new(0.5,0.5,0.5))
					febypass.MeshResize(char.Part2,Vector3.new(0.5,0.5,0.5))
				end)
				wait(0.2)
				pcall(function()
					febypass.Color(char.Part1,char:WaitForChild("Right Leg").Color)
					febypass.Color(char.Part2,char:WaitForChild("Left Leg").Color)
				end)
				wait(0.2)
				spawn(function()
					febypass.SetCollision(player.Character.Part1,false)
					febypass.SetCollision(player.Character.Part2,false)
					febypass.Weld(char.Part1,char.HumanoidRootPart,char.Part1)
					febypass.Weld(char.Part2,char.Part1,char.Part2)
				end)
				repeat wait() until char.Part2:FindFirstChild("BTWeld")
				spawn(function()
					febypass.SetAnchor(false,char.HumanoidRootPart)
					febypass.SetAnchor(false,char.Part1)
					febypass.SetAnchor(false,char.Part2)
				end)
				repeat wait()
					febypass.SetAnchor(false,char.HumanoidRootPart)
					febypass.SetAnchor(false,char.Part1)
					febypass.SetAnchor(false,char.Part2)
				until char.Part2.Anchored == false
			end
		end
		Bum(game.Players.LocalPlayer)
	end)
	script.Parent.colorall.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local function randomise()
			for i,v in game.Workspace:GetDescendants() do
				if v:IsA("BasePart") then
					spawn(function()
						febypass.SetLocked(v,false)
						febypass.Color(v,Color3.new(math.random(0,255),math.random(0,255),math.random(0,255)))
					end)
				end
			end
		end
		while wait() do
			spawn(function()
				randomise()
			end)
		end
	end)
	
	script.Parent.decalspam.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local function spam(id)
			for i,v in game.workspace:GetDescendants() do
				if v:IsA("BasePart") then
					spawn(function()
						febypass.SetLocked(v,false)
						febypass.SpawnDecal(v,Enum.NormalId.Front)
						febypass.AddDecal(v,id,Enum.NormalId.Front)
	
						febypass.SpawnDecal(v,Enum.NormalId.Back)
						febypass.AddDecal(v,id,Enum.NormalId.Back)
	
						febypass.SpawnDecal(v,Enum.NormalId.Right)
						febypass.AddDecal(v,id,Enum.NormalId.Right)
	
						febypass.SpawnDecal(v,Enum.NormalId.Left)
						febypass.AddDecal(v,id,Enum.NormalId.Left)
	
						febypass.SpawnDecal(v,Enum.NormalId.Bottom)
						febypass.AddDecal(v,id,Enum.NormalId.Bottom)
	
						febypass.SpawnDecal(v,Enum.NormalId.Top)
						febypass.AddDecal(v,id,Enum.NormalId.Top)
					end)
				end
			end 
		end
		spam("1488984727")
	end)
	
	script.Parent.duckify.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local function Duckify(player)
			for i,v in player.Character:GetDescendants() do
				if v:IsA("BasePart") then
					pcall(function()
						febypass.SetLocked(v,false)
						febypass.SetTrans(v,1)
					end)
				end
			end
			local char = player.Character
			--spawn(function()
			spawn(function()
				febypass.SetAnchor(true,char.HumanoidRootPart)
				febypass.CreatePart(char.HumanoidRootPart.CFrame,char)
				febypass.SetCollision(char.Part,false)
				febypass.SetName(char.Part, "Duck")
			end)
			repeat wait() until char:FindFirstChild("Duck")
			spawn(function()
				febypass.SetLocked(char.Duck,false)
				febypass.SetLocked(char.HumanoidRootPart,false)
				febypass.Weld(char.Duck,char.HumanoidRootPart,char.Duck)
				febypass.SetAnchor(false,char.Duck)
				febypass.AddMesh(char.Duck)
			end)
			repeat wait() until char.Duck:FindFirstChild("Mesh")
			febypass.MeshResize(char.Duck,Vector3.new(8,8,8))
			febypass.SetMesh(char.Duck,"10749878672")
			febypass.SetTexture(char.Duck,"10749878886")
			febypass.SetAnchor(false,char.HumanoidRootPart)
			--end)
		end
		for i,v in game.Players:GetPlayers() do
			--spawn(function()
			Duckify(v)
			--end)
		end
	end)
	
	script.Parent.fire.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local function AddFire(part)
			local args = {
				[1] = "CreateDecorations",
				[2] = {
					[1] = {
						["Part"] = part,
						["DecorationType"] = "Fire"
					}
				}
			}
			febypass.remoteExecute(args)
		end
		local function Fire(player)
			for i,v in player.Character:GetDescendants() do
				if v:IsA("BasePart") then
					AddFire(v)
				end
			end
		end
	
		for i,v in game.Players:GetPlayers() do
			spawn(function()
				pcall(function()
					Fire(v)
				end)
			end)
		end
	end)
	
	script.Parent.luigi.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local hrpcf = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		while wait(0.5) do
			local x = hrpcf.x
			local z = hrpcf.z
			local randint = math.random(-600,600)
			local randint2 = math.random(-600,600)
			local xloc = randint + x
			local zloc = randint2 + z
			local cf = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.y + 400
			spawn(function()
				febypass.CreatePart(CFrame.new(math.floor(xloc), math.random(cf,cf+400), math.floor(zloc)))
				for i,v in game.Workspace:GetDescendants() do
					if v.Name == "Part" and v.Parent == workspace and v.CFrame.x == math.floor(xloc) and v.CFrame.z == math.floor(zloc) then
						febypass.SetName(v,"b_1337")
						febypass.SetAnchor(false,v)
						febypass.AddMesh(v)
						febypass.Resize(v, Vector3.new(100,100,100),v.CFrame)
						febypass.MeshResize(v,Vector3.new(20,20,20))
						febypass.SetMesh(v,"1618237875")
						febypass.SetTexture(v, "1618237897")
						febypass.SetCollision(v,false)
					else
					end
				end
			end)
		end
	end)
	
	script.Parent.toad.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local hrpcf = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
		while wait(0.5) do
			local x = hrpcf.x
			local z = hrpcf.z
			local randint = math.random(-600,600)
			local randint2 = math.random(-600,600)
			local xloc = randint + x
			local zloc = randint2 + z
			local cf = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.y + 400
			spawn(function()
				febypass.CreatePart(CFrame.new(math.floor(xloc), math.random(cf,cf+400), math.floor(zloc)))
				for i,v:Instance in game.Workspace:GetDescendants() do
					if v.Name == "Part" and v.Parent == workspace and v.CFrame.x == math.floor(xloc) and v.CFrame.z == math.floor(zloc) and v:IsA("Part") then
						febypass.SetName(v,"b_1337")
						febypass.SetAnchor(false,v)
						febypass.AddMesh(v)
						febypass.Resize(v, Vector3.new(100,100,100),v.CFrame)
						febypass.MeshResize(v,Vector3.new(20,20,20))
						febypass.SetMesh(v,"614605299")
						febypass.SetTexture(v, "614605300")
						febypass.SetCollision(v,false)
					else
					end
				end	
			end)
		end
	end)
	
	script.Parent.thomas.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local function Thomas(player)
			local char = player.Character
			febypass.SetAnchor(true,char.HumanoidRootPart)
			febypass.CreatePart(char.HumanoidRootPart.CFrame,char)
			febypass.SetCollision(char.Part,false)
			febypass.SetLocked(char.Part,false)
			febypass.CreateSpotlight(char.Part)
			febypass.SyncLighting(char.Part,100)
			febypass.SetLocked(char.HumanoidRootPart,false)
			febypass.Weld(char.Part,char.HumanoidRootPart,char.Part)
			febypass.SetAnchor(false,char.Part)
			febypass.AddMesh(char.Part)
			febypass.MeshResize(char.Part,Vector3.new(3,3,3))
			febypass.SetMesh(char.Part,"4340968808")
			febypass.SetTexture(char.Part,"4340968918")
			febypass.SetAnchor(false,char.HumanoidRootPart)
			char.Humanoid.WalkSpeed = 100
			char.HumanoidRootPart.Touched:connect(function(obj)
				if obj.Parent:FindFirstChild("HumanoidRootPart") then
					febypass.SetLocked(obj.Parent.HumanoidRootPart,false)
					febypass.DestroyPart(obj.Parent.HumanoidRootPart)
					spawn(function()
					wait(2)
					febypass.SetLocked(obj.Parent.Head,false)
					febypass.DestroyPart(obj.Parent.Head)
					end)
				end
			end)
			game:GetService("RunService").RenderStepped:Connect(function()
				for i,v in char:GetDescendants() do
					if v:IsA("BasePart") then
						char.Humanoid.WalkSpeed = 100
						v.CanCollide = false
					end
				end
			end)
		end
		Thomas(game.Players.LocalPlayer)
	end)
	
	script.Parent.unanchor.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local function Unanchor()
			for i,v in game.Workspace:GetDescendants() do
				spawn(function()
					febypass.SetLocked(v,false)
					febypass.SetAnchor(false,v)
				end)
			end
		end
		Unanchor()
	end)
	
	script.Parent.kill.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local function KillAll()
			for i,v in game.Players:GetPlayers() do
				spawn(function()
					febypass.SetLocked(v.Character.Head,false)
					febypass.DestroyPart(v.Character.Head)
				end)
			end
		end
		KillAll()
	end)
	
	script.Parent.freeboo.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local function Boob(player)
			local char = player.Character
			for i,v in char:GetChildren() do
				pcall(function()
					febypass.SetLocked(v,false)
				end)
			end
			if player.Character:FindFirstChild("Boob2") then
				return
			else
	
				febypass.SetAnchor(true,player.Character.HumanoidRootPart)
				spawn(function()
					febypass.CreatePart(player.Character:WaitForChild("Right Leg").CFrame * CFrame.new(0,2,-0.6),player.Character)
					febypass.SetName(player.Character.Part,"Boob1")
					febypass.CreatePart(player.Character:WaitForChild("Left Leg").CFrame * CFrame.new(0,2,-0.6),player.Character)
					febypass.SetName(player.Character.Part,"Boob2")
				end)
				wait(0.2)
				repeat wait() until char:FindFirstChild("Boob2")
				spawn(function()
					febypass.AddMesh(char.Boob1)
					febypass.AddMesh(char.Boob2)
					febypass.SetMesh(char.Boob1,"5697933202")
					febypass.SetMesh(char.Boob2,"5697933202")
				end)
				wait(0.2)
				repeat wait() until char.Boob2:FindFirstChild("Mesh")
				febypass.MeshResize(char.Boob1,Vector3.new(0.4,0.4,0.4))
				febypass.MeshResize(char.Boob2,Vector3.new(0.4,0.4,0.4))
				pcall(function()
					febypass.Color(char.Boob1,char:WaitForChild("Torso").Color)
					febypass.Color(char.Boob2,char:WaitForChild("Torso").Color)
				end)
				wait(0.2)
				spawn(function()
					febypass.SetCollision(player.Character.Boob1,false)
					febypass.SetCollision(player.Character.Boob2,false)
					febypass.Weld(char.Boob1,char.HumanoidRootPart,char.Boob1)
					febypass.Weld(char.Boob2,char.Boob1,char.Boob2)
				end)
				repeat wait() until char.Boob2:FindFirstChild("BTWeld")
				for i,v in char:GetChildren() do
					pcall(function()
						febypass.SetLocked(v,false)
					end)
				end
				for i,v in char:GetChildren() do
					pcall(function()
						febypass.SetAnchor(false,v)
					end)
				end
				spawn(function()
					febypass.SetAnchor(false,char.HumanoidRootPart)
					febypass.SetAnchor(false,char.Boob1)
					febypass.SetAnchor(false,char.Boob2)
				end)
			end
		end
		Boob(game.Players:FindFirstChild(script.Parent.freeboo.TextBox.Text))
	end)
	
	script.Parent.skybox.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local function Sky(id)
			local char = game.Players.LocalPlayer.Character
			local e = char.HumanoidRootPart.CFrame.x
			local f = char.HumanoidRootPart.CFrame.y
			local g = char.HumanoidRootPart.CFrame.z
			febypass.CreatePart(CFrame.new(math.floor(e),math.floor(f),math.floor(g)) + Vector3.new(0,6,0),workspace)
			for i,v in game.Workspace:GetDescendants() do
				if v:IsA("BasePart") and v.CFrame.x == math.floor(e) and v.CFrame.z == math.floor(g) then
					--spawn(function()
					febypass.SetName(v,"Sky")
					febypass.AddMesh(v)
					--end)
					--spawn(function()
					febypass.SetMesh(v,"8006679977")
					febypass.SetTexture(v,id)
					--end)
					febypass.MeshResize(v,Vector3.new(830,830,830))
					febypass.SetLocked(v,true)
				end
			end
		end
		Sky("433517917")
	end)
	
	script.Parent.skybox2.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local function Sky(id)
			local char = game.Players.LocalPlayer.Character
			local e = char.HumanoidRootPart.CFrame.x
			local f = char.HumanoidRootPart.CFrame.y
			local g = char.HumanoidRootPart.CFrame.z
			febypass.CreatePart(CFrame.new(math.floor(e),math.floor(f),math.floor(g)) + Vector3.new(0,6,0),workspace)
			for i,v in game.Workspace:GetDescendants() do
				if v:IsA("BasePart") and v.CFrame.x == math.floor(e) and v.CFrame.z == math.floor(g) then
					--spawn(function()
					febypass.SetName(v,"Sky")
					febypass.AddMesh(v)
					--end)
					--spawn(function()
					febypass.SetMesh(v,"8006679977")
					febypass.SetTexture(v,id)
					--end)
					febypass.MeshResize(v,Vector3.new(50,50,50))
					febypass.SetLocked(v,true)
				end
			end
		end
		Sky("12483457696")
	end)
	
	script.Parent.penicer.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local function Penis(player)
			local char = player.Character
			for i,v in char:GetChildren() do
				pcall(function()
					febypass.SetLocked(v,false)
				end)
			end
			if player.Character:FindFirstChild("Penis") then
				return
			else
	
	
				febypass.SetAnchor(true,player.Character.HumanoidRootPart)
				spawn(function()
					febypass.CreatePart(player.Character:WaitForChild("Right Leg").CFrame * CFrame.new(-0.8,1,-0.6),player.Character)
					febypass.SetName(player.Character.Part,"Balls1")
					febypass.CreatePart(player.Character:WaitForChild("Left Leg").CFrame * CFrame.new(0.8,1,-0.6),player.Character)
					febypass.SetName(player.Character.Part,"Balls2")
				end)
				wait(0.2)
				repeat wait() until char:FindFirstChild("Balls2")
				print("done")
				spawn(function()
					febypass.CreatePart(player.Character:WaitForChild("Torso").CFrame * CFrame.new(0,-1,-1.3),player.Character)
					febypass.SetName(player.Character.Part,"Penis")
					febypass.CreatePart(player.Character:WaitForChild("Torso").CFrame * CFrame.new(0,-1,-2.5),player.Character)
					febypass.SetName(player.Character.Part,"Head1")
				end)
				repeat wait() until char:FindFirstChild("Head1")
				spawn(function()
					febypass.AddMesh(char.Balls1)
					febypass.AddMesh(char.Balls2)
					febypass.AddMesh(char.Head1)
					febypass.AddMesh(char.Penis)
				end)
				repeat wait() until char.Penis:FindFirstChild("Mesh")
				spawn(function()
					febypass.SetMesh(char.Penis,"4743972117")
					febypass.SetMesh(char.Head1,"4743972117")
					febypass.MeshResize(char.Penis,Vector3.new(0.5,0.5,3))
					febypass.MeshResize(char.Head1,Vector3.new(0.5,0.5,1))
				end)
				spawn(function()
					febypass.Weld(char.Penis,char.HumanoidRootPart,char.Penis)
					febypass.SetMesh(char.Balls1,"5697933202")
					febypass.SetMesh(char.Balls2,"5697933202")
					febypass.MeshResize(char.Balls1,Vector3.new(0.2,0.2,0.2))
					febypass.MeshResize(char.Balls2,Vector3.new(0.2,0.2,0.2))
				end)
				wait(0.2)
				pcall(function()
					febypass.Color(char.Balls1,char:WaitForChild("Torso").Color)
					febypass.Color(char.Balls2,char:WaitForChild("Torso").Color)
					febypass.Color(char.Penis,char:WaitForChild("Torso").Color)
					febypass.Color(char.Head1, Color3.fromRGB(255,100,100))
				end)
				wait(0.2)
				spawn(function()
					febypass.SetCollision(player.Character.Balls1,false)
					febypass.SetCollision(player.Character.Balls2,false)
					febypass.SetCollision(player.Character.Penis,false)
					febypass.SetCollision(player.Character.Head1,false)
				end)
				wait(0.2)
				spawn(function()
					febypass.Weld(char.Balls1,char.HumanoidRootPart,char.Balls1)
					febypass.Weld(char.Balls2,char.Balls1,char.Balls2)
					febypass.Weld(char.Head1,char.Penis,char.Head1)
				end)
				wait(0.2)
				spawn(function()
					febypass.SetAnchor(false,char.Balls1)
					febypass.SetAnchor(false,char.Balls2)
					febypass.SetAnchor(false,char.Penis)
					febypass.SetAnchor(false,char.Head1)
					febypass.SetAnchor(false,char.HumanoidRootPart)
				end)
				repeat wait()
					febypass.SetAnchor(false,char.HumanoidRootPart)
					febypass.SetAnchor(false,char.Balls1)
					febypass.SetAnchor(false,char.Balls2)
					febypass.SetAnchor(false,char.Penis)
					febypass.SetAnchor(false,char.Head1)
				until char.Head1.Anchored == false
			end
		end
		Penis(game.Players.LocalPlayer)
	end)
	
	script.Parent.fireparts.MouseButton1Click:Connect(function()
		local febypass = loader.load_febypass()
		local function AddFire(part)
			local args = {
				[1] = "CreateDecorations",
				[2] = {
					[1] = {
						["Part"] = part,
						["DecorationType"] = "Fire"
					}
				}
			}
			febypass.remoteExecute(args)
		end
		local function FireParts()
			for i,v in game.Workspace:GetDescendants() do
				spawn(function()
					febypass.SetLocked(v,false)
					AddFire(v)
				end)
			end
		end
		FireParts()
	end)
end
coroutine.wrap(BLRBG_fake_script)()
local function KMAYUAF_fake_script() -- lol2.MainExecutor 
	local script = Instance.new('LocalScript', lol2)
	local req = require
	local require = function(obj)
		local fake = fake_module_scripts[obj]
		if fake then
			return fake()
		end
		return req(obj)
	end

	script.Parent.execute.MouseButton1Click:Connect(function()
		local scripted = script.Parent.TextBox.Text
		assert(loadstring(scripted))()
	end)
end
coroutine.wrap(KMAYUAF_fake_script)()
