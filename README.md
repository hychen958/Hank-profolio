Hank's Portfolio
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Welcome to the source code of my personal portfolio website. 
This project showcases my skills as a Full-Stack Developer, 
providing details about me, my skills, projects, 
and a dynamic digital clock feature.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🛠️ Technologies Used
HTML5
CSS3 (with multiple stylesheets for modularity)
base.css: Basic styles and resets.
main.css: Typography, layout, and responsive design.
hp.css: Styles specific to the clock display feature.
JavaScript

hp.js: JavaScript code for the real-time digital clock.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📝 File Descriptions
index.html

The main HTML file with sections for Intro, About Me, Skills, Portfolio, and Contact.
Includes links to external stylesheets and JavaScript files.
base.css

Provides CSS resets, general styles, and responsive layout utilities.
main.css

Defines typography, headings, buttons, and reusable theme styles for the entire site.
hp.css

Custom styles for the clock display section.
hp.js

Implements a real-time digital clock that updates every second.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
⏰ Dynamic Clock Feature
The clock is displayed within the Portfolio section. It's styled with hp.css and functions using hp.js.

Code Example for Clock (hp.js)
javascript
function renderTime() {
    var currentTime = new Date();
    var h = currentTime.getHours();
    var m = currentTime.getMinutes();
    var s = currentTime.getSeconds();

    if (h < 10) h = "0" + h;
    if (m < 10) m = "0" + m;
    if (s < 10) s = "0" + s;

    var myClock = document.getElementById('clockDisplay');
    myClock.textContent = h + ":" + m + ":" + s;
    setTimeout(renderTime, 1000);
}

renderTime();
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🚀 How to Run the Project
Clone the repository:

bash
git clone https://github.com/hychen958/Hank-profolio.git
cd Hank-profolio
Open index.html in your browser:

bash
open index.html
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📧 Contact
Name: Hank Chen
Email: Hychen958@gmail.com
Phone: +1-418-655-9481
