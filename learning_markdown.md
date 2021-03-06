## Markdown is easy to learn. 

What's it all about?

Simple: 
It's just typing a few simple characters like # or * before and/or after the text. Then bam! Those characters are interpreted as changes in font, headings, and more! Ok, to be honest, there are few little things to master, such as exact spacing and the use of characters that you don't normally use, such as `, but it's nothing you can't get the hang of in about an hour. 

Say you want to check items off a list. On a new line enter a dash, then a space, then a left-side bracket (it's next to the p key). Then enter a lower case x and a right-side bracket (hopefully you've found that by now). 

Then hit space and name your list item. Hit return and repeat the process. Remember, no x if it's not done! The [x] ends up looking like a checked box: 

- [x] Learn what brackets are.
- [ ] Watch the Brak show.

Behind the scenes:

`- [x] Learn what brackets are.`
<br>
`- [ ] Watch the Brak show.`

Learning Markdown is as simple as following cookbook instructions. In this case the main recipes are found here: [This is the recipe](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax). 

## Security alert: You should only click a trusted link. But it's ok, you can trust me...Which is what they all say!

FYI that line above actually started like this in Markdown:

`## Security alert:...` 

Don't forget to put a space after the hashes. This is the case with most Markdown signs that do things. Otherwise they won't work. Not so with brackets, parentheses, or those backwards apostrophes we call tick marks,  though! 

`Tick marks before and behind your text actually make text appear just like these words do in this funny typewriter font. It's called inline. You may want to use it for examples or for computer code itself.`

Moving on to links. They simply take you to another page (underlined, blue and clickable ringing a bell?). Use the fun brackets to name the link `[link goes here]` then without hitting space put some good old parentheses and paste that link between 'em `(https://www.duckduckgo.com)` which will actually be hidden upon display. 

[Hover over this link to see if it's legit. You can read it in the bottom left hand corner of your browser.](https://www.google.com)

And now pulling back the curtain: 

`[Hover over this link to see if it's legit. You can read it in the bottom left hand corner of your browser as being a trusted domain](https://www.google.com)`

And remember, once you master the easy stuff, you can master the harder stuff like tables: 

| What | Why |
| --- | --- |
| code | instruct machine |
| cables | connect machines |

Now this might seem complicated but it's not. All you have to do is find the key that has a vertical line on it above the enter/return key, usually. Hold control and hit that key (on a new line, no spaces). Then on the same line enclose the name of the first column within these lines after a space before and after (called pipes):

`| What | Why |`

That's only the top row that names the columns. To make it look like the top row, which tells you what category is in the columns, put this on the second line: 

`| --- | --- |` 

Remember to get the spacing right (one space on both sides of the three dashes).   

Now add the columns you need. Just don't add more or less than the number of table headers you defined at the beginning:

`| code | instruct machine |` <br>
`| cables | connect machines |`

The whole thing should look like this:

`| What | Why |` <br>
`| --- | --- |` <br>
`| code | instruct machine |` <br>
`| cables | connect machines |` 

So, this was a hop, skip, and a jump through markdown. We touched on the most basic stuff such as header size and links, but also did some more complex Markdowns, creating lists that can be checked off, and even a table. 

Challenge: insert an image into your .md file. 

