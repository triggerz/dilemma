# Config
 - Title: Who to ask to take an extra shift?

# Description
There is a flu going round, and you just received a message that Joan will not be coming in tomorrow morning. 

If you cannot find a replacement, the monthly production targets are in risk of not being met, as the lack of the extra set of hands is likely to slow down the production. 

But: You have already asked around, and no-one wants to take the shift. 

There is no way around it: You have to go back and ask one who have already turned you down the first time you asked. 

Who will you contact next?

# Choices
## You tell him exactly how you feel, and try to appeal to him to improve his behavior
 - time: -1
 - engagement: -3
 - performance: -2
 - total: round(((engagement * performance) / 100) - (100 - time))
 - next: brad_a

## You pick up 3 problematic situations from the past month where Brad’s behaviour have been a problem, and ask him to explain himself
 - time: -1
 - engagement: -4
 - performance: -3
 - total: round(((engagement * performance) / 100) - (100 - time))
 - next: brad_b

## You assume that there is an underlying problem that you should identify first. Therefore you start asking positive questions about what Brad likes/dislikes about his job – and ask into his ambitions for the future
 - time: -1
 - engagement: +2
 - performance: +2
 - total: round(((engagement * performance) / 100) - (100 - time))
 - next: brad_c

## You let him know that you are aware that there is a serious problem – but tell him that you are ready to help and coach him in weekly conversations for at least the coming 4 weeks
 - time: -5
 - engagement: +0
 - performance: +0
 - total: round(((engagement * performance) / 100) - (100 - time))
 - next: brad_d
