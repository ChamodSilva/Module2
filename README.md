## Module 2 Lab Exercises.

---
<div style="border: 12px solid #ccc; padding: 10px; margin-bottom: 10px;">
  <details>
    <summary>Exercise 1 - HTML</summary>
    <ul>
      <!-- SECTION I -->
      <details>
        <summary>Template and Live Server</summary>
        <ul>
          <li>
            Open the src folder in VS code and take a look at the template HTML files.
          </li>
          <li>
            With index.html opened, start the Live Server extension by clicking the Go Live button in the bottom
            right-hand corner of VS Code.
          </li>
          <li>
            This should open <code>http://127.0.0.1:5500/index.html</code> in your browser.
            <ol>
              <li>
                Change the above URL to load the form.html page, and then click the Home link to go back to index.
              </li>
            </ol>
          </li>
        </ul>
        <img alt="Exercise 1 - Template and Live Server" src="/Lab Screenshots/Exercise1/Exercise1-1.gif">
      </details>
      <!-- SECTION II -->
      <details>
        <summary>HTML Elements - Metadata</summary>
        <ul>
          <li>
            Add a title using the HTML title tag.
          </li>
          <li>
            Add metatags using HTML
            <meta> tags for the following 5 items:
            <ul>
              <li>charset</li>
              <li>description</li>
              <li>keywords</li>
              <li>author</li>
              <li>viewport</li>
            </ul>
          </li>
        </ul>
        <img alt="Exercise 1 - HTML Elements - Metadata" src="/Lab Screenshots/Exercise1/Exercise1-2.png">
      </details>
      <!-- SECTION III -->
      <details>
        <summary>HTML Elements- div, span, p, pre, ul, li, ol, article</summary>
        <ul>
          <li>
            Add 3 divs next to each other at the beginning of the body section and put some distinctive content into
            each of the divs.
          </li>
          <li>
            Below the divs, add 3 spans next to each other and put some distinctive content into each span. Observe the
            difference between block and inline elements in the browser.
          </li>
          <li>
            Below, add p and pre tags into your HTML body using the below contents:
            <pre>
"&lt;p&gt;
p represents paragraph without preserving spacing
&lt;/p&gt;
&lt;pre&gt;
Text in a pre element
is displayed in a fixed-width
font, and it preserves
both spaces and
line breaks
&lt;/pre&gt;"
            </pre>
          </li>
          <li>
            Add an unordered list of 4 items to your page using ul and li tags.
          </li>
          <li>
            Add an ordered list of 3 items to your page using ol and li tags.
          </li>
          <li>
            Add a nested list of 2 items inside the last item of either the unordered or ordered list above.
          </li>
          <li>
            Wrap all the elements you've created so far with an article tag.
          </li>
          <li>
            Add a page headline - add an h1 tag above your article with any content, e.g. "My HTML learning journey".
          </li>
          <li>
            Add an article headline - add an h2 tag within the article tag with any content, e.g.
            "Learning elements - div, span, p, pre, ul, li, ol, article". Consider the difference between the page headline and article headline.
          </li>
        </ul>
        <img alt="Exercise 1 - HTML Elements - div, span, p, pre, ul, li, ol, article - 1" src="/Lab Screenshots/Exercise1/Exercise1-3-1,2,3,4,5,6,7,8,9-1.png">
        <img alt="Exercise 1 - HTML Elements - div, span, p, pre, ul, li, ol, article - 2" src="/Lab Screenshots/Exercise1/Exercise1-3-1,2,3,4,5,6,7,8,9-2.png">
      </details>
      <!-- SECTION IV -->
      <details>
        <summary>HTML elements - Tables - table, thead, tbody, tr, td, th</summary>
        <ul>
          <li>
            Start by adding another article below the first one, with a unique h2 tag inside this newly created article.
          </li>
          <li>
            Below, add p and pre tags into your HTML body using the below contents:
            <pre>
