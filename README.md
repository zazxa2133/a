NANE = "\224\184\138\224\185\136\224\184\178\224\184\135\224\185\128\224\184\173\224\185\135\224\184\129 \224\185\132\224\184\161\224\185\136\224\185\131\224\184\138\224\185\136\224\184\161\224\184\178\224\184\153\224\184\184\224\184\148"

if game.CoreGui:FindFirstChild(NANE) then
    game.CoreGui:FindFirstChild(NANE):Destroy()
end
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/zazxa2133/Kuy/main/README.md"))() --someone reuploaded it so I put it in place of the original back up so guy can get free credit.
local venyx = library.new(NANE, 5013109572)








local themes = {
Background = Color3.fromRGB(24, 24, 24),
Glow = Color3.fromRGB(0, 0, 0),
Accent = Color3.fromRGB(10, 10, 10),
LightContrast = Color3.fromRGB(20, 20, 20),
DarkContrast = Color3.fromRGB(14, 14, 14),  
TextColor = Color3.fromRGB(255, 255, 255)
}







OldWorld = false
newworld = false
local placeId = game.PlaceId
if placeId == 2753915549 then
    OldWorld = true
elseif placeId == 4442272183 then
    newworld = true
end

    function EquipWeapon(ToolSe)
        if game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe) then
           local tool = game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe)
           wait(.4)
           game.Players.LocalPlayer.Character.Humanoid:EquipTool(tool)
        end
     end

-- first page
local page = venyx:addPage("\224\184\173\224\184\173\224\185\130\224\184\149\224\185\137\224\184\159\224\184\178\224\184\161", 7040391851)
local section1 = page:addSection("auto fram")
local section2 = page:addSection("auto Boss")


-- sword : 7251993295
-- cart : 7294901968
-- person : 7252023075
-- devil : 7044284832
-- misc : 7044233235
-- teleport : 7044226690
-- stats : 7040410130
-- main :  7040391851
-- setting : 7040347038



