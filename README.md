# Parakeet2HA
HA voice control 

Just a prrof of concept no LLM needed voice control of HA.

The LLM needs for turning on a lightbulb or staic fixed strings of HASSIL have always been a confusion for me.
So knocked this up over the last couple of days, its running on a I3-9100 mini pc with HA.
Uses the websockets API so can be situated anywhere and used Parakeet as I am a lazy Dev.
Rather than have hardcoded language strings when HA has translated presentation layers, why not use them.
So Parakeet do to its relatively low compute and fast speed and language support was used a demo.
Same methods with smaller models will work, but you have have individual language models and also maybe implement noise supression as parakeet is very tolerant.

Its extremely fast to update from end of voice command even on a I3-9100.
I have played about with the intent parser enough to get much working, but I don't really create product, just highlight methods and concept.
It can be set as an authoritive 2nd stage wakeword or without and could even replave the need for wakeword.

Anyway have a play, its MIT so copy and molest at your liesure.
