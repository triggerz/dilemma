# Config
 - Title: Dilemma 2: Veronica

# Description
Veronica is a well qualified HR Leader in your team and well liked with her internal clients.
But she is not as dominant as some of the alpha-type persons in your department,
and several times in the past months you have seen the team coming down on her – even making fun of her Scottish dialect - and not taking her seriously.
Lately you have seen her leave team meetings with a tormented expression in her face.
You have tried to let her know that your door is always open if she wants to talk – but so far she has just answered with a ”everything is fine”.

You know that’s not true. What approach shall you choose?


# Choices
## Keep letting her know that you are there when she need you – but not push her any further (she must come forward when she is ready to talk)
 - time: -1
 - engagement: -1
 - performance: -1
 - total: round(((engagement * performance) / 100) - (100 - time))
 - next: veronica_a

## Invite her to an extraordinary development conversation. Start by letting her know how well she is performing – but also bring your concerns up directly, offering to spend time and effort in figuring out how to best handle the challenge.
 - time: -1
 - engagement: +2
 - performance: +2
 - total: round(((engagement * performance) / 100) - (100 - time))
 - next: veronica_b

## Invite her to a meeting formally about a project that you are both involved with – but  during the conversation turn to the real subject of concern. Start by letting her know how well she is performing – but also bring your concerns up directly, offering to spend time and effort in figuring out how to best handle the challenge.
 - time: -1
 - engagement: +3
 - performance: +3
 - total: round(((engagement * performance) / 100) - (100 - time))
 - next: veronica_c
