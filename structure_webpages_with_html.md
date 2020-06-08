## Preliminary structuring of webpages with HTML: Planning - Sketching - Wireframing - Ongoing Collaboration 

Writing code should actually be the last step in the process. First you should ask yourself some overarching questions, such as, "what do I want my website to do? How do I want to present the content?" Once you have a very general idea, then you can follow these basic steps: 

1. What is the cause, or the apps reason for being? Therefore, what will the content be? What needs to be conveyed? Is there an organization you are part, or are linked to, that you may want to involve? What types of data/info is it? How will the content function? At this point you should be pitching your ideas to your teach, and vice versa. 

2. How will the content be structured/organized? What pages need to come into being? Prioritize what needs to be seen first by the user. Block elements into what may later become sections on the pages. What is the relationship between these blocks of content? 

3. Sketch it out! Using paper or a whiteboard is recommended, because it is more hands on and changeable. You can print out templates to aid with this. This is wireframing. After brainstorming a few possible designs by sketching them out, settle on the wireframed design you will use. 

4. As part of the ongoing development process, create a Slack message group to continue to communicate, as the development process will be spread over a period of time to be determined. This will also facilitate code-sharing. 

## Helpful allegories (HTML, CSS, JS)

1. HTML (HyperText Markup Language) is the skeleton of the body. It forms the core structure that is essential for the appearance and functioning of the body. 
<br><br> Alt. = Wooden frame of a house (Allow the house to stand in the firstplace in order build other things on top of the frame). 


2. CSS (Cascading Style Sheets) is the clothing. It controls much of the basic styling of the website, such as background, containers, tables, images, and more. 
<br><br>Alt. = Drywall, paint, trim, polish (Makes the house look nice). 

3. Javascript is the muscle of the website. It does things, often faciliating changes on the website through user input or action, helping the website to be more dynamic and functional. <br><br>Alt. = Plumping, electrical (If I turn this faucet, this switch, something happens)

## HTML Basics

- Tags markup or wrap the content. There are opening tags and closing tags. Closing tags have a forward slash after the first carrot:

       <p>This will be a new paragraph</p>

- Some tags don't need a closing tag (self-closing): 

       <br> This will also be on a new line, but no need to close the tag. 

- Use lower case. 

- Tags tell browser how to display content. 

- Attributes like `href` and `src` further modify tags and how they behave.

HTML boilerplate (the most basic skeleton of HTML): 

    <!DOCTYPE html>
        <head>
            <title></title>
        </head>
        <body>
            <script></script>
        </body>
    </html>