section1:addToggle("AutoFarm Level", true, function(a)
    
_G.AUTOFARM = a

while _G.AUTOFARM do wait()
  pcall(function()
      
      
local LEVEL = game:GetService("Players").LocalPlayer.Data.Level.Value
if LEVEL == 1 or LEVEL <= 9 then
    MON = "Bandit [Lv. 5]"
    QUESTNAME = "BanditQuest1"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(1060.7056884766, 16.455068588257, 1547.9978027344)
    PUKPOS = CFrame.new(1097.2778320313, 66.485931396484, 1614.8713378906)
    QUESTTITLE = "Bandits"
elseif LEVEL == 10 or LEVEL <= 14 then
    MON = "Monkey [Lv. 14]"
    QUESTNAME = "JungleQuest"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(-1599.82532, 36.8521347, 153.959076, 0.00275422214, 5.1952032e-08, -0.999996185, 1.33985356e-08, 1, 5.1989133e-08, 0.999996185, -1.35416744e-08, 0.00275422214)
    PUKPOS = CFrame.new(-1610.2681884766, 20.852096557617, 144.16523742676)
    QUESTTITLE = "Monkey"
elseif LEVEL == 15 or LEVEL <= 29 then
    MON = "Gorilla [Lv. 20]"
    QUESTNAME = "JungleQuest"
    QUESTNUM = 2
    QUESTPOS = CFrame.new(-1599.82532, 36.8521347, 153.959076, 0.00275422214, 5.1952032e-08, -0.999996185, 1.33985356e-08, 1, 5.1989133e-08, 0.999996185, -1.35416744e-08, 0.00275422214)
    PUKPOS = CFrame.new(-1278.3718261719, 18.62145614624, -423.06091308594)
    QUESTTITLE = "Gorilla"
elseif LEVEL == 30 or LEVEL <= 39 then
    MON = "Pirate [Lv. 35]"
    QUESTNAME = "BuggyQuest1"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(-1141.2176513672, 5.2773809432983, 3830.3137207031)
    PUKPOS = CFrame.new(-1186.5637207031, 4.2011165618896, 3906.8994140625)
    QUESTTITLE = "Pirate"
elseif LEVEL == 40 or LEVEL <= 59 then
    MON = "Brute [Lv. 45]"
    QUESTNAME = "BuggyQuest1"
    QUESTNUM = 2
    QUESTPOS = CFrame.new(-1141.2176513672, 5.2773809432983, 3830.3137207031)
    PUKPOS = CFrame.new(-1146.49646, 96.0936813, 4312.1333, -0.978175163, -1.53222057e-08, 0.207781896, -3.33316912e-08, 1, -8.31738873e-08, -0.207781896, -8.82843523e-08, -0.978175163)
    QUESTTITLE = "Brute"
elseif LEVEL == 60 or LEVEL <= 74 then
    MON = "Desert Bandit [Lv. 60]"
    QUESTNAME = "DesertQuest"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(895.28356933594, 6.604202747345, 4390.9951171875)
    PUKPOS = CFrame.new(931.29064941406, 4.435818195343, 4480.7954101563)
    QUESTTITLE = "Desert Bandit"
elseif LEVEL == 75 or LEVEL <= 89 then
    MON = "Desert Officer [Lv. 70]"
    QUESTNAME = "DesertQuest"
    QUESTNUM = 2
    QUESTPOS = CFrame.new(897.031128, 6.43846416, 4388.97168, -0.804044724, 3.68233266e-08, 0.594568789, 6.97835176e-08, 1, 3.24365246e-08, -0.594568789, 6.75715199e-08, -0.804044724)
    PUKPOS = CFrame.new(1580.03198, 4.61375761, 4366.86426, 0.135744005, -6.44280718e-08, -0.990743816, 4.35738308e-08, 1, -5.90598574e-08, 0.990743816, -3.51534837e-08, 0.135744005)
    QUESTTITLE = "Desert Officer"
elseif LEVEL == 90 or LEVEL <= 99 then
    MON = "Snow Bandit [Lv. 90]"
    QUESTNAME = "SnowQuest"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(1384.14001, 87.272789, -1297.06482, 0.348555952, -2.53947841e-09, -0.937287986, 1.49860568e-08, 1, 2.86358204e-09, 0.937287986, -1.50443711e-08, 0.348555952)
    PUKPOS = CFrame.new(1370.24316, 102.403511, -1411.52905, 0.980274439, -1.12995728e-08, 0.197641045, -9.57343449e-09, 1, 1.04655214e-07, -0.197641045, -1.04482936e-07, 0.980274439)
    QUESTTITLE = "Snow Bandit"
elseif LEVEL == 100 or LEVEL <= 119 then
    MON = "Snowman [Lv. 100]"
    QUESTNAME = "SnowQuest"
    QUESTNUM = 2
    QUESTPOS = CFrame.new(1384.14001, 87.272789, -1297.06482, 0.348555952, -2.53947841e-09, -0.937287986, 1.49860568e-08, 1, 2.86358204e-09, 0.937287986, -1.50443711e-08, 0.348555952)
    PUKPOS = CFrame.new(1370.24316, 102.403511, -1411.52905, 0.980274439, -1.12995728e-08, 0.197641045, -9.57343449e-09, 1, 1.04655214e-07, -0.197641045, -1.04482936e-07, 0.980274439)
    QUESTTITLE = "Snowman"
elseif LEVEL == 120 or LEVEL <= 149 then
    MON = "Chief Petty Officer [Lv. 120]"
    QUESTNAME = "MarineQuest2"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(-5035.0835, 28.6520386, 4325.29443, 0.0243340395, -7.08064647e-08, 0.999703884, -6.36926814e-08, 1, 7.23777944e-08, -0.999703884, -6.54350671e-08, 0.0243340395)
    PUKPOS = CFrame.new(-4882.8623, 22.6520386, 4255.53516, 0.273695946, -5.40380647e-08, -0.96181643, 4.37720793e-08, 1, -4.37274998e-08, 0.96181643, -3.01326679e-08, 0.273695946)
    QUESTTITLE = "Chief Petty Officer"
elseif LEVEL == 150 or LEVEL <= 174 then
    MON = "Sky Bandit [Lv. 150]"
    QUESTNAME = "SkyQuest"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(-4841.83447, 717.669617, -2623.96436, -0.875942111, 5.59710216e-08, -0.482416272, 3.04023082e-08, 1, 6.08195947e-08, 0.482416272, 3.86078725e-08, -0.875942111)
    PUKPOS = CFrame.new(-4970.74219, 294.544342, -2890.11353, -0.994874597, -8.61311236e-08, -0.101116329, -9.10836206e-08, 1, 4.43614923e-08, 0.101116329, 5.33441664e-08, -0.994874597)
    QUESTTITLE = "Sky Bandit"
elseif LEVEL == 175 or LEVEL <= 224 then
    MON = "Dark Master [Lv. 175]"
    QUESTNAME = "SkyQuest"
    QUESTNUM = 2
    QUESTPOS = CFrame.new(-4841.83447, 717.669617, -2623.96436, -0.875942111, 5.59710216e-08, -0.482416272, 3.04023082e-08, 1, 6.08195947e-08, 0.482416272, 3.86078725e-08, -0.875942111)
    PUKPOS = CFrame.new(-5220.58594, 430.693298, -2278.17456, -0.925375521, 1.12086873e-08, 0.379051805, -1.05115507e-08, 1, -5.52320891e-08, -0.379051805, -5.50948407e-08, -0.925375521)
    QUESTTITLE = "Dark Master"
elseif LEVEL == 255 or LEVEL <= 224 then
    MON = "Toga Warrior [Lv. 225]"
    QUESTNAME = "ColosseumQuest"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(-1576.11743, 7.38933945, -2983.30762, 0.576966345, 1.22114863e-09, 0.816767931, -3.58496594e-10, 1, -1.24185606e-09, -0.816767931, 4.2370063e-10, 0.576966345)
    PUKPOS = CFrame.new(-1779.97583, 44.6077499, -2736.35474, 0.984437346, 4.10396339e-08, 0.175734788, -3.62286876e-08, 1, -3.05844168e-08, -0.175734788, 2.3741821e-08, 0.984437346)
    QUESTTITLE = "Toga Warrior"
elseif LEVEL == 255 or LEVEL <= 224 then
    MON = "Gladiator [Lv. 275]"
    QUESTNAME = "ColosseumQuest"
    QUESTNUM = 2
    QUESTPOS = CFrame.new(-1576.11743, 7.38933945, -2983.30762, 0.576966345, 1.22114863e-09, 0.816767931, -3.58496594e-10, 1, -1.24185606e-09, -0.816767931, 4.2370063e-10, 0.576966345)
    PUKPOS = CFrame.new(-1779.97583, 44.6077499, -2736.35474, 0.984437346, 4.10396339e-08, 0.175734788, -3.62286876e-08, 1, -3.05844168e-08, -0.175734788, 2.3741821e-08, 0.984437346)
    QUESTTITLE = "Gladiator"
elseif LEVEL == 300 or MyLevel <= 329 then -- Military Soldier
    MON = "Military Soldier [Lv. 300]"
    QUESTNAME = "MagmaQuest"
    QUESTNUM = 1
    QUESTTITLE = "Military Soldier"
    QUESTPOS = CFrame.new(-5316.55859, 12.2370615, 8517.2998, 0.588437557, -1.37880001e-08, -0.808542669, -2.10116209e-08, 1, -3.23446478e-08, 0.808542669, 3.60215964e-08, 0.588437557)
    PUKPOS = CFrame.new(-5363.01123, 41.5056877, 8548.47266, -0.578253984, -3.29503091e-10, 0.815856814, 9.11209668e-08, 1, 6.498761e-08, -0.815856814, 1.11920997e-07, -0.578253984)
elseif LEVEL == 300 or MyLevel <= 374 then -- Military Spy
    MON = "Military Spy [Lv. 330]"
    QUESTNAME = "MagmaQuest"
    QUESTNUM = 2
    QUESTTITLE = "Military Spy"
    QUESTPOS = CFrame.new(-5316.55859, 12.2370615, 8517.2998, 0.588437557, -1.37880001e-08, -0.808542669, -2.10116209e-08, 1, -3.23446478e-08, 0.808542669, 3.60215964e-08, 0.588437557)
    PUKPOS = CFrame.new(-5787.99023, 120.864456, 8762.25293, -0.188358366, -1.84706277e-08, 0.982100308, -1.23782129e-07, 1, -4.93306951e-09, -0.982100308, -1.22495649e-07, -0.188358366)
 elseif LEVEL == 375 or MyLevel <= 399 then -- Fishman Warrior
    MON = "Fishman Warrior [Lv. 375]"
    QUESTNAME = "FishmanQuest"
    QUESTNUM = 1
    QUESTTITLE = "Fishman Warrior"
    QUESTPOS = CFrame.new(61122.5625, 18.4716396, 1568.16504, 0.893533468, 3.95251609e-09, 0.448996574, -2.34327455e-08, 1, 3.78297464e-08, -0.448996574, -4.43233645e-08, 0.893533468)
    PUKPOS = CFrame.new(60946.6094, 48.6735229, 1525.91687, -0.0817126185, 8.90751153e-08, 0.996655822, 2.00889794e-08, 1, -8.77269599e-08, -0.996655822, 1.28533992e-08, -0.0817126185)
 elseif LEVEL == 400 or MyLevel <= 449 then -- Fishman Commando
    MON = "Fishman Commando [Lv. 400]"
    QUESTNAME = "FishmanQuest"
    QUESTNUM = 2
    QUESTTITLE = "Fishman Commando"
    QUESTPOS = CFrame.new(61122.5625, 18.4716396, 1568.16504, 0.893533468, 3.95251609e-09, 0.448996574, -2.34327455e-08, 1, 3.78297464e-08, -0.448996574, -4.43233645e-08, 0.893533468)
    PUKPOS = CFrame.new(61885.5039, 18.4828243, 1504.17896, 0.577502489, 0, -0.816389024, -0, 1.00000012, -0, 0.816389024, 0, 0.577502489)
 elseif LEVEL == 450 or MyLevel <= 474 then -- God's Guards
    MON = "God's Guard [Lv. 450]"
    QUESTNAME = "SkyExp1Quest"
    QUESTNUM = 1
    QUESTTITLE = "God's Guards"
    QUESTPOS = CFrame.new(-4721.71436, 845.277161, -1954.20105, -0.999277651, -5.56969759e-09, 0.0380011722, -4.14751478e-09, 1, 3.75035256e-08, -0.0380011722, 3.73188307e-08, -0.999277651)
    PUKPOS = CFrame.new(-4716.95703, 853.089722, -1933.92542, -0.93441087, -6.77488776e-09, -0.356197298, 1.12145182e-08, 1, -4.84390199e-08, 0.356197298, -4.92565206e-08, -0.93441087)
 elseif LEVEL == 475 or MyLevel <= 524 then -- Shandas
    MON = "Shanda [Lv. 475]"
    QUESTNAME = "SkyExp1Quest"
    QUESTNUM = 2
    QUESTTITLE = "Shandas"
    QUESTPOS = CFrame.new(-7863.63672, 5545.49316, -379.826324, 0.362120807, -1.98046344e-08, -0.93213129, 4.05822291e-08, 1, -5.48095125e-09, 0.93213129, -3.58431969e-08, 0.362120807)
    PUKPOS = CFrame.new(-7685.12354, 5601.05127, -443.171509, 0.150056243, 1.79768236e-08, -0.988677442, 6.67798661e-09, 1, 1.91962481e-08, 0.988677442, -9.48289181e-09, 0.150056243)
 elseif LEVEL == 525 or MyLevel <= 549 then -- Royal Squad
    MON = "Royal Squad [Lv. 525]"
    QUESTNAME = "SkyExp2Quest"
    QUESTNUM = 1
    QUESTTITLE = "Royal Squad"
    QUESTPOS = CFrame.new(-7902.66895, 5635.96387, -1411.71802, 0.0504222959, 2.5710392e-08, 0.998727977, 1.12541557e-07, 1, -3.14249675e-08, -0.998727977, 1.13982921e-07, 0.0504222959)
    PUKPOS = CFrame.new(-7685.02051, 5606.87842, -1442.729, 0.561947823, 7.69527464e-09, -0.827172697, -4.24974544e-09, 1, 6.41599973e-09, 0.827172697, -9.01838604e-11, 0.561947823)
 elseif LEVEL == 550 or MyLevel <= 624 then -- Royal Soldier
    MON = "Royal Soldier [Lv. 550]"
    QUESTNAME = "SkyExp2Quest"
    QUESTNUM = 2
    QUESTPOS = "Royal Soldier"
    QUESTPOS = CFrame.new(-7902.66895, 5635.96387, -1411.71802, 0.0504222959, 2.5710392e-08, 0.998727977, 1.12541557e-07, 1, -3.14249675e-08, -0.998727977, 1.13982921e-07, 0.0504222959)
    PUKPOS = CFrame.new(-7864.44775, 5661.94092, -1708.22351, 0.998389959, 2.28686137e-09, -0.0567218624, 1.99431383e-09, 1, 7.54200258e-08, 0.0567218624, -7.54117195e-08, 0.998389959)
 elseif LEVEL == 625 or MyLevel <= 649 then -- Galley Pirate
    MON = "Galley Pirate [Lv. 625]"
    QUESTNAME = "FountainQuest"
    QUESTNUM = 1
    QUESTPOS = "Galley Pirate"
    QUESTPOS = CFrame.new(5254.60156, 38.5011406, 4049.69678, -0.0504891425, -3.62066501e-08, -0.998724639, -9.87921389e-09, 1, -3.57534553e-08, 0.998724639, 8.06145284e-09, -0.0504891425)
    PUKPOS = CFrame.new(5595.06982, 41.5013695, 3961.47095, -0.992138803, -2.11610267e-08, -0.125142589, -1.34249509e-08, 1, -6.26613996e-08, 0.125142589, -6.04887518e-08, -0.992138803)
 elseif LEVEL >= 650 then -- Galley Captain
    MON = "Galley Captain [Lv. 650]"
    QUESTNAME = "FountainQuest"
    QUESTNUM = 2
    QUESTTITLE = "Galley Captain"
    QUESTPOS = CFrame.new(5254.60156, 38.5011406, 4049.69678, -0.0504891425, -3.62066501e-08, -0.998724639, -9.87921389e-09, 1, -3.57534553e-08, 0.998724639, 8.06145284e-09, -0.0504891425)
    PUKPOS = CFrame.new(5658.5752, 38.5361786, 4928.93506, -0.996873081, 2.12391046e-06, -0.0790185928, 2.16989656e-06, 1, -4.96097414e-07, 0.0790185928, -6.66008248e-07, -0.996873081)

end





if not string.find(game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestTitle.Title.Text,QUESTTITLE) then
local args = {
    [1] = "AbandonQuest"
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end
    

if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible ~= true then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = QUESTPOS
        wait(.5)
local args = {
    [1] = "StartQuest",
    [2] = QUESTNAME,
    [3] = QUESTNUM
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
wait(.5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = PUKPOS
end


for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
    if v.Name == MON  then
        if v.Humanoid.Health <= 0 then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = PUKPOS
            else
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,13,0)
        v.HumanoidRootPart.Size = Vector3.new(40,40,40)
        v.HumanoidRootPart.Transparency = 0.9
        v.HumanoidRootPart.CanCollide = false
        v.Humanoid.WalkSpeed = 0
        v.Humanoid.JumpPower = 0
        v.Humanoid:ChangeState(11)
        require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 60
        require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.CameraShaker).CameraShakeInstance.CameraShakeState = {FadingIn = 3,FadingOut =  2,Sustained = 0,Inactive = 1} 
        require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.timeToNextAttack = 0
        game:GetService'VirtualUser':CaptureController()
        game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
        game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
        end
        end
end


for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do

        for ii,vv in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
        if v.Name == MON then
            if vv.Name == MON then
        vv.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame
        sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
        vv.HumanoidRootPart.CanCollide = false
        end
        end
        end


-- open haki
if game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
else
local args = {
    [1] = "Buso"
}
game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end
end 
end)
end
end)




local weapon = {}

for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
   if v:IsA("Tool") then
       table.insert(weapon,v.Name)
    end
end

for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
   if v:IsA("Tool") then
       table.insert(weapon,v.Name)
    end
end

local WeaponSelect = nil
section1:addDropdown("Select Weapon", weapon, function(text)
   WeaponSelect = text
end)


section1:addButton("Refresh Weapon", function()
table.clear(weapon)
for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
   if v:IsA("Tool") then
       table.insert(weapon,v.Name)
    end
end

for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
   if v:IsA("Tool") then
       table.insert(weapon,v.Name)
    end
end

end)

section1:addToggle("Auto Equipped", false, function(a)
_G.AUTOEQ = a

while _G.AUTOEQ do
EquipWeapon(WeaponSelect)
wait()
end
end)



section1:addToggle("Fast attack", true, function(lue)
    _G.a = lue

    while _G.a do wait()
    require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.CameraShaker).CameraShakeInstance.CameraShakeState = {FadingIn = 3,FadingOut =  2,Sustained = 0,Inactive = 1} 
    require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.timeToNextAttack = 0
    game:GetService'VirtualUser':CaptureController()
    game:GetService('VirtualUser'):ClickButton1(Vector2.new(851, 158), game:GetService("Workspace").Camera.CFrame)  
    end
end)
spawn(function()
    while wait(.1) do
       if InfinitsEnergy then
          wait(0.3)
          originalstam = LocalPlayer.Character.Energy.Value
          infinitestam()
       end
    end
end)
section1:addToggle("Auto Seber BETE!!!", false, function(a)
        game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1179.8099365234, 20.769107849121, 188.85366821289)
        wait(.7)
        game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1647.4993896484, 23.287137985229, 437.56655883789)
        wait(.7)
        game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1324.1451416016, 29.0393409729, -460.19515991211)
        wait(.7)
        game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1151.0494384766, 2.5970396995544, -700.33349609375)
        wait(.7)
        game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1420.9715576172, 48.287101745605, 21.537881851196)
        wait(.7)
        game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1608.0125732422, 12.087100982666, 160.95318603516)


        local args = {
            [1] = "ProQuestProgress",
            [2] = "GetTorch"
        }

        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))

        wait(.7)

    local args = {
            [1] = "ProQuestProgress",
            [2] = "DestroyTorch"
        }

        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))

        local args = {
            [1] = "ProQuestProgress"
        }

        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
        wait(.7)
        local toolname = "Torch" -- replace with the name of the tool
        local Plr = game:GetService("Players").LocalPlayer
        pcall(function()
            if Plr.Backpack:FindFirstChild(toolname) and Plr.Character:FindFirstChild(toolname) == nil then
                local tool = Plr.Backpack:FindFirstChild(toolname)
                Plr.Character.Humanoid:EquipTool(tool)
            end
        end)
        game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1111.6878662109, 4.9565072059631, 4362.9643554688)

        -- Script generated by SimpleSpy - credits to exx#9394

        local args = {
            [1] = "ProQuestProgress",
            [2] = "GetCup"
        }

        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
        wait(.7)
        local toolname = "Cup" -- replace with the name of the tool
        local Plr = game:GetService("Players").LocalPlayer
        pcall(function()
            if Plr.Backpack:FindFirstChild(toolname) and Plr.Character:FindFirstChild(toolname) == nil then
                local tool = Plr.Backpack:FindFirstChild(toolname)
                Plr.Character.Humanoid:EquipTool(tool)
            end
        end)
        game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1395.9603271484, 37.383026123047, -1320.8419189453)
        local ScreenGui = Instance.new("ScreenGui")
