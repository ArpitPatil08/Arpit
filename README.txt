====================================================
  GAMING PORTFOLIO — README & SETUP GUIDE
====================================================

FOLDER STRUCTURE
----------------
portfolio/
│
├── index.html          ← Home page (start here)
├── about.html          ← About me page
├── qualifications.html ← Education and skills
├── interests.html      ← Hobbies and interests
├── certifications.html ← Courses and certificates
├── contact.html        ← Contact info and links
│
├── style.css           ← ALL styling lives here
│
└── images/             ← Put ALL your photos here
    ├── photo.jpg           (your profile photo)
    ├── project1.jpg        (gallery image 1)
    ├── project2.jpg        (gallery image 2)
    └── cert-example.jpg    (certificate image)


HOW TO OPEN THE WEBSITE
------------------------
1. Double-click  index.html  to open it in a browser.
   (No server or internet needed for local testing.)


HOW TO EDIT YOUR NAME EVERYWHERE
----------------------------------
Search for "Your Name" across all files and replace
with your actual name. You can use VS Code's
"Find in Files" (Ctrl+Shift+H) to do it all at once.


HOW TO ADD YOUR PHOTO (index.html)
------------------------------------
1. Save your photo as  photo.jpg  in the portfolio folder.
2. Open index.html.
3. Find this line and UNCOMMENT it (remove <!-- and -->):
      <!-- <img src="photo.jpg" alt="Your Name" /> -->
4. Delete the <div class="photo-placeholder"> block below it.


HOW TO ADD GALLERY IMAGES
---------------------------
1. Create a folder called  images/  inside portfolio/.
2. Save your images there (e.g. images/project1.jpg).
3. Open any HTML file with a gallery section.
4. Find a gallery-item block and uncomment the <img> line:
      <!-- <img src="images/project1.jpg" alt="Project 1" /> -->
5. Delete the <div class="img-placeholder"> block.
6. To add more images, copy a whole <div class="gallery-item">
   block and change the src and alt values.


HOW TO CHANGE THE NEON COLOR
------------------------------
Open  style.css  and find this line near the top:
    --neon: #00ff88;
Change #00ff88 to any color you like, for example:
    --neon: #00cfff;   ← neon blue
    --neon: #ff00ff;   ← neon pink / magenta
    --neon: #ffff00;   ← neon yellow


HOW TO CHANGE THE BACKGROUND COLOR
-------------------------------------
In style.css, find:
    --bg-color: #0a0a0a;
Change to any dark color, e.g.:
    --bg-color: #050510;   ← very dark blue-black


ADDING A NEW PAGE
------------------
1. Copy any existing HTML file, e.g. copy about.html.
2. Rename it, e.g. projects.html.
3. Change the <title> tag.
4. Update the nav: add class="active" to the new link.
5. Add a new <li> in the nav of EVERY other HTML file too.
6. Write your content inside <main class="container">.


TIPS FOR BEGINNERS
-------------------
- Always save files before refreshing the browser.
- Use VS Code (free) for the best editing experience.
- The browser DevTools (F12) help you inspect any element.
- Comments in code start with <!-- and end with --> (HTML)
  or /* and */ (CSS). They explain what each part does.
- Every page uses the SAME style.css, so changing one
  thing there changes it on all pages automatically.

====================================================
