local ProximityPromt = script.Parent
local Door = script.Parent.Parent

ProximityPromt.Triggered:Connect(function()
	if ProximityPromt.ActionText == "Open" then
		Door.Transparency = 1
		Door.CanCollide = false
		ProximityPromt.ActionText = "Close"
	else
		Door.Transparency = 0
		Door.CanCollide = true
		ProximityPromt.ActionText = "Open"
	end
end)
