In the Year 2015 I create an online multi-sig wallet containing around 200.000 Dogecoin (worth ~25€ at the time),
I managed successfully - as actually planned! - to forget about it til recently.
Sadly the way I remembered was the information that the service is being shutdown and there is only very low time left til they go offline.

I didn't manage to find my wallet password in time, but the owners told me to contact them once I find my password.
This password is one of the 2 private keys needed for the wallet, the other can be retrieved this first key if the site owners keep their word.

After a lot of digging I found a few clues about the password - but sadly those hints are cryptic themselves , using probably rather simple cyphers I came up with myself.

The password probably consists of 3 parts :
- a part consisting of 3 letter abbreviations
- a part which is entirely made up of p,i and n ( e.g pinpippinnniip)
- a part which is made up of 2-letter syllables arranged in a very onomatopoeic way, often with the same syllable repeated twice and then transitioned to another one with the transition sounding nicely and mostly in a way that it resembles real word parts. (momobonobodogogotododo)
- that part is most likely entirely made up of alternating vowels and consonants (with o probably being the most common one by a wide margin), but there might be 1 or even 2 exceptions, most likely a doubled "o" (but this might also be a wrong memory and be part of the 3 letter abbreviations)

- the password only allowed alphanumeric characters (a-z , A-Z , 0-9) - I am quite sure that there are either no numbers or a very low amount (something like a 1 at the very end or so)

What I assume is the hint for the p,i,n part is in the httphint.txt file 
The 2-letter syllables part is definitely hidden in the commitmessages.txt
The 3-letter abbreviations probably too

there might be 1 word interpersed into the password which is out of place, probably between 2 parts
this word is most likely threepwood or vinividivici (most likely with this spelling mistake, or maybe venivedivici), but vinividivici might also be part of the 2 latter part (maybe in abbreviated form like vinidici)

- some (or maybe many) of the commit messages might be just normal commit messages, the one with meaning have been intentionally build in a way that they dont stand out

There are most likely different cyphers being used - certain keywords or letters / letter combinations might change the rules (just like in the card game fluxx which I played a bit around that time)


This repository contains the hints I found, some general information about the password and a json file with one of the private keys as encrypted passphrase + encryption algorithm information. (so password guesses can be tested against this).
