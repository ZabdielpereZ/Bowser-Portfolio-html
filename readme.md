# Learning Objectives

## Create a Well-Structured HTML Document:
**Comprehend the basic syntax of HTML, including tags, elements, and attributes.
Learn to construct a well-organized HTML document with essential elements like DOCTYPE, html, head, and body.**

**Use Basic and Advanced HTML Elements Effectively:
Apply basic HTML elements such as headings (h1-h6), paragraphs (p), text formatting (b, strong, i, em), lists (ul, ol, li), hyperlinks (a), images (img), line breaks (br), and horizontal rules (hr).
Utilize advanced text elements, including tables (table, th, tr, td), quotations (blockquote, q), code snippets (code, pre), and understand their significance.**

**Incorporate Multimedia Elements:
Embed multimedia elements such as images, audio, and video into web pages.
Bonus: Integrate YouTube videos to enhance the visual content.**

**Leverage Semantic HTML5 Elements:
Understand the importance of semantic HTML5 elements in structuring web content.
Implement semantic elements like header, footer, article, section, nav, and aside effectively.**

**Build Interactive HTML Forms:
Create interactive HTML forms with various input elements, including text fields, passwords, checkboxes, radio buttons, and submit buttons.
Apply attributes like name, placeholder, and autocomplete to enhance form functionality.**

**Implement Form Validation and Accessibility:
Explore HTML5 form validation attributes for validating user inputs.
Consider accessibility principles when designing forms to ensure inclusivity.**

## Start by creating html file
**Name the File:**
**idex.html** 
**use command: !**
**you should see the following**
```  
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  
</body>
</html>
```
##### from here you can freely create your html file and implement the following.

