README (CharmiDEV)

Inside this folder, you will find two exports that you can use:

exports['charmi-hud']:IsSettingsLoaded() -- Checking HUD settings loaded or not
exports['charmi-hud']:IsCinematicMode() -- Checking Cinematic mode on or off


Inside this folder, events:
RegisterNetEvent('hud:client:UpdateHarness', function(harnessHp))
RegisterNetEvent('hud:client:UpdateNeeds', function(newHunger, newThirst))
RegisterNetEvent('hud:client:UpdateStress', function(newStress))
RegisterNetEvent('hud:client:UpdateNitrous', function(_, nitroLevel, bool))

The script offers the following functionalities:

Speedometer: Speedometer feature in vehicle
Satatushud: Status HUD (Player food, stress and more)
Compass: Compass feature
HUDsettings: HUD configuration settings
Saved settings: Previously saved settings
Cinema Mode: Cinema viewing mode
Other features: Additional options available through the HUD menu

We hope you enjoy using these script!

How to install?!?

Go to qb-smallresource/seatbelt.lua and but this under 84 line

---Checks whether you have the seatbelt on or not
---@return boolean 
local function hasSeatbelt()
    return seatbeltOn
end

exports("hasSeatbelt", hasSeatbelt)
