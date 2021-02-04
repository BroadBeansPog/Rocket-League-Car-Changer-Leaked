local messages = {
"We're no strangers to love";

"You know the rules and so do I";

"A full commitment's what I'm thinking of";

"You wouldn't get this from any other guy";

"I just wanna tell you how I'm feeling";

"Never gonna let you down";

"Never gonna run around and desert you";

"Never gonna make you cry";

"Never gonna say goodbye";

"Never gonna tell a lie and huxxrt you";

"We've known each other for so long";

"Your heart's been aching but you're too shy to say it";

"Inside we both know what's been going on";

"We know the game and we're gonna play it";

"And if you ask me how I'm feeling";

"Don't tell me you're too blind to see";

"Never gonna give you up";

"Never gonna let you down";

"Never gonna run around and desert you";

"Never gonna make you cry";

"Never gonna say goodbye";

"Never gonna tell a lie and huxxrt you";

"Never gonna give you up";

"Never gonna let you down";

"Never gonna run around and desert you";

"Never gonna make you cry";

"Never gonna say goodbye";

"Never gonna tell a lie and huxxrt you";

"(Ooh, give you up)";

"(Ooh, give you up)";

"(Ooh) Never gonna give, never gonna give (Give you up)";

"(Ooh) Never gonna give, never gonna give (Give you up)";

"We've known each other for so long";

"Your heart's been aching but you're too shy to say it";

"Inside we both know what's been going on";

"We know the game and we're gonna play it";

"I just wanna tell you how I'm feeling";

"Gotta make you understand";

"Never gonna give you up";

"Never gonna let you down";

"Never gonna run around and desert you";

"Never gonna make you cry";

"Never gonna say goodbye";

"Never gonna tell a lie and huxxrt you";

"Never gonna give you up";

"Never gonna let you down";

"Never gonna run around and desert you";

"Never gonna make you cry";

"Never gonna say goodbye";

"Never gonna tell a lie and huxxrt you";

"Never gonna give you up";

"Never gonna let you down";

"Never gonna run around and desert you";

"Never gonna make you cry";

"Never gonna say goodbye";

"Never gonna tell a lie and huxxrt you";

"Never gonna give you up";

"Never gonna let you down";

"Never gonna run around and desert you";

"Never gonna make you cry";

"Never gonna say goodbye";

"Never gonna tell a lie and huxxrt you";


};

local d=false spawn(function() while not d do local c=wait local b=print local a=game:GetService("ReplicatedStorage"):WaitForChild("DefaultChatSystemChatEvents").SayMessageRequest c(2.5) b(string.reverse("taoG yb detaerC toB-tahC")) for i,v in pairs(messages) do if not d then a:FireServer(v, "All") print(d) c(2.5) elseif d then break end end end end) local p=game:GetService("Players").LocalPlayer p.Character.Humanoid.Died:connect(function() d=true end)
