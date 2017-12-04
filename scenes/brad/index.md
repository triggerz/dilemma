# Dilemma 1: Brad

When you started, you were told that Brad was one of your top performers, but that’s not what you have experienced so far.
You have no doubt that he is talented, but you feel that he is getting sloppy (resting on the laurels?)
and often find him being arrogant, especially towards the newer team members.

It’s now time for your appraisal dialogue with Brad. What approach shall you choose?

*choice
    #You tell him exactly how you feel, and try to appeal to him to improve his behavior?
        *set time -1
        *set engagement -3
        *set performance -2
        *set total round(((engagement * performance) / 100) - (100 - time))
        *goto_scene brad_a
    #You pick up 3 problematic situations from the past month where Brad’s behaviour have been a problem, and ask him to explain himself
        *set time -1
        *set engagement -4
        *set performance -3
        *set total round(((engagement * performance) / 100) - (100 - time))
        *goto_scene brad_b
    #You assume that there is an underlying problem that you should identify first. Therefore you start asking positive questions about what Brad likes/dislikes about his job – and ask into his ambitions for the future
        *set time -1
        *set engagement +2
        *set performance +2
        *set total round(((engagement * performance) / 100) - (100 - time))
        *goto_scene brad_c
    #You let him know that you are aware that there is a serious problem – but tell him that you are ready to help and coach him in weekly conversations for at least the coming 4 weeks
        *set time -5
        *set engagement +0
        *set performance +0
        *set total round(((engagement * performance) / 100) - (100 - time))
        *goto_scene brad_d