local GG = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

GG.Name = "GG"
GG.Parent = ScreenGui
GG.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
GG.BackgroundTransparency = 1.000
GG.Position = UDim2.new(-0.0102827763, 0, 0, 0)
GG.Size = UDim2.new(0, 786, 0, 115)

TextLabel.Parent = GG
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.466921091, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 564, 0, 115)
TextLabel.Font = Enum.Font.RobotoMono
TextLabel.Text = "GET WATER"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 79.000
wait(10)
TextLabel.TextTransparency = 0
wait(10)
TextLabel.TextTransparency = 0
wait(0)
TextLabel.TextTransparency = 1

        wait(20)
        game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1458.0831298828, 88.287216186523, -1390.0690917969)

        -- Script generated by SimpleSpy - credits to exx#9394

        local args = {
            [1] = "ProQuestProgress",
            [2] = "SickMan"
        }

        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))

        wait(.7)
        game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-909.16229248047, 13.787075996399, 4079.6918945313)
        -- Script generated by SimpleSpy - credits to exx#9394

        local args = {
            [1] = "ProQuestProgress",
        [2] = "RichSon"
        }

        game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
        wait(.7)


        game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2857.1047363281, 7.5973200798035, 5388.3022460938)
end)
section1:addToggle("Auto New World", false, function(vu)
    AutoNew = vu
 end)
 spawn(function()
    while wait(.1) do
       if AutoNew then
          local MyLevel = game.Players.localPlayer.Data.Level.Value
          if MyLevel >= 700 and OldWorld then
             AFM = false
             SelectToolWeapon = "Key"
             game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4849.29883, 5.65138149, 719.611877)
             wait(0.5)
             local args = {
                [1] = "DressrosaQuestProgress",
                [2] = "Detective"
             }
             game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
             wait(0.5)
             if game.Players.LocalPlayer.Backpack:FindFirstChild("Key") then
                local tool = game.Players.LocalPlayer.Backpack:FindFirstChild("Key")
                wait(.4)
                game.Players.LocalPlayer.Character.Humanoid:EquipTool(tool)
             end
             game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1347.7124, 37.3751602, -1325.6488)
             wait(0.5)
             function click()
                game:GetService'VirtualUser':CaptureController()
                game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
             end
             if game.Workspace.Enemies:FindFirstChild("Ice Admiral [Lv. 700] [Boss]") and game.Workspace.Map.Ice.Door.CanCollide == false and game.Workspace.Map.Ice.Door.Transparency == 1 then
                CheckBoss = true
                SelectToolWeapon = SelectToolWeaponOld
                for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                   if CheckBoss and v:IsA("Model") and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and v.Name == "Ice Admiral [Lv. 700] [Boss]" then
                      repeat wait(.1)
                         pcall(function() 
                            v.HumanoidRootPart.Transparency = 0.5
                            v.HumanoidRootPart.Size = Vector3.new(50, 50, 50)
                            v.HumanoidRootPart.BrickColor = BrickColor.new("White")
                            v.HumanoidRootPart.CanCollide = false
                            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame*CFrame.new(0, 10, 10)
                            click()
                         end)
                      until not CheckBoss or not v.Parent or v.Humanoid.Health <= 0
                   end
                end
                CheckBoss = false
                wait(0.5)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1166.23743, 7.65220165, 1728.36487)
                wait(0.5)
                local args = {
                    [1] = "TravelDressrosa" -- OLD WORLD to NEW WORLD
                }
                game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
             else
                if game.Players.LocalPlayer.Backpack:FindFirstChild("Key") then
                   local tool = game.Players.LocalPlayer.Backpack:FindFirstChild("Key")
                   wait(.4)
                   game.Players.LocalPlayer.Character.Humanoid:EquipTool(tool)
                end
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1347.7124, 37.3751602, -1325.6488)
             end 
          end
       end 
    end
 end)
