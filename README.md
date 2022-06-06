# HTML Course & Project plan

1. Introduction

   - what is HTML? Why HTML? History of HTML
   - Advantages, Disadvantages of HTML
   - Content, Tag, Element, Attribute
   - Types of Tags -> container tag/pair tag, empty tag
   - Basic structure of HTML

     ```html
     <!DOCTYPE html>
     <html lang="en">
       <head>
         <meta charset="UTF-8" />
         <meta http-equiv="X-UA-Compatible" content="IE=edge" />
         <meta
           name="viewport"
           content="width=device-width, initial-scale=1.0"
         />
         <title>Document</title>
       </head>
       <body></body>
     </html>
     ```

   - Inside Head tags (add title, link css file)
     `<title>Document</title>`
   - Comments (add comments for all sections)

   ```html
   <!-- Header section starts  -->
   <!-- Header section ends  -->

   <!-- Summary section starts  -->
   <!-- Summary section ends  -->

   <!-- Employment history/experience section starts  -->
   <!-- Employment history/experience section ends  -->

   <!-- Education section starts  -->
   <!-- Education section ends  -->

   <!-- Skills section starts  -->
   <!-- Skills section ends  -->

   <!-- Contact section starts  -->
   <!-- Contact section ends  -->

   <!-- Footer section starts  -->
   <!-- Footer section ends  -->
   ```

   - HTML Validation (check validity)

2. Typography

   - Headings, Horizontal rule, Line break

   ```html
   <!-- Header section starts  -->
   <h1>Anisul Islam</h1>
   <hr />
   <!-- Header section ends  -->

   <!-- Summary section starts  -->
   <h2>Summary</h2>
   <!-- Summary section ends  -->

   <!-- Employment history/experience section starts  -->
   <h2>Employment History</h2>
   <!-- Employment history/experience section ends  -->

   <!-- Education section starts  -->
   <h2>Education</h2>
   <!-- Education section ends  -->

   <!-- Skills section starts  -->
   <h2>Skills</h2>
   <!-- skills section ends  -->

   <!-- Contact section starts  -->
   <h2>Contact</h2>
   <!-- Contact section ends  -->

   <!-- Footer section starts  -->
   <!-- Footer section ends  -->
   ```

   - Paragraphs

     ```html
     <!-- Summary section starts  -->
     <h2>Summary</h2>
     <p>
       A Software, web & cloud development graduate, an experienced full-stack
       software developer with a diverse and interesting technical background.
       Last 8 years trained millions of students in JavaScript, TypeScript,
       React.js, REST API, C++, Python, Java and many other subjects related to
       software development through a YouTube channel where 1,800 videos were
       uploaded and gained 3,33,000 subscribers.
     </p>
     <!-- Summary section ends  -->

     <!-- footer starts   -->
     <p>Developed with love by Anisul Islam</p>
     <p>Copyright copy 2022</p>
     <!-- footer ends  -->
     ```

   - Text-formatting tags -> b, strong, i, em, u, span, mark, sup, sub, pre, del

     - add strong tag inside header `<strong>Software Developer</strong>`
     - add italic tag inside h2 tag of all other sections `<h2><em> Summary </em></h2>`

   - Entity, Symbol & Emoji
     - add entity to footer
     ```html
     <!-- footer starts (entity)  -->
     <p>Developed with &hearts; by Anisul Islam</p>
     <p>Copyright &copy;2022</p>
     <!-- footer ends  -->
     ```

