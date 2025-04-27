# extra-lives-dialogues
All in-game dialogues and help messages from Extra Lives by Mdickie

The dialogues file contain strong language, mentions of violence, firearms, and profanity. I have not modified them in any way beyond just seperating help, and dialogues.  

These were collected by extracting `game.swf` from the unzipped APK of Extra Lives, decompiling it, and then a grep search for strings, other patterns in the game source code. They were all clumped up in a single file along with code, and there was no distinction between help messages, dialogues.

There are some placeholder variables in the dialogues that can be replaced with a constant for easier reading. For example, `this.promoname[1]` always refers to the player name. It can be replaced with let's say "John Doe". Similarly, `this.He` is for the pronouns of the character. It can be replaced with "he". But I haven't done that to preserve the original.

For example, ""Let me help you, " + this.promoName[1] + "! We have" becomes "Let me help you John Doe! We have"

I am not the original creator of it. All rights reserved by the original creator. I'm just releasing it, under fair use, to preserve them and because I personally enjoyed some of them.
