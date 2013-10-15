#Regular Expressions

#####Find e-mail addresses:
    .*@.*\.[a-zA-Z]{2,3}

#####Find phone numbers (US):
    (1-)?[2-9][0-9]{2}-[0-9]{3}-[0-9]{4}

#####Find dollar amounts:
    (\$[0-9]*(\.[0-9]{2})?|[0-9]*\.[0-9]{2})

#####Find where one sentence ends and another begins:
    \w\W\W? [A-Z0-9]

#####Find trailing whitespace:
    [ \t]+$