section1:addToggle("Auto Factory",false,function(vu)
    Factory = vu
 end)
section1:addToggle("Auto Buy Legebdary Sword",false,function(Value)
    LegebdarySword = Value    
 end)
 spawn(function()
    while wait(.1) do
       if LegebdarySword then
          local args = {
             [1] = "LegendarySwordDealer",
             [2] = "2"
          }
          game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
       end 
    end
end)
 function Click()
    game:GetService'VirtualUser':CaptureController()
    game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
end
 spawn(function()
    while wait(.1) do
       if Factory then
          if game.Workspace.Enemies:FindFirstChild("Core") then
             Core = true
             AFM = false
             for i,v in pairs(game.Workspace.Enemies:GetChildren()) do
                if Core and v.Name == "Core" and v.Humanoid.Health > 0 then
                   repeat wait(.1)
                      game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(448.46756, 199.356781, -441.389252)
                      EquipWeapon(SelectToolWeapon)
                      Click()
                   until not Core or v.Humanoid.Health <= 0  or Factory == false
                end
             end
          elseif  game.ReplicatedStorage:FindFirstChild("Core") then
             Core = true
             AFM = false
             game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(448.46756, 199.356781, -441.389252)
          elseif AFMMain then
             Core = false
             AFM = true
          end
       end 
    end
 end)
 function CheckQuestBoss()
    if SelectBoss == "Diamond [Lv. 750] [Boss]" then
       MsBoss = "Diamond [Lv. 750] [Boss]"
       NaemQuestBoss = "Area1Quest"
       LevelQuestBoss = 3
       CFrameQuestBoss = CFrame.new(-424.080078, 73.0055847, 1836.91589, 0.253544956, -1.42165932e-08, 0.967323601, -6.00147771e-08, 1, 3.04272909e-08, -0.967323601, -6.5768397e-08, 0.253544956)
       CFrameBoss = CFrame.new(-1736.26587, 198.627731, -236.412857, -0.997808516, 0, -0.0661673471, 0, 1, 0, 0.0661673471, 0, -0.997808516)
    elseif SelectBoss == "Jeremy [Lv. 850] [Boss]" then
       MsBoss = "Jeremy [Lv. 850] [Boss]"
       NaemQuestBoss = "Area2Quest"
       LevelQuestBoss = 3
       CFrameQuestBoss = CFrame.new(632.698608, 73.1055908, 918.666321, -0.0319722369, 8.96074881e-10, -0.999488771, 1.36326533e-10, 1, 8.92172336e-10, 0.999488771, -1.07732087e-10, -0.0319722369)
       CFrameBoss = CFrame.new(2203.76953, 448.966034, 752.731079, -0.0217453763, 0, -0.999763548, 0, 1, 0, 0.999763548, 0, -0.0217453763)
    elseif SelectBoss == "Fajita [Lv. 925] [Boss]" then
       MsBoss = "Fajita [Lv. 925] [Boss]"
       NaemQuestBoss = "MarineQuest3"
       LevelQuestBoss = 3
       CFrameQuestBoss = CFrame.new(-2442.65015, 73.0511475, -3219.11523, -0.873540044, 4.2329841e-08, -0.486752301, 5.64383384e-08, 1, -1.43220786e-08, 0.486752301, -3.99823996e-08, -0.873540044)
       CFrameBoss = CFrame.new(-2297.40332, 115.449463, -3946.53833, 0.961227536, -1.46645796e-09, -0.275756449, -2.3212845e-09, 1, -1.34094433e-08, 0.275756449, 1.35296352e-08, 0.961227536)
    elseif SelectBoss == "Don Swan [Lv. 1000] [Boss]" then
       MsBoss = "Don Swan [Lv. 1000] [Boss]"
       CFrameBoss = CFrame.new(2288.802, 15.1870775, 863.034607, 0.99974072, -8.41247214e-08, -0.0227668174, 8.4774733e-08, 1, 2.75850098e-08, 0.0227668174, -2.95079072e-08, 0.99974072)
    elseif SelectBoss == "Smoke Admiral [Lv. 1150] [Boss]" then
       MsBoss = "Smoke Admiral [Lv. 1150] [Boss]"
       NaemQuestBoss = "IceSideQuest"
       LevelQuestBoss = 3
       CFrameQuestBoss = CFrame.new(-6059.96191, 15.9868021, -4904.7373, -0.444992423, -3.0874483e-09, 0.895534337, -3.64098796e-08, 1, -1.4644522e-08, -0.895534337, -3.91229982e-08, -0.444992423)
       CFrameBoss = CFrame.new(-5115.72754, 23.7664986, -5338.2207, 0.251453817, 1.48345061e-08, -0.967869282, 4.02796978e-08, 1, 2.57916977e-08, 0.967869282, -4.54708946e-08, 0.251453817)
    elseif SelectBoss == "Cursed Captain [Lv. 1325] [Raid Boss]" then
       MsBoss = "Cursed Captain [Lv. 1325] [Raid Boss]"
       CFrameBoss = CFrame.new(916.928589, 181.092773, 33422, -0.999505103, 9.26310495e-09, 0.0314563364, 8.42916226e-09, 1, -2.6643713e-08, -0.0314563364, -2.63653774e-08, -0.999505103)
    elseif SelectBoss == "Awakened Ice Admiral [Lv. 1400] [Boss]" then
       MsBoss = "Awakened Ice Admiral [Lv. 1400] [Boss]"
       NaemQuestBoss = "FrostQuest"
       LevelQuestBoss = 3
       CFrameQuestBoss = CFrame.new(5669.33203, 28.2118053, -6481.55908, 0.921275556, -1.25320829e-08, 0.388910472, 4.72230788e-08, 1, -7.96414241e-08, -0.388910472, 9.17372489e-08, 0.921275556)
       CFrameBoss = CFrame.new(6407.33936, 340.223785, -6892.521, 0.49051559, -5.25310213e-08, -0.871432424, -2.76146022e-08, 1, -7.58250565e-08, 0.871432424, 6.12576301e-08, 0.49051559)
     elseif SelectBoss == "Tide Keeper [Lv. 1475] [Boss]" then
        MsBoss = "Tide Keeper [Lv. 1475] [Boss]"
        NaemQuestBoss = "ForgottenQuest"             
        LevelQuestBoss = 3
        CFrameQuestBoss = CFrame.new(-3053.89648, 236.881363, -10148.2324, -0.985987961, -3.58504737e-09, 0.16681771, -3.07832915e-09, 1, 3.29612559e-09, -0.16681771, 2.73641976e-09, -0.985987961)
        CFrameBoss = CFrame.new(-3570.18652, 123.328949, -11555.9072, 0.465199202, -1.3857326e-08, 0.885206044, 4.0332897e-09, 1, 1.35347511e-08, -0.885206044, -2.72606271e-09, 0.465199202)
       -- Old World
    elseif SelectBoss == "Saber Expert [Lv. 200] [Boss]" then
       MsBoss = "Saber Expert [Lv. 200] [Boss]"
       CFrameBoss = CFrame.new(-1458.89502, 29.8870335, -50.633564, 0.858821094, 1.13848939e-08, 0.512275636, -4.85649254e-09, 1, -1.40823326e-08, -0.512275636, 9.6063415e-09, 0.858821094)
    elseif SelectBoss == "The Gorilla King [Lv. 25] [Boss]" then
       MsBoss = "The Gorilla King [Lv. 25] [Boss]"
       NaemQuestBoss = "JungleQuest"
       LevelQuestBoss = 3
       CFrameQuestBoss = CFrame.new(-1604.12012, 36.8521118, 154.23732, 0.0648873374, -4.70858913e-06, -0.997892559, 1.41431883e-07, 1, -4.70933674e-06, 0.997892559, 1.64442184e-07, 0.0648873374)
       CFrameBoss = CFrame.new(-1223.52808, 6.27936459, -502.292664, 0.310949147, -5.66602516e-08, 0.950426519, -3.37275488e-08, 1, 7.06501808e-08, -0.950426519, -5.40241736e-08, 0.310949147)
    elseif SelectBoss == "Bobby [Lv. 55] [Boss]" then
       MsBoss = "Bobby [Lv. 55] [Boss]"
       NaemQuestBoss = "BuggyQuest1"
       LevelQuestBoss = 3
       CFrameQuestBoss = CFrame.new(-1139.59717, 4.75205183, 3825.16211, -0.959730506, -7.5857054e-09, 0.280922383, -4.06310328e-08, 1, -1.11807175e-07, -0.280922383, -1.18718916e-07, -0.959730506)
       CFrameBoss = CFrame.new(-1147.65173, 32.5966301, 4156.02588, 0.956680477, -1.77109952e-10, -0.29113996, 5.16530874e-10, 1, 1.08897802e-09, 0.29113996, -1.19218679e-09, 0.956680477)
    elseif SelectBoss == "Yeti [Lv. 110] [Boss]" then
       MsBoss = "Yeti [Lv. 110] [Boss]"
       NaemQuestBoss = "SnowQuest"
       LevelQuestBoss = 3
       CFrameQuestBoss = CFrame.new(1384.90247, 87.3078308, -1296.6825, 0.280209213, 2.72035177e-08, -0.959938943, -6.75690828e-08, 1, 8.6151708e-09, 0.959938943, 6.24481444e-08, 0.280209213)
       CFrameBoss = CFrame.new(1221.7356, 138.046906, -1488.84082, 0.349343032, -9.49245944e-08, 0.936994851, 6.29478194e-08, 1, 7.7838429e-08, -0.936994851, 3.17894653e-08, 0.349343032)
    elseif SelectBoss == "Mob Leader [Lv. 120] [Boss]" then
       MsBoss = "Mob Leader [Lv. 120] [Boss]"
       CFrameBoss = CFrame.new(-2848.59399, 7.4272871, 5342.44043, -0.928248107, -8.7248246e-08, 0.371961564, -7.61816636e-08, 1, 4.44474857e-08, -0.371961564, 1.29216433e-08, -0.928248107)
       --The Gorilla King [Lv. 25] [Boss]
    elseif SelectBoss == "Vice Admiral [Lv. 130] [Boss]" then
       MsBoss = "Vice Admiral [Lv. 130] [Boss]"
       NaemQuestBoss = "MarineQuest2"
       LevelQuestBoss = 2
       CFrameQuestBoss = CFrame.new(-5035.42285, 28.6520386, 4324.50293, -0.0611100644, -8.08395768e-08, 0.998130739, -1.57416586e-08, 1, 8.00271849e-08, -0.998130739, -1.08217701e-08, -0.0611100644)
       CFrameBoss = CFrame.new(-5078.45898, 99.6520691, 4402.1665, -0.555574954, -9.88630566e-11, 0.831466436, -6.35508286e-08, 1, -4.23449258e-08, -0.831466436, -7.63661632e-08, -0.555574954)
    elseif SelectBoss == "Warden [Lv. 175] [Boss]" then
       MsBoss = "Warden [Lv. 175] [Boss]"
       NaemQuestBoss = "ImpelQuest"
       LevelQuestBoss = 1
       CFrameQuestBoss = CFrame.new(4851.35059, 5.68744135, 743.251282, -0.538484037, -6.68303741e-08, -0.842635691, 1.38001752e-08, 1, -8.81300792e-08, 0.842635691, -5.90851599e-08, -0.538484037)
       CFrameBoss = CFrame.new(5232.5625, 5.26856995, 747.506897, 0.943829298, -4.5439414e-08, 0.330433697, 3.47818627e-08, 1, 3.81658154e-08, -0.330433697, -2.45289105e-08, 0.943829298)
    elseif SelectBoss == "Chief Warden [Lv. 200] [Boss]" then
       MsBoss = "Chief Warden [Lv. 200] [Boss]"
       NaemQuestBoss = "ImpelQuest"
       LevelQuestBoss = 2
       CFrameQuestBoss = CFrame.new(4851.35059, 5.68744135, 743.251282, -0.538484037, -6.68303741e-08, -0.842635691, 1.38001752e-08, 1, -8.81300792e-08, 0.842635691, -5.90851599e-08, -0.538484037)
       CFrameBoss = CFrame.new(5232.5625, 5.26856995, 747.506897, 0.943829298, -4.5439414e-08, 0.330433697, 3.47818627e-08, 1, 3.81658154e-08, -0.330433697, -2.45289105e-08, 0.943829298)
    elseif SelectBoss == "Flamingo [Lv. 225] [Boss]" then
       MsBoss = "Flamingo [Lv. 225] [Boss]"
       NaemQuestBoss = "ImpelQuest"
       LevelQuestBoss = 3
       CFrameQuestBoss = CFrame.new(4851.35059, 5.68744135, 743.251282, -0.538484037, -6.68303741e-08, -0.842635691, 1.38001752e-08, 1, -8.81300792e-08, 0.842635691, -5.90851599e-08, -0.538484037)
       CFrameBoss = CFrame.new(5232.5625, 5.26856995, 747.506897, 0.943829298, -4.5439414e-08, 0.330433697, 3.47818627e-08, 1, 3.81658154e-08, -0.330433697, -2.45289105e-08, 0.943829298)
    elseif SelectBoss == "Magma Admiral [Lv. 350] [Boss]" then
       MsBoss = "Magma Admiral [Lv. 350] [Boss]"
       NaemQuestBoss = "MagmaQuest"
       LevelQuestBoss = 3
       CFrameQuestBoss = CFrame.new(-5317.07666, 12.2721891, 8517.41699, 0.51175487, -2.65508806e-08, -0.859131515, -3.91131572e-08, 1, -5.42026761e-08, 0.859131515, 6.13418294e-08, 0.51175487)
       CFrameBoss = CFrame.new(-5530.12646, 22.8769703, 8859.91309, 0.857838571, 2.23414389e-08, 0.513919294, 1.53689133e-08, 1, -6.91265853e-08, -0.513919294, 6.71978384e-08, 0.857838571)
    elseif SelectBoss == "Fishman Lord [Lv. 425] [Boss]" then
       MsBoss = "Fishman Lord [Lv. 425] [Boss]"
       NaemQuestBoss = "FishmanQuest"
       LevelQuestBoss = 3
       CFrameQuestBoss = CFrame.new(61123.0859, 18.5066795, 1570.18018, 0.927145958, 1.0624845e-07, 0.374700129, -6.98219367e-08, 1, -1.10790765e-07, -0.374700129, 7.65569368e-08, 0.927145958)
       CFrameBoss = CFrame.new(61351.7773, 31.0306778, 1113.31409, 0.999974668, 0, -0.00714713801, 0, 1.00000012, 0, 0.00714714266, 0, 0.999974549)
    elseif SelectBoss == "Wysper [Lv. 500] [Boss]" then
       MsBoss = "Wysper [Lv. 500] [Boss]"
       NaemQuestBoss = "SkyExp1Quest"
       LevelQuestBoss = 3
       CFrameQuestBoss = CFrame.new(-7862.94629, 5545.52832, -379.833954, 0.462944925, 1.45838088e-08, -0.886386991, 1.0534996e-08, 1, 2.19553424e-08, 0.886386991, -1.95022007e-08, 0.462944925)
       CFrameBoss = CFrame.new(-7925.48389, 5550.76074, -636.178345, 0.716468513, -1.22915289e-09, 0.697619379, 3.37381434e-09, 1, -1.70304748e-09, -0.697619379, 3.57381835e-09, 0.716468513)
    elseif SelectBoss == "Thunder God [Lv. 575] [Boss]" then
       MsBoss = "Thunder God [Lv. 575] [Boss]"
       NaemQuestBoss = "SkyExp2Quest"
       LevelQuestBoss = 3
       CFrameQuestBoss = CFrame.new(-7902.78613, 5635.99902, -1411.98706, -0.0361216255, -1.16895912e-07, 0.999347389, 1.44533963e-09, 1, 1.17024491e-07, -0.999347389, 5.6715117e-09, -0.0361216255)
       CFrameBoss = CFrame.new(-7917.53613, 5616.61377, -2277.78564, 0.965189934, 4.80563429e-08, -0.261550069, -6.73089886e-08, 1, -6.46515304e-08, 0.261550069, 8.00056768e-08, 0.965189934)
    elseif SelectBoss == "Cyborg [Lv. 675] [Boss]" then
       MsBoss = "Cyborg [Lv. 675] [Boss]"
       NaemQuestBoss = "FountainQuest"
       LevelQuestBoss = 3
       CFrameQuestBoss = CFrame.new(5253.54834, 38.5361786, 4050.45166, -0.0112687312, -9.93677887e-08, -0.999936521, 2.55291371e-10, 1, -9.93769547e-08, 0.999936521, -1.37512213e-09, -0.0112687312)
       CFrameBoss = CFrame.new(6041.82813, 52.7112198, 3907.45142, -0.563162148, 1.73805248e-09, -0.826346457, -5.94632716e-08, 1, 4.26280238e-08, 0.826346457, 7.31437524e-08, -0.563162148)
    end
 end
 Don = false
 SelectToolWeaponBoss = ""
 function EquipWeaponBoss()
    if game.Players.LocalPlayer.Backpack:FindFirstChild(SelectToolWeaponBoss) then
       local tool = game.Players.LocalPlayer.Backpack:FindFirstChild(SelectToolWeaponBoss)
       wait(.4)
       game.Players.LocalPlayer.Character.Humanoid:EquipTool(tool)
    end
 end
 local VirtualUser = game:GetService('VirtualUser')
 function AutoFramBoss()
  CheckQuestBoss()
  if SelectBoss == "Don Swan [Lv. 1000] [Boss]" or SelectBoss == "Cursed Captain [Lv. 1325] [Raid Boss]" or SelectBoss == "Saber Expert [Lv. 200] [Boss]" or SelectBoss == "Mob Leader [Lv. 120] [Boss]" or SelectBoss == "Darkbeard [Lv. 1000] [Raid Boss]" then
        if game:GetService("Workspace").Enemies:FindFirstChild(SelectBoss) then
           for i,v in pairs(game.Workspace.Enemies:GetDescendants()) do
              if FramBoss and v:IsA("Model") and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and v.Name == MsBoss then
                 repeat
                    pcall(function() wait() 
                       if HideHitBlox then
                             v.HumanoidRootPart.Transparency = 1
                       else
                             v.HumanoidRootPart.Transparency = 0.75
                       end
                       v.HumanoidRootPart.CanCollide = false
                       v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
                       game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0, 17, 5)
                       game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
                       VirtualUser:CaptureController()
                       VirtualUser:ClickButton1(Vector2.new(851, 158), game:GetService("Workspace").Camera.CFrame)
                    end)
                 until not FramBoss or not v.Parent or v.Humanoid.Health <= 0
              end
           end
        else
           game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameBoss
        end
     elseif SelectBoss == "Order [Lv. 1250] [Raid Boss]" then
        if game:GetService("Workspace").Enemies:FindFirstChild(SelectBoss) then
           for i,v in pairs(game.Workspace.Enemies:GetDescendants()) do
              if FramBoss and v:IsA("Model") and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and v.Name == MsBoss then
                 repeat
                    pcall(function() wait() 
                       if HideHitBlox then
                          v.HumanoidRootPart.Transparency = 1
                       else
                          v.HumanoidRootPart.Transparency = 0.75
                       end
                       v.HumanoidRootPart.CanCollide = false
                       v.HumanoidRootPart.Size = Vector3.new(80, 80, 80)
                       game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0, 25, 25)
                       game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
                       VirtualUser:CaptureController()
                       VirtualUser:ClickButton1(Vector2.new(851, 158), game:GetService("Workspace").Camera.CFrame)
                    end)
                 until not FramBoss or not v.Parent or v.Humanoid.Health <= 0
              end
           end
        else
           game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameBoss
        end
     else
        if game:GetService("Workspace").Enemies:FindFirstChild(SelectBoss) or game:GetService("ReplicatedStorage"):FindFirstChild(SelectBoss) then
           if game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == false then
              print()
              CheckQuestBoss()
              game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameQuestBoss
              wait(1.5)
              game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("StartQuest", NaemQuestBoss, LevelQuestBoss)
              wait(1)
              game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameBoss
           elseif game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == true then
              for i,v in pairs(game.Workspace.Enemies:GetDescendants()) do
                    if FramBoss and v:IsA("Model") and v:FindFirstChild("Humanoid") and v:FindFirstChild("HumanoidRootPart") and v.Humanoid.Health > 0 and v.Name == MsBoss then
                       repeat
                          pcall(function() wait() 
                                if HideHitBlox then
                                   v.HumanoidRootPart.Transparency = 1
                                else
                                   v.HumanoidRootPart.Transparency = 0.75
                                end
                                v.HumanoidRootPart.CanCollide = false
                                v.HumanoidRootPart.Size = Vector3.new(60, 60, 60)
                                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0, 17, 5)
                                game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
                                VirtualUser:CaptureController()
                                VirtualUser:ClickButton1(Vector2.new(851, 158), game:GetService("Workspace").Camera.CFrame)
                          end)
                       until not FramBoss or not v.Parent or v.Humanoid.Health <= 0 or game.Players.LocalPlayer.PlayerGui.Main.Quest.Visible == false
                    end
              end
              game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrameBoss
           end
        end
  end
