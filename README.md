#Regular Expressions Recipe Book
##Or: Regular Expressions, A Love Story

When's the last time you ever used a regular expression to solve a problem? Probably not recently. Even if you do have recent experiences using regexes, I venture you always sit around spending time crafting the right expression for the job. It seems like half the battle is matching the data you want matched and the other half is excluding all the data you don't want matched.

That's why I started this repo for myself, and anyone else who happens on it and finds it useful. I wanted to log all my regular expressions in one place in case I ever needed to look one up quickly. Why would I ever want to sit down and write an expression if I know I've written it beforehand? I don't want to be sitting at the terminal with `grep -rli "` for five minutes while I go left and right to add and subtract things in my expression.

Important note: I'm trying to make these regular expressions Emacs friendly, since that would make it the most "regular" expression possible, as Emacs lacks \d, instead requiring [[:digit:]] or [0-9].
