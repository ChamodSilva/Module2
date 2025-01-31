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
            This should open http://127.0.0.1:5500/index.html in your browser.
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


<div style="border: 12px solid #ccc; padding: 10px; margin-bottom: 10px;">
  <details>
    <summary>Exercise2</summary>

    I. Create a JSON object variable for a book. The book should have a title, description, author, and number of pages.
    * ![Screenshot of Exercise6-1](/Lab%20Screenshots/Exercise6/Exercise6-1.png)

  </details>
</div>