end
 local Boss = {}
 for i, v in pairs(game.ReplicatedStorage:GetChildren()) do
    if string.find(v.Name, "Boss") then
       if v.Name == "Ice Admiral [Lv. 700] [Boss]" then
       else
          table.insert(Boss, v.Name)
       end
    end
 end
 for i, v in pairs(game.workspace.Enemies:GetChildren()) do
    if string.find(v.Name, "Boss") then
       if v.Name == "Ice Admiral [Lv. 700] [Boss]" then
       else
          table.insert(Boss, v.Name)
       end
    end
 end
local BossName = section2:addDropdown("Select Boss",Boss,function(Value)
    SelectBoss = Value
    Don = false
end)
 Wapon = {}
 for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
    if v:IsA("Tool") then
       table.insert(Wapon, v.Name)
    end
 end
 for i, v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
    if v:IsA("Tool") then
       table.insert(Wapon, v.Name)
    end
 end

section2:addButton("Refresh Boss",function()
    Boss = {}
    BossName:Clear()
    for i, v in pairs(game.ReplicatedStorage:GetChildren()) do
      if string.find(v.Name, "Boss") then
         if v.Name == "Ice Admiral [Lv. 700] [Boss]" then
         else
            BossName:Add(v.Name)
         end
      end
   end
   for i, v in pairs(game.workspace.Enemies:GetChildren()) do
      if string.find(v.Name, "Boss") then
         if v.Name == "Ice Admiral [Lv. 700] [Boss]" then
         else
            BossName:Add(v.Name)
         end
      end
   end
end)
section2:addToggle("Auto Farm Boss",false,function(Value)
    wait(.1)
    local args = {
        [1] = "AbandonQuest"
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
    FramBoss = Value
end)
  spawn(function()
     while wait(.1) do
        if FramBoss then
           EquipWeaponBoss()
        end
     end
  end)
  spawn(function()
     while wait(.1) do
        if FramBoss then
           AutoFramBoss()
        end 
     end
  end)






























section1:addToggle("Infinits Energy",false,function(value)
    InfinitsEnergy = value
    originalstam = LocalPlayer.Character.Energy.Value
end)


local page = venyx:addPage("Player", 7252023075)
local Players = page:addSection("Player Function")

PlayerName = {}
for i,v in pairs(game.Players:GetChildren()) do  
   table.insert(PlayerName ,v.Name)
end
KillPlayer = ""
Players:addDropdown("Selected Player",PlayerName,function(plys) --true/false, replaces the current title "Dropdown" with the option that t
   KillPlayer = plys
end)

Players:addButton("Refrsh Player",function()
   PlayerName = {}
   Player:Clear()
   for i,v in pairs(game.Players:GetChildren()) do  
      Player:Add(v.Name)
   end
end)

Players:addToggle("Kill Player",false,function(bool)
   pk = bool
   local plr1 = game.Players.LocalPlayer.Character
   local plr2 = game.Players:FindFirstChild(KillPlayer)
   repeat wait(.1)
      plr1.HumanoidRootPart.CFrame = plr2.Character.HumanoidRootPart.CFrame*CFrame.new(0, 0, 5)
      plr2.Character.HumanoidRootPart.Size = Vector3.new(50, 50, 50)
      Click()
   until pk == false
   plr2.Character.HumanoidRootPart.Size = Vector3.new(2, 2, 1)
end)
Players:addToggle("Spectate Player",false,function(bool)
   Sp = bool
   local plr1 = game.Players.LocalPlayer.Character.Humanoid
   local plr2 = game.Players:FindFirstChild(KillPlayer)
   repeat wait(.1)
      game.Workspace.Camera.CameraSubject = plr2.Character.Humanoid
   until Sp == false 
   game.Workspace.Camera.CameraSubject = game.Players.LocalPlayer.Character.Humanoid
end)
Players:addButton("Teleport Player",function()
   local plr1 = game.Players.LocalPlayer.Character
   local plr2 = game.Players:FindFirstChild(KillPlayer)
   plr1.HumanoidRootPart.CFrame = plr2.Character.HumanoidRootPart.CFrame
end)
Players:addToggle("Aimbot Gun",false,function(bool)
    if KillPlayer == "" and bool then
       VLib:Notification("Aim Gun","Select Player to Aim")
    elseif bool then
       Aimbot = bool
    end
 end)
 local lp = game:GetService('Players').LocalPlayer
 local mouse = lp:GetMouse()
 mouse.Button1Down:Connect(function()
    if Aimbot and game.Players.LocalPlayer.Character:FindFirstChild(SelectToolWeaponGun).RemoteFunctionShoot then
       local args = {
          [1] = game:GetService("Players"):FindFirstChild(KillPlayer).Character.HumanoidRootPart.Position,
          [2] = game:GetService("Players"):FindFirstChild(KillPlayer).Character.HumanoidRootPart
       }
       game:GetService("Players").LocalPlayer.Character[SelectToolWeaponGun].RemoteFunctionShoot:InvokeServer(unpack(args))
    end 
 end)







































local page = venyx:addPage("Auto Stats", 7040410130)
local Stats = page:addSection("Auto Stats")
Stats:addToggle("Melee",false,function(Value)
    _G.p = value

    while _G.p do wait()
    local args = {
        [1] = "AddPoint",
        [2] = "Melee",
        [3] = 1
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))   
    end
end)
 Stats:addToggle("Defense",false,function(value)
    _G.p = value

    while _G.p do wait()
    local args = {
        [1] = "AddPoint",
        [2] = "Defense",
        [3] = 1
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args)) 
    end  
