## Markdown is easy to learn. 

What's it all about?

Simple: 
It's just typing a few simple characters like # or * before and/or after the text. Then bam! Those characters are interpreted as changes in font, headings, and more!

Say you want to check items off a list. On a new line enter a dash, then a space, then a left-side bracket (it's next to the p key). Then enter a lower case x and a right-side bracket (hopefully you've found that by now). 

It should look like this:

[x]

Then hit space and name your list item. Hit return and repeat the process. Remember, no x if it's not done! The [x] ends up looking like a checked box: 

- [x] Learn what brackets are.
- [ ] Watch the Brak show.

Learning Markdown is as simple as following cookbook instructions. In this case the main recipes are found here: [This is the payload](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax). 

## Security alert: You should only click a trusted link. But it's ok, you can trust me...Which is what they all say!

FYI that line above actually started linke this in Markdown:

`## ` and don't forget to put a space after the hash. This is the case with most Markdown signs that do things. Not brackets, parentheses, or those backwards apostrophes we call ticks,  though! 

Moving on to links. They simply take you to another page (underlined, blue and clickable ringing a bell?). Use the fun brackets to name the link `[link goes here]` then without hitting space put some good old parentheses and paste that link between 'em `(www.duckduckgo.com)` which will actually be hidden on your website. 

[Hover over this link to see if it's legit. You can read it in the bottom left hand corner of your browser.](https://www.google.com)

And now pulling back the curtain: 

`[Hover over this link to see if it's legit. You can read it in the bottom left hand corner of your browser as being a trusted domain](google.com)`

And remember, once you master the easy stuff, you can master the harder stuff like tables: 

| What | Why |
| --- | --- |
| code | instruct machine |
| cables | connect machines |

Now this might seem complicated but it's not. All you have to do is find the key that has a vertical line on it above the enter/return key, usually. Hold control and hit that key (on a new line, no spaces). Then on the same line enclose the name of the first column within these lines after a space before and after (called pipes):

`| What | Why |`

That's only the top row that names the columns. To make it look like the top row that tells you what's in the columns, put this on the second line: 

`| --- | --- |` 

Remember to get the spacing right.  

Now add the columns you need. Just don't add more or less than the number of table headers you defined at the beginning:

`| code | instruct machine |` <br>
`| cables | connect machines |`

The whole thing should look like this:

`| What | Why |` <br>
`| --- | --- |` <br>
`| code | instruct machine |` <br>
`| cables | connect machines |` 

Ok, that's enough.

