local key = _G.Key
local check = "https://pwoerfree.000webhostapp.com/check.php?key=" .. key
if game:HttpGet(check) == "Whitelisted" then
loadstring(game:HttpGet("https://pwoerfree.000webhostapp.com/script.lua"))()
else
game.Players.LocalPlayer:Kick("เธฃเธนเนเธงเนเธฒเน€เธเธฒเนเธกเนเธฃเธฑเธเธเนเนเธกเนเธ•เนเธญเธเน€เธชเธทเธญเธเนเธชเนเธเธตเธขเนเธกเธฑเนเธง")
end