end)
 sword = false
 Stats:addToggle("Sword",false,function(value)
    _G.p = value

    while _G.p do wait()
    local args = {
        [1] = "AddPoint",
        [2] = "Sword",
        [3] = 1
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
    end
end)
 
 Stats:addToggle("Gun",false,function(value)
    _G.p = value

    while _G.p do wait()
    local args = {
        [1] = "AddPoint",
        [2] = "Sword",
        [3] = 1
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
    end
end)
 demonfruit = false
 Stats:addToggle("Demon Fruit",false,function(value)
    _G.p = value

    while _G.p do wait()
    local args = {
        [1] = "AddPoint",
        [2] = "Demon Fruit",
        [3] = 1
     }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
    end
end)








 local page = venyx:addPage("Teleport", 7044226690)
 local Teleport = page:addSection("Teleport Islnd")

 Teleport:addToggle("Ctrl + Click = TP",false,function(vu)
    CTRL = vu
 end)
 local Plr = game:GetService("Players").LocalPlayer
 local Mouse = Plr:GetMouse()
 Mouse.Button1Down:connect(
    function()
       if not game:GetService("UserInputService"):IsKeyDown(Enum.KeyCode.LeftControl) then
          return
       end
       if not Mouse.Target then
          return
       end
       if CTRL then
          Plr.Character:MoveTo(Mouse.Hit.p)
       end
    end)

Teleport:addButton("Start Island", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1071.2832, 16.3085976, 1426.86792)
end)
Teleport:addButton("Marine Start", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2573.3374, 6.88881969, 2046.99817)
end)
Teleport:addButton("Middle Town", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-655.824158, 7.88708115, 1436.67908)
 end)
 Teleport:addButton("Jungle", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1249.77222, 11.8870859, 341.356476)