## Head/background image: 

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>King Bowser - Web Resume</title>
    <!-- Link Element (External CSS File) -->
    <link rel="stylesheet" href="css/resume.css">

    <!-- back-ground image using (internal CSS) style -->
    <style>
        body{ 
            background-image: url(https://th.bing.com/th/id/R.a11401268551ea3eaac68cf577bab7e6?rik=LmdyQH59CQApzw&pid=ImgRaw&r=0);
        }
    </style>
</head>
```
## Header/Intro Video:
```
<body>
    <!-- Profile Header -->
    <header>
        <h2><em>Video Introduction</em></h2>
        <video width="420" height="240" controls>
            <source src="bowser_intro_video.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <img class="profile" src="images.png/bowser.jpg" alt="Professional profile picture of Bowser.">
        <h1 class="name">King Bowser</h1>
        <p>Welcome to my professional web resume.</p>
    </header>
```
## Navigation Bar/ Link_to_me(Contact info):
```
    <!-- Navigation Bar  -->
    <nav>
        <h2>Contact</h2>
        <p>Email: KoopaKing@gmail.com</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/King Bowser">King Bowser</a></p>
        <a href="link_to_me.html" target="_blank">Link To Me</a>
    </nav>
```
## Table(Section) with skills:
```
  <!-- Table with (table boarder, table header (th), table row (tr), table data (td)) -->
    <section>
        <h2>Skills</h2>
        <table border="1">
            <tr>
                <th>Technology</th>
                <th>Proficiency</th>
                <th>Years of Experience</th>
            </tr>
            <tr>
                <td>HTML/CSS</td>
                <td>Expert</td>
                <td>1</td>
            </tr>
            <tr>
                <td>JavaScript</td>
                <td>Intermediate</td>
                <td>1</td>
            </tr>
            <!-- Add more skills as needed -->
        </table>
    </section>
```
**outcome:**
#### Table
```
| Technology | Proficiency | Years of Experience |
--------------------------------------------------
| HTML/CSS	 | Expert	   | 1           |
--------------------------------------------------
| JavaScript | Intermediate	|   1            |
--------------------------------------------------
```


## (ul)Unordered List(article) Education:
```
    <!-- Listing education with Unordered lists -->
    <article>
        <h2>Education</h2>
        <ul>
            <li><a href="https://universitywebsite.com"><strong>Mushroom Kingdom University</strong></a>, Bachelor's Degree, June/28/2002</li>
            <!-- Add more educational qualifications as needed -->
        </ul>
    </article>
```
## Work Experience(article):
```
    <!-- Work experience header  -->
    <article>
        <h2>Work Experience</h2>
        <p><strong>Ruler of Mushroom Kingdom</strong>, Nintendo <em>(1985-2024)</em></p>
        <!-- Add more experiences as needed -->
    </article>
```
## Testimonials(aside) "blockquote": 
```
    <!-- Testimonials using blockquote -->
    <aside>
        <h2>Testimonials</h2>
        <blockquote cite="http://example.com/fiona-feedback">
            "King Bowser is the best King of all the 
            land."
        </blockquote>
        <p>- Shy Guy #023, Project Manager at Koopa Troop Task Force </p>
    </aside>
```
## Recent projects(section) &lt(less than) &gt(greater than):
```
    <h2>Recent Projects</h2>
    <section>
        <!-- Coding Projects Section -->
        <p>Project Name: Website Redesign</p>
        <pre><code>&lt;!-- HTML structure of the redesigned homepage --&gt;
            &lt;div class="container"&gt;
    &lt;header&gt;...&lt;/header&gt;
    &lt;nav&gt;...&lt;/nav&gt;
    &lt;main&gt;...&lt;/main&gt;
    &lt;footer&gt;...&lt;/footer&gt;
&lt;/div&gt;
</code></pre>
    </section>
```
## Audio/mp3:
```
    <!-- audio <source src="" type="audio/mp3"> -->
    <section>
        <h2>Peaches song ❤️</h2>
        <audio controls>
            <source src="Bowser - Peaches (Official Music Video)  The Super Mario Bros. Movie.mp3" type="audio/mp3">
            Your browser does not support the audio element.
        </audio>
    </section>
```
## Video/mp4:
```
    <!-- video <source src="" type="video/mp4">   -->
    <section>
        <h2>Project Highlights for Smash Ultimate</h2>
        <video width="420" height="240" controls>
            <source src="Bowser-Montage.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </section>
```
## Embeding Youtube Video:
```
    <!-- youtube video <iframe src="https://www.youtube.com/embed/YOUR_YOUTUBE_VIDEO" -->
    <section>
        <h2>Tutorials & Talks</h2>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/VYpqKBAN6zQ" frameborder="5" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </section>
```
## Adding Contact me button:
```
    <!-- Add a button  -->
     <section>
        <h2>Contact Me</h2>
        <button class="contact-btn">Contact via email</button>
     </section>
     <br/>
```
## Footer/ Copy Right symbol(&copy) / Your Name:
```
    <footer>
        <p>&copy; 2024 King Bowser. All rights reserved.</p>
    </footer>
</body>

</html>
```
## Create a New html File:
**Name the File:**
**link_to_me**


## link_to_me(home page/linked page):
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Linked page</title>
  <style>
    body{ 
        background-image: url(https://th.bing.com/th/id/R.a11401268551ea3eaac68cf577bab7e6?rik=LmdyQH59CQApzw&pid=ImgRaw&r=0);
    }
</style>
</head>
<body>

  <header>
    <nav>
      <a href="index.html">Home</a>
      <a href="link_to_me.html">Linked page</a>
    </nav>
  </header>
```
## Style body(everything) to center:
```
  <!-- styling body to be center and header to be blueviolet; -->
  <body style="text-align:center;">
    <h1 style="color:blueviolet;"> Contact Us</h1>
```
## User input actions (name, email, phone):
```
  <!-- User input for name -->
    <form action="/submit" method="post">
        <label for="name">Name</label>
        <br>
        <input type="text" id="Name" name="name" 
            placeholder="Enter Your Name" required>
    <br><br>

    <!-- User input for email -->
    <form>
        <label for ="user-email">Email</label>
        <br>
        <!-- Email pattern: pattern="[a-z0-9._%+\-]+@[a-z0-9.\-]+\.[a-z]{2,}$" -->
        <input type="email" id="user-email"
        pattern="Enter your Email" required 
        pattern="[a-z0-9._%+\-]+@[a-z0-9.\-]+\.[a-z]{2,}$"
        >
        <br><br>

        <!-- User input for phone -->
        <label for="user-phone">Phone</label>
        <br>
        <!--    
                Pattern reference
                https://www.w3schools.com/tags/att_input_pattern.asp
        -->
        <input type="text" id="user-phone" name="phone" pattern="[0-9]{10}"
        placeholder="Enter your 10 digit phone number">
        <br><br>
```
## Reset/Submit buttons br(break) hr(horizontal rule):
```
 <!-- Reset and submit buttons -->
        <button type="reset">Reset</button>
        <button type="submit">Submit</button>
        <br><br>
        <hr>
        <br>
```
# Schedule Meet Date:
```
        <!-- schedule meet date -->
        <h2><em><label for="schedule">Schedule Meet</label></em></h2>
        <input type="date" min="2024-03-15" max="2024-09-5" id="schedule" name="schedule">
        <br><br>
        <br>
```
## Radio button/aria label reset/submit buttons:
```
    <!-- Radio - user can Choose One option max-->
    <h3><em><label>Select Preferred Contact Method</label></em></h3>
        <input type="radio" id="Phone" name="phone" value="Phone">
        <label for="phone">Phone</label><br>
        <input type="radio" id="email" name="email" value="email">
        <label for="email">Email</label>
        <br><br>
        <hr>

        <!-- textarea to add comments -->
        <h2><em><label for="comments">Additional Comments</label></em></h2>
        <textarea id="comments" name="comments" rows="10" cols="50"
        placeholder="Share your thoughts">
        </textarea>
        <br><br>

        <!-- aria-label reset and submit button -->
        <button type="reset"aria-label="Reset Form">Reset</button>
        <button type="submit"aria-label="Submit Form">Submit</button>
        <br><br>
        <hr>
```
## News letter button checked:
```
        <!-- News letter button label -->
        <label for="newsletter">Subscribe to Newsletter:</label>
        <br>
        <input type="checkbox" id="newsletter" name="newsletter" value="yes" checked>
        <br><br>
```
## Cascading select menu styled red:
```
        <!-- Creating a cascading select menu -->
        <label style="color: rgb(255, 0, 0); " for="category">Category:</label>
        <select id="category" onchange="updateOptions()">
            <option value="guides">Guides</option>
            <option value="tips">Tips</option>
            <option value="articles">Articles</option>
        </select>
    
        <label style="color: rgb(225, 0, 0);" for="games">Games:</label>
        <select id="games">
            <option value="">Please select a category first</option>
            <option value="">Super Mario 64</option>
            <option value="">The Legend of Zelda: Breath of the Wild</option>
            <option value="">The Legend of Zelda: Ocarina of Time</option>
            <option value="">Metroid Prime</option>
            <option value="">Doom Eternal</option>
        </select>
```
## Footer:
```
        <footer>
            <p>&copy; 2024 King Bowser. All rights reserved.</p>
        </footer>
    </form>
</body>
</html> 
```