3. List, Link, Images, Frames, Media

   - List: Ordered List, Unordered List, Definition List

     ```html
     <!-- experience / Employment History starts (list) -->
     <h2><em>Employment History</em></h2>
     <ol>
       <li>
         <b> Junior Software Developer at M-Files </b>
         <span> | DEC 2021 - JAN 2022 </span>
         <p>Developed & tested M-Files React Metadata Card</p>
       </li>

       <li>
         <b> Research Assistant, Tampere University, Tampere </b>
         <span> | Nov 2020 - JAN 2021 </span>
         <p>
           developed a full-stack website for the users to explore and select
           open-source software. Technologies used: JavaScript, React, Node,
           Express, MongoDB.
         </p>
       </li>

       <li>
         <b> Project Team Leader, Demola Global </b>
         <span> | Nov 2020 - JAN 2021 </span>
         <p>
           Led and delivered a project to a client, M-Files to update the core
           application.
         </p>
         <p>
           Prepared & conducted user tests and reported findings to the client,
           M-Files.
         </p>
       </li>
     </ol>
     <!-- experience / Employment History  ends  -->

     <!-- education starts  -->
     <section>
       <h2><em>Education</em></h2>
       <ul>
         <li>
           <strong>M.Sc. in Software, Web & Cloud</strong>
           <p>Tampere University, Tampere, Finland</p>
           <p>Grading Point: 3.79/5</p>
         </li>
         <li>
           <strong>B.Sc. in CSE</strong>
           <p>Leasing University, Sylhet, Bangladesh</p>
           <p>Grading Point: 3.92/4</p>
         </li>
       </ul>
     </section>
     <!-- education ends  -->
     ```

   - Link

     ```html
     <!--heading starts  -->
     <h1>Anisul Islam</h1>
     <strong>Software Developer</strong>
     <p>
       <a href="https://www.studywithanis.com/" target="_blank">Website</a>
       <a href="https://www.linkedin.com/in/anisul2020/" target="_blank"
         >LinkedIn</a
       >
       <a href="https://github.com/anisul-Islam" target="_blank">GitHub</a>
       <a href="https://www.facebook.com/studywithanis" target="_blank"
         >Facebook Page</a
       >
       <a href="tel:+8801710444700" target="_blank">Phone</a>
       <a href="mailto:anisul2010s@yahoo.co.uk" target="_blank">Email</a>
     </p>

     <hr />
     <!--heading ends -->
     ```

   - Image

     ```html
     <!--heading starts -->
     <h1>Anisul Islam</h1>
     <img src="/images/cv_photo.png" alt="cv_photo" /> <br />
     <strong>Software Developer</strong>
     ```

   - Frames (add a youtube video / map using iframe)

     ```html
     <!-- contact starts  -->
     <h2><em>Contact</em></h2>
     <iframe
       src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1905.6688119905182!2d23.85106535205227!3d61.46907804459599!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x468edf995e12d029%3A0x2bbe7f2b9c9dd9d6!2sPyykkiojankatu%202%2C%2033710%20Tampere!5e0!3m2!1sen!2sfi!4v1654488270841!5m2!1sen!2sfi"
       width="600"
       height="450"
       style="border: 0"
       allowfullscreen=""
       loading="lazy"
       referrerpolicy="no-referrer-when-downgrade"
     ></iframe>
     <!-- contact ends  -->
     ```

   - Audio, Video

4. Table, Form

   - Table example

     ```html
     <!-- skills starts (table)  -->
     <h2><em>Skills</em></h2>
     <table border="1">
       <thead>
         <tr>
           <th>Technologies</th>
           <th>Skill Level</th>
         </tr>
       </thead>
       <tbody>
         <tr>
           <td>C, C++</td>
           <td>★★★★☆</td>
         </tr>
         <tr>
           <td>Java</td>
           <td>★★★★☆</td>
         </tr>
       </tbody>
     </table>
     ```

   - Form example

     - add label, input-text, email, submit, button, text-area
     - required

     ```html
     <!-- contact starts  -->
     <h2><em>Contact</em></h2>
     <form>
       <div>
         <label for="name">Name</label>
         <input type="text" id="name" required />
       </div>
       <br />

       <div>
         <label for="email">Email</label>
         <input type="email" id="email" required />
       </div>
       <br />

       <div>
         <span>Gender: </span>
         <input type="radio" name="gender" id="male" />
         <label for="male">Male</label>
         <input type="radio" name="gender" id="female" />
         <label for="female">Female</label>
       </div>
       <br />

       <div>
         <label for="occupation">Occupation</label>
         <select name="" id="occupation">
           <option value="student">student</option>
           <option value="teacher">teacher</option>
           <option value="others">others</option>
         </select>
       </div>
       <br />

       <div>
         <label for="message">Message</label> <br />
         <textarea id="message" required></textarea>
       </div>
       <br />

       <div>
         <button type="submit">SEND MESSAGE</button>
       </div>
     </form>a

     <!-- iframe here  -->
     <!-- contact ends  -->
     ```

5. Semantic HTML

   - HTML5 Semantic elements: <header> <nav> <main> <article> <aside> <section> <footer> <figure> <figcaption> <details> <summary> <mark> <time>

6. Web accessibility

   - what is web accessibility?
   - how to test? - lighthouse, axe tool
   - how to make website accessible?

7. how to add basic CSS style in HTML
   ```html
   <style>
     header {
       text-align: center;
     }
     a {
       font-size: 3rem;
       margin: 1rem 1rem 0 0;
     }
   </style>
   ```
