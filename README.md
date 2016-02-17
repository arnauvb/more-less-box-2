Do you want to add to your website a box that expands and contracts when you click on it?

Follow the instructions behind and with this HTML code you will have your very own more-or-less box.

To start with, you have to create a JSfiddle account.

In there you will find three boxes. The top left one is for HTML, the top right is for CSS and the bottom left is for Javascript. On the bottom right you will be able to visualise all the things you are doing. 

To see them, you have to click on the "RUN" button - which you will find on the top left hand side -.

A good tip is to include some text both in the website and inside the more-or-less box. By doing this, you will see and have a better idea on how does the final product will look like. 

The first thing to do is a heading.

You have to write `<h1>´
(to open the heading),
followed by the text you want to use as the heading, and then adding 
`</h1>´ 
(to close the heading.)

The next step is to create some paragraphs, in order to give some content and body to your website.

Every time you want to create a paragraph, you will type in <p> followed by the text and then </p>.

If you want to have another paragraph, you will write the same as in the line above. The same happens with the headings, but you have to remeber to change the number every time you are writing a new heading. 

# H1 stands for heading one, whilst ## H2 stands for heading two, and so on. 

After the heading and the paragraph, I am sure you will have some facts that you would like to put in a box.

At this point is when you have to do a more or less box.

The first thing to do is to create a div class named "more-less box": <div class="more-less-box">

The function <div> defines a division or a section in an HTML document.

Inside the div class, you have to create a third heading <h3></h3>. 

The third heading will be Fact Box. So, you will have to have something like this: 

<h3>
Fact Box
</h3>

The next step is to create a paragraph inside the fact box.

Bearing in mind what it has been said before, you will start with: <p class="more-less-area collapsed"> followeb by the paragraph you want to use.

At the end of the paragraph you will have to close it by adding: </p>.

The next step is to create a button inside the fact box, which gives the opption to expand or contract the text whenever the reader wants to. 

To have this option, the first thing to write is: <a class= "more-less-button"

Then, you have to add this href: "javascript:void(0);"onclick="toggleMoreLess('.more-less-area')">Show/Hide

And, before finishing, you can't forget to close both </a> and </div>

Right under the HTML side, you will find the Javascript one. In order to link with Javascript the fact box you have donw with HTML, you will have to write the following:

function toggleMoreless(areaClass){
$(areaClass).toggleClass('collapsed');
}

Finally, the last step is to work on the CSS. As said at the begining, you will find the CSS on the top left of the page.

CSS allows you to design your box, so you can make it look the way you prefer.

There are some concepts to bear in mind, when designing your box, such as:

width
box-sizing
margin
padding
overflow

And many more others. But this is up to you. It's your website and it's your fact box, so you have to use your own criteria when it comes to design it.

# more-less-box-2
An expandable box for news articles