&lt;table&gt;
    &lt;thead&gt;
    &lt;tr&gt;
        &lt;th&gt;First header&lt;/th&gt;
        &lt;th&gt;Second header&lt;/th&gt;
    &lt;/tr&gt;
    &lt;/theah&gt;
    &lt;tbody&gt;
        &lt;tr&gt;
            &lt;td&gt;First cell - first row&lt;td&gt;
            &lt;td&gt;Second cell - first row&lt;td&gt;
        &lt;tr&gt;
    &lt;/tbody&gt;
&lt;/table&gt;
            </pre>
          </li>
          <li>
            Create another row by copying a tr tag, together with its children, below the first row.
          </li>
          <li>
            4.	By default, tables don't have any styles. Add basic styling by copying the code below to the head section of the page:
            <pre>
&lt;style&gt;
  table, th, td {
    border: 1px solid black;
  }
&lt;/style&gt;
            </pre>
          </li>
          <li>
            Add a third cell inside one of the rows. Observe how the table lost its shape.
          </li>
          <li>
            Each table row needs to account for the same amount of columns, and violating this rule will cause your table to lose shape. Fix the table by adding the missing td tag on the other row/s.
          </li>
          <li>
            Now the header is missing for the third column. Fix this by adding a colspan attribute to the first th tag to make it span two columns.
          </li>
          <li>
            Add a third row with 2 columns to the table and add a rowspan="2" attribute to one of the td tags on the second row, then observe what happens.
          </li>
        </ul>
        <img alt="Exercise 1 - tables - table, thead, tbody, tr, td, th - 1" src="/Lab Screenshots/Exercise1/Exercise1-4-1,2,3,4,5,6,7,8-1.png">
        <img alt="Exercise 1 - tables - table, thead, tbody, tr, td, th - 2" src="/Lab Screenshots/Exercise1/Exercise1-4-1,2,3,4,5,6,7,8-2.png">
      </details>
      <!-- SECTION V -->
      <details>
        <summary>HTML Elements - img, video, audio</summary>
        <ul>
          <li>
            Start by adding another article below the second one, with a unique h2 tag inside this newly created article.
          </li>
          <li>
            Add an image to your website using the code below. Add a value for the alt attribute, and experiment with using one, then both of the width and height attributes to change the size of the image.
            <pre>
&lt;img src="https://picsum.photos/400/400" alt="" /&gt;
            </pre>
          </li>
          <li>
            Add a second image using the html_lab_image.jpg file from the assets folder. Give it an alt attribute and make it appear the same size as the first image.
          </li>
          <li>
            Add a video using the example code below:
            <pre>
&lt;video controls width="250"&gt;
  &lt;source src="/assets/flower.webm" type="video/webm"&gt;
  Sorry, your browser doesn't support embedded videos.
&lt;/video&gt;
            </pre>
          </li>
          <li>
            Add an audio element using the example code below, then add a caption to it using figure and figcaption:
            <pre>
&lt;audio controls src="/assets/t-rex-roar.mp3"&gt;
  Your browser does not support the &lt;code&gt;audio&lt;/code&gt; element.
&lt;/audio&gt;
            </pre>
          </li>
          <li>
            Try removing the controls attribute and adding autoplay attribute to both audio and video tags. Observe the changes.
          </li>
        </ul>
        <img alt="Exercise 1 - HTML Elements - img, video, audio - 1" src="/Lab Screenshots/Exercise1/Exercise1-5-1,2,3,4,5,6-1.png">
        <img alt="Exercise 1 - HTML Elements - img, video, audio - 2" src="/Lab Screenshots/Exercise1/Exercise1-5-1,2,3,4,5,6-2.png">
      </details>
      <!-- SECTION VI -->
      <details>
        <summary>HTML Elements - Forms - form, input, label, select, option, button</summary>
        <ul>
          <li>
            Add a form using a &lt;form&gt; tag like this:
            <pre>
