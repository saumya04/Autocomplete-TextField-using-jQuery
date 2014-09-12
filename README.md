Autocomplete-TextField-using-jQuery
===================================

Enables users to quickly find and select from a pre-populated list of values as they type, leveraging searching and filtering.

Explanation :
===================================
We need following files to make it work..!!

•	index.html      ----    Main Source File through which we give a raw designing to our project

•	jquery.ui.autocomplete.min.js
•	jquery.ui.core.min.js
•	jquery.ui.position.min.js
•	jquery.ui.widget.min.js
•	jquery-1.7.1.min.js
•	jquery-ui-1.8.16.custom.css
The files highlighted with red color are the files provided by jquery.com’s website which have their own working.
The file named “jquery.ui.autocomplete.min.js” is a part of jQuery UI Framework, it handles autocomplete functioning.
The file named “jquery.ui.core.min.js” is a part of jQuery UI Framework, it handles all the core functioning of jQuery UI.
The file named “jquery.ui.positioning.min.js” is a part of jQuery UI Framework, it handles autocomplete functioning.
The file named “jquery.ui.widget.min.js” it provides suggestions while you type into the, it is a part of jQuery main Framework file (v.1.7.1)
The file named “jquery-ui-1.8.16.custom.css” is a stylesheet provided by jQuery which handles all the styling of the autocomplete textbox field.

•	bg.jpg
•	dark-yellow_1x100.png
The “bg.jpg” file is used to set a custom background of the main page.

The “dark-yellow_1x100.png” file is responsible for setting up the dark yellow colored background of the autocomplete dropdown list.

First of all it is very important to include or import some important javascript files & stylesheets (all the files mentioned above) to our main file named – index.html
So to make the Text Box & the whole page to look according to the design in my mind, I added some css code myself in which I changed some colors, padding, borders, background, font style, and lots of other stuffs.
To see that stuff kindly see the <style>…</style> tag section in index.html.
====================<style>…</style>====================
Now comes the step of the data or you can say it as - Database that should be shown in dropdown menu whenever user wants to search for the particular item.
I choose to prepare that particular database to be created in javascript or <script>…</script> tags itself so that it could be much simple.
As I am a huge fan of Soccer/Football so I choose to prepare the database of some cool soccer players (majorly for wingers). Please don’t mention it, you can create of your own database such that – for Countries, Colors, etc..!!
You can see them in <script>…</script> tags just after starting of <body> tag.
The general form for making the database in javascript is –
<script>
var data = [ “a”, “b”, “c”,…….];
</script>
====================<script>…</script>====================
Now as you can see I’ve also used a function inside the <script> tags which helps us for limiting the Suggestions Result Lists.
Here I’ve given 10 as limit.

At last here comes the main code for creating the Text Field which is created under <input>…</input> tags.
====================<center>…</center>====================
