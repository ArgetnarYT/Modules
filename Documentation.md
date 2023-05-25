# Modules for Lua scripts in Roblox
## Using
To use this module library, you need to add this line at the beginning of your code:
```lua
local ArgetnarLib = loadstring(game:HttpGet("https://argetnarhub.tk/raw/Modules.lua"))()
```
## Services
### We also have the right services for scripting:
```
Argetnar.Players -- Players service
Argetnar.Workspace -- Workspace service
Argetnar.ReplicatedStorage -- ReplicatedStorage service
Argetnar.Http -- Http service
Argetnar.Tween -- Tween service
Argetnar.CoreGui -- CoreGui service
Argetnar.Pathfinding -- Pathfinding service
Argetnar.RunService -- Run service
Argetnar.Teleport -- Teleport service
Argetnar.Network -- Network settings
Argetnar.UserInput -- UserInput service
```
### Example of using services:
```lua
local localPlayer = Players.LocalPlayer
local workspaceFolder = Workspace:FindFirstChild("MyFolder")
local replicatedStringValue = ReplicatedStorage:WaitForChild("MyStringValue")
local randomId = HttpService:GenerateGUID()
local tweenInfo = TweenInfo.new(1, Enum.EasingStyle.Quad)
local guiService = CoreGui:FindFirstChild("MyGuiService")
local pathfinder = PathfindingService:CreatePathfinder(workspaceFolder)
local isRunning = RunService:IsRunning()
local teleportSuccess = TeleportService:Teleport(1234567, localPlayer)
local networkSettings = NetworkSettings:GetSettings("Default")
local isKeyDown = UserInputService:IsKeyDown(Enum.KeyCode.Space)
```
## Basic
- Teleport `tp(x,y,z)`
- Fly on `Fly(true)`
- Fly off `Fly(false)`
- Speed `Speed(v)`
- Gravity `Gravity(v)`
- Kick `Kick(reason)`
- BTools `BTools()`
- Noclip `noclip()`
- Clip `clip()`
- AntiAfk `AntiAfk()`
- ESP on `Esp(true)`
- ESP off `Esp(false)`


### We will be making more features soon
