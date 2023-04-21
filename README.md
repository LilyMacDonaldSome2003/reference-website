# reference-website

1. Naming convention for all filenames, paths and folders
- There are three conventions, All have to be lowercase, there should be no spaces, and use only letters, numbers, and dashes.

2. Best practices for commit messages
- One best practice to commit messages 

3. What is HTML?
- HTML is the coding language used to describe the content of websites known as Hypertext Markup Language.

4. Proper syntax for HTML tags
- The tags are used to define the role of the text. For example '<h1>I am a heading</h1>'

5. Explain or demonstrate commonly used html tags/elements:
    headings: h1-h6
    - h1 demonstrates the most important heading of the web page. 
    - h6 demonstrates the least important heading and the smallest one out of all the headings.
    p
    - p demonstrates the paragraph 
    lists: ul, ol, dl
    - ul demonstrates an unordered list
    - ol demonstrates an ordered list
    - dl stands for description list
    a
    - open <a> demonstrates where the link should begin and the end.
    - closing </a> demonstrates where the link ends.
    img
    - img represents the image and the location of the image and the alternative content
    figure (img & figcaption)
    q
    - q demonstrates quotes embedded in the element to show a paragraph.
    blockquote
    - blockquote demonstrates large stand quotes.
    cite
    - cite demonstrates the source of the quote.
    em
    - em is a phrasing element that demonstrates the emphasis.
    strong
    - strong is a phrasing element that demonstrates the many emphasis and strong importance.
    b
    - be is a phrasing element that demonstrates a keyword.
    i
    - i is a phrasing element that demonstrates another language, technical term and/or title.
    small
    - small demonstrates a sentence that's small or tiny.
- 

6. Explain block Elements and also explain the list of block elements and why they are used from below:
    html
    head
    body
    header
    nav
    main
    section
    article
    div
    aside
    footer
    span
    small
- Block elements are used to group elements together. The list of block elemts are used to give meaning to the content yet sometimes an element is needed for meaningless.

7. Explain why accessibility is important and also explain the accessibility properties like:
    landmark roles
    aria labels
    image alternative texts
- Accessibility is important because it makes the web work for everyone, including users with disabilities. Landmark roles are to help those who use screen readers. Aria labels are to help the user with a non-visual label. And image alternative texts are the written copy that appears in place of an image on a webpage if the image fails to load on a user's screen.

8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)
- CSS is defined as Cascading Style Sheets which is a language used to control appearence and style of the html page provided.

9. What is the difference between CSS property and value (write explanation and an example code)
- The difference between CSS property and value is that the property is the type of design you want to add and the value is the accepted value for the property

-Ex.  h1 {
        color: red;
      }

10. Why do we use border-box property in CSS?
- We use border-box property in CSS because it is friendlier for flexible layouts also padding and border are included in the width and height along with it.

11. Explain different type of ways we can add spacing to an element
- There are two different ways to add spacing to an element, the padding and margin properties.

12. What is the main difference between margin and padding?
- Margin is invisible space around your box and padding adds spacing within the box, pushing the content away from the border. 

13. What are different types of display properties?
- Display properties manages and alters how the HTML elements are represented on the web page. There are four different display properties, Inline elements, Block elements, Inline-block elements, and Hiding elements with display. 

14. Write a brief explanation of flexbox property
- The flexbox property applys to the parent element, but affect the child elements.

15. What are different types of flexbox properties and what is the major difference between them?
- flex-direction.
- flex-wrap.
- flex-flow.
- justify-content.
- align-items.
- align-content
- The major difference between them are the offers of greater control over alignment and space distribution between items.

16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property
-  <section>
       <div>
       <div>
   </section>    

- section {
    display: flex;
  }

17. Write a code example on how you will use a flexbox property on a parent element with sub properties.
- <section>
    <div>
     <p>Lorem ipsum</p>
    <div>
   </section>  

18. What is CSS grid property?
- CSS grid property is a two-dimensional grid system to CSS. The grids can be used to lay out major page areas or small user interface elements.

19. Write the parent and two sub-properties used for CSS Grid Property.
- <main>
    <header>Header</header>
    <article>Article</article>
    <nav>Sidebar</nav>

    <footer>Footer</footer>
  </main>

20. What is the difference between display: flex and display: grid?
- Display: grid is better suited for creating two-dimensional layouts, while display: flex is better for one-dimensional designs.

21. What sub-property we use to divide elements in CSS Grid properties?
- grid-template-columns.

22. What unit we use to fractionally divide the element width in CSS Grid property and what are others unit we can use alternatively? (Write a code example)
- .grid {
    display: grid;
    grid-template-columns: 2fr 1fr 300px;
   }

23. What is the area property in CSS grid we use for the child elements?
- The area property in CSS grid is a grid item's size and location within a grid by contributing a line, a span, or nothing (automatic) to its grid placement, thereby specifying the edges of its grid area.

24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property.
- .grid {
    display: grid;
    grid-template-columns: 2fr 1fr 300px;
   }

25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file.
- 1. Go to https://fonts.google.com/ 
- 2. Choose or type in a font you want for your website don't forget to select serif and/or sans-serif.
- 3. Once picked, choose the styles of the font and click on the add button.
- 4. Copy the html link into html file and the CSS link to CSS file.