&lt;form method="POST" action="http://127.0.0.1:5500/form.html"&gt;
&lt;/form&gt;
            </pre>
          </li>
          <li>
            Inside the form, add 2 text inputs - one for inputting first name and the second one for inputting last name.
            <ol>
              <li>
                Remember to add a label for each input. 
              </li>
              <li>
                Wrap each input, together with its label, in a div to stack the inputs one below another. 
              </li>
            </ol>
          </li>
          <li>
            Add 3 radio buttons using &lt;input type="radio" ...&gt;, allowing the user to select their favourite coding language.
            <ol>
              <li>
                Remember to label the inputs and add name and value attributes. 
              </li>
              <li>
                Wrap the radio buttons in a div to separate them from the other form fields. 
              </li>
            </ol>
          </li>
          <li>
            Add 3 checkboxes using &lt;input type="checkbox" ...&gt;, allowing the user to select the types of vehicles they own.
            <ol>
              <li>
                Remember to label the inputs and add name and value attributes.
              </li>
              <li>
                Wrap the checkboxes in a div to separate them from the other form fields. 
              </li>
            </ol>
          </li>
          <li>
            Add a dropdown element to your form using &lt;select&gt; and &lt;option&gt; tags, allowing the user to choose the brand of car they own. 
            <ol>
              <li>
                Remember to label the dropdown and add a value attribute for each option.
              </li>
            </ol>
          </li>
          <li>
            Add a submit button at the end of the form:
              <pre>
&lt;button type="submit"&gt;Submit form&lt;/button&gt;
              </pre>
          </li>
        </ul>
        <img alt="Exercise 1 - HTML Elements - iForms - form, input, label, select, option, button - 1" src="/Lab Screenshots/Exercise1/Exercise1-6-1,2,3,4,5,6-1.png">
        <img alt="Exercise 1 - HTML Elements - iForms - form, input, label, select, option, button - 2" src="/Lab Screenshots/Exercise1/Exercise1-6-1,2,3,4,5,6-2.png">
      </details>
      <!-- SECTION VII -->
      <details>
        <summary>Adding a link from Home to Form page</summary>
        <ul>
          <li>
            Add another &lt;a&gt; element, linking to the form page, inside the &lt;nav&gt; tag in both index.html and form.html.
          </li>
          <li>
            Test your links by clicking them to navigate to both pages.
          </li>
        </ul>
        <img alt="Exercise 1 - Adding a link from Home to Form page - 1" src="/Lab Screenshots/Exercise1/Exercise1-7-1,2-1.png">
        <img alt="Exercise 1 - Adding a link from Home to Form page - 2" src="/Lab Screenshots/Exercise1/Exercise1-7-1,2-2.gif">
      </details>
      <!-- SECTION VIII -->
      <details>
        <summary>Inspecting the HTML</summary>
        <ul>
          <li>
            Use inspection tool – right click anywhere on the page and click ‘Inspect’.
          </li>
          <li>
            Select various elements on your website by clicking on them using the Elements tab of the Inspection tool. Observe how they are highlighted as you hover and click them.
          </li>
          <img alt="Exercise 1 - Inspecting the HTML - 1" src="/Lab Screenshots/Exercise1/Exercise1-8-1,2-1.gif">
          <li>
            Take a look at the CSS in the "Styles" subtab (under or right of the "Elements" tab) and try editing the CSS styles. For example you may try adding some of the following values:
            <pre>
margin: 20px; color: blue; font-size: 24px;
            </pre>
          </li>
          <img alt="Exercise 1 - Inspecting the HTML - 2" src="/Lab Screenshots/Exercise1/Exercise1-8-3-1.gif">
        </ul>
      </details>
    </ul>
  </details>
</div>

<!-- Exercise 2 -->
<div style="border: 12px solid #ccc; padding: 10px; margin-bottom: 10px;">
  <details>
    <summary>Exercise 2 - CSS Basics</summary>
    <ul>
      <details>
        <!-- SECTION I -->
        <summary>Selectors and Combinators</summary>
        <ul>
          <!-- Step 1 -->
          <li>Selectors</li>
          <ul>
            <li>
              Using the type selector, add margin, padding and border to each &lt;article&gt; on the page, e.g.
              <pre>
