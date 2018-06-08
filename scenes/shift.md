# Config
 - Title: Who to ask to take an extra turn?
 - Image: https://flemmingfog.github.io/spike/woman.jpg
 - Next: outro

# Description
There is a flu going round, and you just received a message that Joan will not be coming in tomorrow morning. 

If you cannot find a replacement, the monthly targets are in risk of not being met, as the lack of the extra set of hands is likely to slow things down. 

But: You have already asked around, and no-one wants to take the shift. 

There is no way around it: You have to go back and ask one who have already turned you down the first time you asked. 

Who will you contact next?

# Choice
Lilly? When you her asked the first time, she answered that she had already taken on two extra shifts in the past 3 weeks, so she did not want to take another one! (but you have a sense that you could talk her into it…)

# Variables
 - Resources: -1
 - Engagement: -1
 - Output: +2
 - Total: round(((Engagement * Output) / 100) - (100 - Resources))

# Choice
Jonas? When you him asked the first time, he really wanted to help, but couldn't because he had promised to drive his son to the dentist tomorrowself

# Variables
 - Resources: -1
 - Engagement: -1
 - Output: +2
 - Total: round(((Engagement * Output) / 100) - (100 - Resources))

# Choice
No-one? Though it's likely to cost a slightly lower output tomorrow, this is what happens from time to time.

# Variables
 - Resources: +0
 - Engagement: +0
 - Output: -4
 - Total: round(((Engagement * Output) / 100) - (100 - Resources))

# Choice
Achmed? When you him asked the first time, he pointed out that its Friday tomorrow, and that he had planned to visit his mosque. 

# Variables
 - Resources: -1
 - Engagement: -2
 - Output: +2
 - Total: round(((Engagement * Output) / 100) - (100 - Resources))

