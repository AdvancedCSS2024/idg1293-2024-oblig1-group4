Report

We startet the process by marking up the two screenshots provided to get an idea of how the two pages are structured. 
We outlined the main elements like h1, h2, nav bars, cards, inputs and so on. We then decided on which page we wanted to implement.

We faced some issues in the first phase as we ended up having different scss files, which later caused complications with GitHub 
when merging. At one point we weren't able to solve conflicts in the browser and needed to solve several conflicts locally. 
With some help from one of the teachers in web development we managed to understand the process of commiting, pushing and pulling 
from GitHub, and from then on we were able to commit, merge and solve conflicts to make progress on the project. 

Even though the assignment stated for us to create elements first, we found it easier to work on the seperate pages and then 
link the elements to the demo page. We wrote most of the code for our elements in the common.scss file with some adjustments to 
the seperate pages and the demo page in the style.scss file.

We decided insert colors from the finn.no design system as variables stored in the common.scss file.
We also copied the spescific finn.no font-faces by copying from the source code.

How the main page was implemented:

* 

How the login page was implimented:

* The page was divided into two cards. The login card was created first in HTML, but edited to the right 
with flex-direction: row-reverse; in SCSS
* The login card elements were placed vertically with flex-direction: column;
* Inputs and buttons were styled to match the finn.no login page
* Links were styled according to the page design
* Padding and margin were edited where needed
* The eye-icon in the password input and the information icon weren't added due to lack of time