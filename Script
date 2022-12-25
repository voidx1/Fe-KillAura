<div align="center"> 
<p style="text-align: center;"></p><div class="separator" style="clear: both;"><div class="separator" style="clear: both; text-align: center;"><span style="font-size: x-large;"><div class="separator" style="clear: both; text-align: center;"><div class="separator" style="clear: both; text-align: center;"><a href="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEicRvJi9Q58Tp8b0sKdpqk2yLDSVnEZ2H_1umbC9pnL4WVQiUFQss06K33ijliOomLxe8p_zwS2BT36Pe0XWvVtQhFNiMjIPWn8oFHxoTo6SlH9xT6lMJzns2kDMP3RNuKKz-84AVNUdBZK7gMcIZZtubWKXF40Ry4VaCIgSglKAmp-1E6D9kbLpE5ogw/s850/%D8%B3%D9%83%D8%B1%D8%A8%D8%AA%20Dance.png" style="margin-left: 1em; margin-right: 1em;"><img border="0" data-original-height="500" data-original-width="850" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEicRvJi9Q58Tp8b0sKdpqk2yLDSVnEZ2H_1umbC9pnL4WVQiUFQss06K33ijliOomLxe8p_zwS2BT36Pe0XWvVtQhFNiMjIPWn8oFHxoTo6SlH9xT6lMJzns2kDMP3RNuKKz-84AVNUdBZK7gMcIZZtubWKXF40Ry4VaCIgSglKAmp-1E6D9kbLpE5ogw/s16000/%D8%B3%D9%83%D8%B1%D8%A8%D8%AA%20Dance.png" /></a></div><br /><div class="separator" style="clear: both; text-align: center;"><br /></div></div><div class="separator" style="clear: both; text-align: center;"><span style="font-size: x-large; text-align: right;">تجربة السكربت :</span></div><div class="separator" style="clear: both; text-align: center;"><span style="font-size: x-large; text-align: right;"><br /></span></div></span></div><div class="separator" style="clear: both; text-align: center;"><div style="clear: both; text-align: center;">[youtube url=https://www.youtube.com/watch?v=qUZ1jcHFDmc]</div><div style="clear: both; text-align: center;"><br /></div></div></div><h3><span style="font-size: large;">السكربت :</span></h3><div>
  
<code><pre>--// Setting \\--
local range = 15

--// Variable \\--
local player = game:GetService("Players").LocalPlayer

--// Script \\--
game:GetService("RunService").RenderStepped:Connect(function()
    local p = game.Players:GetPlayers()
    for i = 2, #p do local v = p[i].Character
        if v and v:FindFirstChild("Humanoid") and v.Humanoid.Health > 0 and v:FindFirstChild("HumanoidRootPart") and player:DistanceFromCharacter(v.HumanoidRootPart.Position) <= range then
            local tool = player.Character and player.Character:FindFirstChildOfClass("Tool")
            if tool and tool:FindFirstChild("Handle") then
                tool:Activate()
                for i,v in next, v:GetChildren() do
                    if v:IsA("BasePart") then
                        firetouchinterest(tool.Handle,v,0)
                        firetouchinterest(tool.Handle,v,1)
                    end
                end
            end
        end
    end
end)</code></pre>