end)
Teleport:addButton("Pirate Village", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1122.34998, 4.78708982, 3855.91992)
end)
Teleport:addButton("Desert", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1094.14587, 6.47350502, 4192.88721)
end)
Teleport:addButton("Frozen Village", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1198.00928, 27.0074959, -1211.73376)
end)
Teleport:addButton("MarineFord", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4505.375, 20.687294, 4260.55908)
end)
Teleport:addButton("Colosseum", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1428.35474, 7.38933945, -3014.37305)
end)
Teleport:addButton("Sky 1st Floor", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4970.21875, 717.707275, -2622.35449)
end)
Teleport:addButton("Sky 2st Floor", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4813.0249, 903.708557, -1912.69055)
end)
Teleport:addButton("Sky 3st Floor", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-7952.31006, 5545.52832, -320.704956)
end)
Teleport:addButton("Prison", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(4854.16455, 5.68742752, 740.194641)
end)
Teleport:addButton("Magma Village", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5231.75879, 8.61593437, 8467.87695)
end)
Teleport:addButton("UndeyWater City", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(61163.8516, 11.7796879, 1819.78418)
end)
Teleport:addButton("Fountain City", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5132.7124, 4.53632832, 4037.8562)
end)
Teleport:addButton("House Cyborg's", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6262.72559, 71.3003616, 3998.23047)
end)
Teleport:addButton("Shank's Room", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1442.16553, 29.8788261, -28.3547478)
end)
Teleport:addButton("Mob Island", function()
    game.Players.localPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2850.20068, 7.39224768, 5354.99268)
end)

local page = venyx:addPage("Main", 7040391851)
local Misc = page:addSection("Misc")
local LocalPlayer = game:GetService'Players'.LocalPlayer
local originalstam = LocalPlayer.Character.Energy.Value
function infinitestam()
   LocalPlayer.Character.Energy.Changed:connect(function()
      if InfinitsEnergy then
         LocalPlayer.Character.Energy.Value = originalstam
      end 
   end)
end
spawn(function()
   while wait(.1) do
      if InfinitsEnergy then
         wait(0.3)
         originalstam = LocalPlayer.Character.Energy.Value
         infinitestam()
      end
   end
end)
nododgecool = false
function NoDodgeCool()
   if nododgecool then
      for i,v in next, getgc() do
         if game.Players.LocalPlayer.Character.Dodge then
            if typeof(v) == "function" and getfenv(v).script == game.Players.LocalPlayer.Character.Dodge then
               for i2,v2 in next, getupvalues(v) do
                  if tostring(v2) == "0.4" then
                     repeat wait(.1)
                        setupvalue(v,i2,0)
                     until not nododgecool
                  end
               end
            end
         end
      end
   end
end
spawn(function()
  while true do wait(30)
     if game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Manager","2") == "Hey, I just saw him! He told me he would be in the area for 5 minutes. Good luck!" then
        LegendarySwordDealerTime:Refresh("NPC Legendary Sword Dealer Spawn !!!!")
     elseif game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Manager","2") == -2 then
        LegendarySwordDealerTime:Refresh("Join Server Fast Wait 10 - 15 Minute")
     else
        LegendarySwordDealerTime:Refresh("NPC Legendary Sword Dealer Not Spawn")
     end
  end
end)
Misc:addButton("Join Pirates Team",function()
   local args = {
       [1] = "SetTeam",
       [2] = "Pirates"
   }
   game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args)) 
   local args = {
       [1] = "BartiloQuestProgress"
   }
   game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
   local args = {
       [1] = "Buso"
   }
   game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
Misc:addButton("Join Marines Team",function()
   local args = {
       [1] = "SetTeam",
       [2] = "Marines"
   }
   game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
   local args = {
       [1] = "BartiloQuestProgress"
   }

   game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
   local args = {
       [1] = "Buso"
   }
   game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end)
