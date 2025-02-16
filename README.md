In the Year 2015 I created an online multi-sig wallet containing around 200.000 Dogecoin (worth ~25€ at the time),
I managed successfully to forget about it til recently - as actually planned, as I wanted to prevent to sell too early 
Sadly the way I remembered was the information that the service is being shutdown and there is only very low time left til they go offline.

I didn't manage to find my wallet password in time, but the owners told me to contact them once I find my password - If they will really help me in the end even if the password is found is uncertain though.
This password is one of the 2 private keys needed for the wallet, the other can be retrieved this first key if the site owners keep their word.

After a lot of digging I found a few clues about the password - but sadly those hints are cryptic themselves , using probably rather simple cyphers I came up with myself.

The account was created on April 13th but the messages containing the password might be from before.

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
- some messages might only contain parts of the message or be practice to get the algorithm down and might contain other onomatopoeic syllables or something which will stand out if correctly decoded but not be part of the password.
- there might be encoding errors

I made the encoding rules up with pen & paper and they are probably trivial once you know them, I remember practicing decoding it and it can be done without any complicated tables or calculation or smth, 
-There are most likely different cyphers being used - certain keywords or letters / letter combinations might change the rules (just like in the card game fluxx which I played a bit around that time)
-its all about deletions, swapping, maybe insertions, 
-there most likely is some vowelshifting going on,
-and the visual appearance of letters most likely is important ... p and b and d being the same just being rotated, 
-maybe some ligatures like "cl" which look similar to a "d" in some fonts or "rn" as "m" might also happen (but not necessarily those and not always and maybe those examples not at all)
-pronounciation might also be important (and somewhat inconsistently applied) . ("are" becoming "r")
-some letters might have a special meaning or be entirely removed.  ( "l" is very likely candidate to be - in many cases - not be a l but have some other function)
-Some keywords might change the rules. 2 same characters might also have a special meaning or trigger a positional swap
-removing whitespace might be important. 
- characters like "=" or numbers might maybe need to be rewritten as word
- there might be other rules... I remember something like searching for the same syllable (or its (in some way) mirrored version then picking this substring and symmetrically deleting left and right til only a few letters remain

At some point I might have realised this is way too complicated and later commit messages might have a reduced rule set.

  


This repository contains the hints I found and a json file with one of the private keys as encrypted passphrase + encryption algorithm information. (so password guesses can be tested against this).

