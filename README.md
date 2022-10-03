# This is a Level 1 Heading

## Let's Learn an ESLint Rule : semi

semi is an important rule because the creators of JavaScript
basically took something that was simple and made it complicated
for no apparent reason. While the argument can be made that a
semi-colon isn't required because of **automatic semicolon insertion** (ASI),
it can cause unintentional problems down the line.

The answer to this is semi. By enabling the "always" option in semi,
you can ensure that your code will ALWAYS have semicolons in the correct places.
If you are crazy enough to set it to "never" it will still have semicolons
in the correct places, but also it will allow you too foolishly and
wrecklessly leave semicolons out in the rest of your precious code.

Enrich yourself on the use of semi here:
[semi: A Good Idea](https://eslint.org/docs/latest/rules/semi)