margin: 20px 0;
padding: 20px;
border: 1px solid black;
              </pre>
            </li>
            <li>
              Using a class selector, change the font color of the element with class style-me1 to red
            </li>
            <li>
              Using an id selector, change the font color of the element with id <code>style-me2</code> to blue
            </li>
            <li>
              Using a specific selector, change the font color of the element that has both a class of <code>style-me1</code> and an id of <code>style-me2</code> to purple.
            </li>
            <img alt="Exercise 2 - Selectors - 1" src="/Lab Screenshots/Exercise2/Exercise2-1-1-1,2,3,4-1.png">
            <img alt="Exercise 2 - Selectors - 2" src="/Lab Screenshots/Exercise2/Exercise2-1-1-1,2,3,4-2.png">
          </ul>
          <!-- Step 2 -->
          <li>Combinators</li>
          <ul>
            <li>
              Using a descendant combinator, style all the &lt;p&gt; elements that are descendants of <code>.my-descendants-are-styled</code> by setting their background to red.
            </li>
            <li>
              Using a child combinator, style all the &lt;p&gt; elements that are direct children of <code>.my-children-are-styled</code>, by setting their background to lightgreen.
            </li>
            <img alt="Exercise 2 - Combinators - 1" src="/Lab Screenshots/Exercise2/Exercise2-1-2-1,2-1.png">
            <img alt="Exercise 2 - Combinators - 2" src="/Lab Screenshots/Exercise2/Exercise2-1-2-1,2-2.png">
          </ul>
        </ul>
      </details>
      <details>
        <!-- SECTION II -->
        <summary>Box Model and Common Properties</summary>
        <ul>
          <!-- Step 1 -->
          <li>Set margin and padding on an element with class <code>.box</code>:</li>
          <ul>
            <li>
              First set a background colour for your box to easily see where it starts and finishes.
            </li>
            <li>
              Now use different margin and padding syntaxes - 4-value syntax, 2-value syntax and 1-value syntax. Use pixels as units for margin and padding but do not hesitate to try out other types of units including <code>em</code> and <code>%</code>.
            </li>
          </ul>
          <!-- Step 2 -->
          <li>Practice setting width and height:</li>
          <ul>
            <li>
              Set width and height using different dimension units: <code>px, rem, vh, vw.</code> <code>vh</code> stands for viewport height, and <code>vw</code> stands for viewport width.
            </li>
            <li>
              Observe how the third box retains height styled via the style attribute. Why is this? Force your CSS rules to take precedence using the <code>!important</code> operator.
              <div style="font-style: italic; font-size: small;">
                This is becaise within the <code>index.html</code> the tags for that specific box sets a height, and as a result overrides the stylings set in <code>index.css</code>.
              </div>
            </li>
            <li>
              Try resizing the browser window while the box size depends on the <code>vw</code> and <code>vh</code> units. What can you observe?
              <div style="font-style: italic; font-size: small;">
                The box size varies based with viewport(browser window) size changing. This is because in <code>index.css</code> the height and width is set to dimensions related to the viewport with the use of <code>vh</code> and <code>vw</code>.
              </div>
            </li>
          </ul>
          <!-- Step 3 -->
          <li>Practice adding a border:</li>
          <ul>
            <li>
              Set a border on the .box element: try 2 or 3 different border styles and colors
            </li>
            <li>
              Make the border 10px thick and solid, and observe how thickness of the border moves surrounding elements in each direction.
            </li>
          </ul>
          <!-- Step 4 -->
          <li>The box-sizing property:</li>
          <ul>
            <li>
              Test the two different values of box-sizing. How do they affect the width and height of the box elements?
              <div style="font-style: italic; font-size: small;">
                <code>box-sizing: border-box</code>: Sets the boxes sizing to originate from the outer corner of border.<br>
                <code>box-sizing: content-box</code>: Sets the boxes sizing to originate from inner corner of border.
              </div>
            </li>
          </ul>
          <!-- Step 5 -->
          <li>
            Use overflow to define the behaviour when content does not fit inside its container:
          </li>
          <ul>
            <li>
              Make text overflow outside of the element by setting width and height to smaller values, so the text in the second box goes over the box borders.
            </li>
            <li>
              Set the overflow CSS rule for the <code>.box</code> class - test several different values. How do they affect the box?
              <div style="font-style: italic; font-size: small;">
                <code>overflow: visible</code>: Allows overflowing text to be visible.<br>
                <code>overflow: hidden</code>: Hides any overflowing text.<br>
                <code>overflow: scroll</code>: Allows the boxes to be scrollable.<br>
                <code>overflow: auto</code>: Allows boxes to be scrollable <b>independently</b> when necessary, instead of making all boxes scrollable.
              </div>     
            </li>
          </ul>
          <!-- Step 6 -->
          <li>Add an outline:</li>
          <ul>
            <li>
              Set a wide outline (<code>10px</code>) on the <code>.box</code>. Observe that setting the outline does not shift the other elements around, like with borders.
            </li>
          </ul>
          <!-- Step 7 -->
          <li>Use border-radius to affect the box corners:</li>
          <ul>
            <li>
              Set <code>border-radius</code> on the <code>.box</code> element. Start by trying out different values expressed in pixels, e.g. <code>20px</code> or <code>ems</code>, e.g. <code>1em</code>.
            </li>
            <li>
              Setting <code>border-radius</code> to 50% together with width=height will make the element look like a circle. If the width is different from height, then the element will become an oval. 
            </li>
            <li>
              Increase the padding so the text inside the box is not cut off by the border corners.
            </li>
          </ul>
          <!-- Step 8 -->
          <li>Adding a background image:</li>
          <ul>
            <li>
              Set a background image for the box using the background property. Image to use is located in: <code>./assets/images/img1.png</code> file.
            </li>
            <li>
              Set <code>background-size</code> to `cover`. Also experiment with other values.
            </li>
            <li>
              Set <code>background-repeat</code> to `no-repeat`. Also experiment with other values.
            </li>
            <li>
              Set <code>background-position</code> to `center`. Also experiment with other values.
            </li>
          </ul>
          <img alt="Exercise 2 - Box Model and Common Properties - 1" src="/Lab Screenshots/Exercise2/Exercise2-2-1,2,3,4,5,6,7,8-1.png">
          <img alt="Exercise 2 - Box Model and Common Properties - 2" src="/Lab Screenshots/Exercise2/Exercise2-2-1,2,3,4,5,6,7,8-2.png">
        </ul>
      </details>
      <details>
        <!-- SECTION III -->
        <summary>Positioning</summary>
        <ul>
          <!-- Step 1 -->
          <li>Absolute positioning:</li>
          <ul>
            <li>
              Use CSS to apply absolute position on the <code>.position-absolute</code> class
            </li>
            <li>
              On the same class, add a <code>top</code> position of 0 to fix this element to the top of the page (also try changing <code>top</code> to <code>bottom</code>).
            </li>
            <li>
              Add a background color to make finding the absolutely positioned elements easier.
            </li>
          </ul>
          <!-- Step 2 -->
          <li>Relative positioning for absolute elements:</li>
          <ul>
            <li>
              Set relative position on the <code>.position-relative</code> class.
            </li>
            <li>
              Add a different background colour to the relatively positioned container.
            </li>
            <li>
              How is absolute positioning within relative different from absolute positioning that is outside of relative?
              <div style="font-style: italic; font-size: small;">
                the absolute positioning within a relative positions it in relation to to the container's absolute. Absolute outside the container, without any relative tags follows the absolute of the HTML.
              </div>
            </li>
            <li>
              Add a <code>left</code> position value to the <code>.position-absolute</code> class and observe the difference. Add a right position value as well – what does this do?
              <div style="font-style: italic; font-size: small;">
                Adding a <code>left: 0;</code> moves the div to the left side of the page against the wall. Adding <code>right: 0;</code> to the style stretches the div across the whole page, left to right.
              </div>
            </li>
          </ul>
          <!-- Step 3 -->
          <li>Sticky positioning:</li>
          <ul>
            <li>
              Set sticky position on <code>.position-sticky</code> class and scroll the page to see it work.
            </li>
            <li>
              Add a different background colour to the <code>.position-sticky</code> class.
            </li>
            <li>
              Set a top position value to change where the element ‘sticks’ to.
            </li>
          </ul>
          <img alt="Exercise 2 - Positioning - 1" src="/Lab Screenshots/Exercise2/Exercise2-3-1,2,3-1.png">
          <img alt="Exercise 2 - Positioning - 2" src="/Lab Screenshots/Exercise2/Exercise2-3-1,2,3-2.gif">
        </ul>
      </details>
      <details>
        <!-- SECTION IV -->
        <summary>Styling Text</summary>
        <ul>
          <!-- Step 1 -->
          <li>Color</li>
          <ul>
            <li>
              Set a font color using the <code>color</code> CSS rule on the <code>.text-style</code> class.
            </li>
          </ul>
          <!-- Step 2 -->
          <li>Font Size</li>
          <ul>
            <li>
              Add a font-size CSS rule to the <code>.text-style</code> class. Experiment with different sizes and units.
            </li>
          </ul>
          <!-- Step 3 -->
          <li>Line Height</li>
          <ul>
            <li>
              Add a <code>line-height</code> CSS rule to the <code>.text-style</code> class. Experiment with different values and units – also with omitting the units.
            </li>
          </ul>
          <!-- Step 4 -->
          <li>Font Weight</li>
          <ul>
            <li>
              add a <code>font-weight</code> CSS rule to the <code>.text-style</code> class. Experiment setting the font weight with both keyword and number values, e.g. bold and 800 (choose from 100, 200, 300, 400, 500, 600, 700, 800, 900).
            </li>
          </ul>
          <!-- Step 5 -->
          <li>Importing Fonts and <code>font-family</code></li>
          <ul>
            <li>
              Visit <code>https://fonts.google.com/</code> and find a font that you like.
            </li>
            <li>
              Click ‘Select this style’ on several variations of the same font (see screenshot below). Selecting font styles is used to save the bandwidth for the user, if we do not intend to use certain styles of the font then we should not select them.
            </ln>
            <ln>
              Select the </code>&lt;link&gt;</code> option from ‘Use on the web’ and copy the stylesheet code into the </code>&lt;head&gt;</code> section of </code>index.html</code>.
            </ln>
            <ln>
              Copy the <code>font-family</code> CSS rule into your <code>.text-style</code>. The <code>sans-serif</code> part of that rule activates in the situation where the previous font could not be loaded, e.g. we misspelled ‘Roboto’ or there is no internet connection. In that case, the browser will load the default <code>sans-serif</code> font.
            </ln>
          </ul>
          <!-- Step 6 -->
          <li>Text Manipulation</li>
          <ul>
            <li>
              <b>Text Alignment</b> - add a <code>text-align</code> CSS rule to the <code>.text-style</code> class. Experiment with different values.
            </li>
            <li>
              <b>Letter Spacing</b> - Add a <code>letter-spacing</code> CSS rule to the <code>.text-style</code> class. Experiment with different values using <code>px</code> units.
            </li>
            <li>
              <b>Word Spacing</b> - Add a <code>word-spacing</code> CSS rule to the <code>.text-style</code> class. Experiment with different values using <code>px</code> units.
            </li>
            <li>
              <b>Text Transformation</b> - Add a <code>text-transform</code> CSS rule to the <code>.text-style</code> class. Experiment with different values using <code>px</code> units.
            </li>
            <li>
              <b>Text Decoration</b> - Add a <code>text-decoration</code> CSS rule to the <code>.text-style</code> class. Experiment with different values using <code>px</code> units.
            </li>
          </ul>
          <img alt="Exercise 2 - Styling Text - 1" src="/Lab Screenshots/Exercise2/Exercise2-4-1,2,3,4,5,6-1.png">
          <img alt="Exercise 2 - Styling Text - 2" src="/Lab Screenshots/Exercise2/Exercise2-4-1,2,3,4,5,6-2.png">
        </ul>
      </details>
      <details>
        <!-- SECTION V -->
        <summary>Styling links</summary>
        <ul>
          <!-- Step 1 -->
          <li>
            <code>a:link</code> Style all of the links in index.html in their basic (default) state by:
          </li>
          <ul>
            <li>
              Setting a font <code>color</code>.
            </li>
            <li>
              Modifying the <code>font-size</code>, <code>font-weight</code>, and <code>text-decoration</code> for your links.
            </li>
          </ul>
          <!-- Step 2 -->
          <li>
          <code>a:hover</code>, <code>a:active</code>, <code>a:focus</code> Style all of these ‘active’ links differently to default links by:
          </li>
          <ul>
            <li>
              Overriding the <code>color</code> with a darker shade.
            </li>
            <li>
              Using a different <code>text-decoration</code> value.
            </li>
          </ul>
          <!-- Step 3 -->
          <li>
            <code>a:visited</code> Many websites do not apply special styling to visited links. Style yours differently by:
          </li>
          <ul>
            <li>
              Overriding the <code>color</code>.
            </li>
            <li>
              Using a different <code>font-style</code> value.
            </li>
          </ul>
          <div style="font-style: italic; font-size: small;">
            <code>font-style</code> Does not work due to browsers wanting to protect the users privacy. In the early days this was used by malicious websites in conjunction with JavaScript to figure out what website the user has visited.
          </div>
          <img alt="Exercise 2 - Syling Links - 1" src="/Lab Screenshots/Exercise2/Exercise2-5-1,2,3-1.png">
          <img alt="Exercise 2 - Syling Links - 2" src="/Lab Screenshots/Exercise2/Exercise2-5-1,2,3-2.gif">
        </ul>
      </details>
      <details>
        <!-- SECTION VI -->
        <summary>calc()</summary>
        <ul>
          <!-- Step 1 -->
          <li>
            Add a new fixed width rule: <code>width: 100vw;</code> to the <code>.calc-style</code> class. The element should now overflow outside of the screen.
          </li>
          <ul>
            <li>
              Add a background colour to the <code>.calc-style</code> class to easily see its boundaries.
            </li>
            <li>
              Add a new rule: <code>width: calc(100vw - 100px);</code> to the <code>.calc-style</code> class. Now the element occupies <code>100px</code> less than the entire width of the screen.
            </li>
          </ul>
          <!-- Step 2 -->
          <li>
            Create a new selector for the <code>.fixed-width-col</code> class to set its width to <code>350px</code> and <code>display: inline-block;</code>.
          </li>
          <!-- Step 3 -->
          <li>
            Create a second selector for the <code>.fluid-col</code> class  and set <code>display: inline-block;</code> on it as well. This will display the <code>fixed-width-col</code> stacked on top of the <code>fluid-col</code>.
          </li>
          <ul>
            <li>
              Use <codle>calc()</code> to subtract the width of the <code>fixed-width-col</code> from the total page width and set a dynamically calculated width for the <code>fluid-col</code> so that the two elements appear side-by-side.
            </li>
          </ul>
          <img alt="Exercise 2 - calc() - 1" src="/Lab Screenshots/Exercise2/Exercise2-6-1,2,3-1.png">
          <img alt="Exercise 2 - calc() - 2" src="/Lab Screenshots/Exercise2/Exercise2-6-1,2,3-2.png">
        </ul>
      </details>
    </ul>
  </details>
</div>