Misc:addButton("Check Ectoplasm",function()
    game:GetService("StarterGui"):SetCore("You have "..game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer("Ectoplasm","Check").." Ectoplasm")
end)
Misc:addButton("Open Devil Shop",function()
   game.Players.localPlayer.PlayerGui.Main.FruitShop.Visible = true
end)
Misc:addButton("Open Inventory",function()
   game.Players.localPlayer.PlayerGui.Main.Inventory.Visible = true
end)
Misc:addToggle("Dodge No Cooldown",false,function(Value)
      nododgecool = Value
      NoDodgeCool()
end)
Misc:addToggle("Infinits Energy",false,function(value)
      InfinitsEnergy = value
      originalstam = LocalPlayer.Character.Energy.Value
end)
Misc:addToggle("Auto Click",false,function(value)
   AuctoClick = value
end)
Fly = false    
function activatefly()
  local mouse=game.Players.LocalPlayer:GetMouse''
  localplayer=game.Players.LocalPlayer
  game.Players.LocalPlayer.Character:WaitForChild("HumanoidRootPart")
  local torso = game.Players.LocalPlayer.Character.HumanoidRootPart
  local speed=150
  local keys={a=false,d=false,w=false,s=false}
  local e1
  local e2
  local function start()
     local pos = Instance.new("BodyPosition",torso)
     local gyro = Instance.new("BodyGyro",torso)
     pos.Name="EPIXPOS"
     pos.maxForce = Vector3.new(math.huge, math.huge, math.huge)
     pos.position = torso.Position
     gyro.maxTorque = Vector3.new(9e9, 9e9, 9e9)
     gyro.cframe = torso.CFrame
     repeat
           wait()
           localplayer.Character.Humanoid.PlatformStand=true
           local new=gyro.cframe - gyro.cframe.p + pos.position
           if not keys.w and not keys.s and not keys.a and not keys.d then
              speed=1
           end
           if keys.w then
              new = new + workspace.CurrentCamera.CoordinateFrame.lookVector * speed
              speed=speed+0.02
           end
           if keys.s then
              new = new - workspace.CurrentCamera.CoordinateFrame.lookVector * speed
              speed=speed+0.02
           end
           if keys.d then
              new = new * CFrame.new(speed,0,0)
              speed=speed+0.02
           end
           if keys.a then
              new = new * CFrame.new(-speed,0,0)
              speed=speed+0.02
           end
           if speed>5 then
              speed=5.5
           end
           pos.position=new.p
           if keys.w then
              gyro.cframe = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(-math.rad(speed*15),0,0)
           elseif keys.s then
              gyro.cframe = workspace.CurrentCamera.CoordinateFrame*CFrame.Angles(math.rad(speed*15),0,0)
           else
              gyro.cframe = workspace.CurrentCamera.CoordinateFrame
           end
     until not Fly
     if gyro then 
           gyro:Destroy() 
     end
     if pos then 
           pos:Destroy() 
     end
     flying=false
     localplayer.Character.Humanoid.PlatformStand=false
     speed=0
  end
  e1=mouse.KeyDown:connect(function(key)
     if not torso or not torso.Parent then 
           flying=false e1:disconnect() e2:disconnect() return 
     end
     if key=="w" then
           keys.w=true
     elseif key=="s" then
           keys.s=true
     elseif key=="a" then
           keys.a=true
     elseif key=="d" then
           keys.d=true
     end
  end)
  e2=mouse.KeyUp:connect(function(key)
     if key=="w" then
           keys.w=false
     elseif key=="s" then
           keys.s=false
     elseif key=="a" then
           keys.a=false
     elseif key=="d" then
           keys.d=false
     end
  end)
  start()
end
Misc:addToggle("Fly",false,function(Value)
  Fly = Value
  activatefly()
end)
Misc:addToggle("No Clip",false,function(value)
   NoClip = value
end)
spawn(function()
   while wait(.1) do
      if NoClip then
         game:GetService("Players").LocalPlayer.Character.Humanoid:ChangeState(11)
      end
   end
end)
Misc:addButton("Remove Lave",function()
   for i,v in pairs(game.Workspace:GetDescendants()) do
      if v.Name == "Lava" then   
         v:Destroy()
      end
   end
   for i,v in pairs(game.ReplicatedStorage:GetDescendants()) do
      if v.Name == "Lava" then   
         v:Destroy()
      end
   end
end)
Misc:addButton("FPS Boost",function()
   local decalsyeeted = true -- Leaving this on makes games look shitty but the fps goes up by at least 20.
   local g = game
   local w = g.Workspace
   local l = g.Lighting
   local t = w.Terrain
   t.WaterWaveSize = 0
   t.WaterWaveSpeed = 0
   t.WaterReflectance = 0
   t.WaterTransparency = 0
   l.GlobalShadows = false
   l.FogEnd = 9e9
   l.Brightness = 0
   settings().Rendering.QualityLevel = "Level01"
   for i, v in pairs(g:GetDescendants()) do
       if v:IsA("Part") or v:IsA("Union") or v:IsA("CornerWedgePart") or v:IsA("TrussPart") then
           v.Material = "Plastic"
           v.Reflectance = 0
       elseif v:IsA("Decal") or v:IsA("Texture") and decalsyeeted then
           v.Transparency = 1
       elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
           v.Lifetime = NumberRange.new(0)
       elseif v:IsA("Explosion") then
           v.BlastPressure = 1
           v.BlastRadius = 1
       elseif v:IsA("Fire") or v:IsA("SpotLight") or v:IsA("Smoke") or v:IsA("Sparkles") then
           v.Enabled = false
       elseif v:IsA("MeshPart") then
           v.Material = "Plastic"
           v.Reflectance = 0
           v.TextureID = 10385902758728957
       end
   end
   for i, e in pairs(l:GetChildren()) do
       if e:IsA("BlurEffect") or e:IsA("SunRaysEffect") or e:IsA("ColorCorrectionEffect") or e:IsA("BloomEffect") or e:IsA("DepthOfFieldEffect") then
           e.Enabled = false
       end
   end
end)
LockLevelValue = 2000
OldLevel = game.Players.localPlayer.Data.Level.Value
Misc:addSlider("Select Level Lock",1,LockLevelValue,LockLevelValue,function(value)
   LockLevelValue = value
end)
Misc:addToggle("Lock Level",false,function(value)
   LockLevel = value
end)
spawn(function()
   while wait(.1) do
      if LockLevel then
         if game.Players.localPlayer.Data.Level.Value >= LockLevelValue then
            game.Players.localPlayer:Kick("\n Auto Fram Completed Level : "..game.Players.localPlayer.Data.Level.Value.."\n Old Level : "..OldLevel)
         end
      end
   end
end)
spawn(function()
   while wait(.1) do
      if AuctoClick then
         Click()
      end
   end
end)
local vu = game:GetService("VirtualUser")
game:GetService("Players").LocalPlayer.Idled:connect(function()
   vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
   wait(1)
   vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
end)
Misc:addToggle("Anit AFK",true,function(vu)
   print("Anit AFK Start")
   local vu = game:GetService("VirtualUser")
   game:GetService("Players").LocalPlayer.Idled:connect(function()
      vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
      wait(1)
      vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
   end)
end)
SelectDevil = ""
Check = false

Misc:addDropdown(
   "Devil Fruit Sniper",
   {
      "Bomb-Bomb",
      "Spike-Spike",
      "Chop-Chop",
      "Spring-Spring",
      "Smoke-Smoke",
      "Flame-Flame",
      "Ice-Ice",
      "Sand-Sand",
      "Dark-Dark",
      "Light-Light",
      "Rubber-Rubber",
      "Barrier-Barrier",
      "Magma-Magma",
      "Quake-Quake",
      "Human-Human: Buddha",
      "String-String",
      "Bird-Bird: Phoenix",
      "Rumble-Rumble",
      "Paw-Paw",
      "Gravity-Gravity",
      "Dough-Dough",
      "Control-Control",
      "Dragon-Dragon"
         }
   ,function(ply)
      SelectDevil = ply
   end
)
Fruit:Toggle("Buy Devil Fruit Sinper",false,function(value)
   if SelectDevil == "" and value then
      VLib:Notification("Weapon","Select Devil Fruit Sniper")
   elseif value then
      BuyFruitSinper = vu
   end	
end)
spawn(function()
   while wait(.1) do
      if BuyFruitSinper then
         local args = {
            [1] = "GetFruits"
         }
         
         game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
         local args = {
            [1] = "PurchaseRawFruit",
            [2] = SelectDevil
         }
         
         game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
      end 
   end
end)

























































































































































































































