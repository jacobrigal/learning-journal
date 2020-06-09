## Dynamic Web Pages with JavaScript

- HTML, CSS, and JavaScript are three different layers. HTML is the content layer, CSS is the presentation layer, and JavaScript is the behavior layer. These layers should be kept in seperate files as much as possible. 

- Progressive enahncement: start with HTML only to focus on the content. Then add a CSS file to enhance how the basic content is presented. Finally, add JavaScript as a seperate file. This allows the page to load even if JS is disabled. Also keeping files seperate is faster. Keep these files is seperate folders to stay organized. 

## Adding a greeting based on the time of day. 

Write the code in a seperate file with a .js exension: 

    var today = new Date();
    var hourNow = today.getHours();
    var greeting;

    if (hourNow > 18) {
    greeting = 'Good evening!';
    } else if (hourNow > 12) {
    greeting = 'Good afternoon!';   
    } else if (hourNow > 0) {
    greeting = 'Good morning!';
    } else {
    greeting = 'Welcome!';
    }

    document.write('<h3>' + greeting + '</h3>');

Link the file in the .html file between the `<script src=""></script>` tags with whatever you named your .js file, and to the folder you saved it in. Put this line of code in the `<body></body>` section: 

    <script src="js/addcontent.js"></script> 

This will insert a heading with a greeting based on the time of day. If it's after midnight, but before, noon, the greeting will say, "Good morning!", if it's after noon and before 6pm, it will say, "Good afternoon!", and if it's after 6pm, it will say, "Good evening!"