<h1>Site Overview</h1>

This project is a fictional university, the North West Technological University. It is intended to serve as a pastiche project, taking inspiration from real-life academic facilites. As I pursue my own academic goals I felt it could be an interesting project to try to design my own university website, applying the knowledge I've acquired so far in the course.

It's a website designed to market and promote a university, showcasing its facilities, programs and support services. It's designed to highlight what the university has to offer, with the express intention of engaging with prospective students.

In order to achieve this I felt that the website needed a very clean and clear visual, with descriptive links, a facade that is easily navigable with an intuitive layout. As with the nature of the industry I wanted to keep it professional and meaningful, so a relatively simple, clean, but efficient design was important.

<h1>Planning Stage</h1>

<h2>Identifying a Target Audience</h2>

<li>Prospective Students who want to go to a technological university</li>
<li>Parents who can assess the credibility, expertise and value of the university<li>
<li>Users who are curious as to what courses the university offers</li>

<h1>User Stories</h1>
<h2>First-time Visitors</h2>

<li>Users should see immediate information on the subject</li>
<li>The website should be easy to navigate</li>
<li>The website should have a contact page where users can acquire the information they need</li>

<h1>Design & Features</h1>
<h2>Colours and Fonts</h2>

With respect to the colourway adopted for the project, I elicited understated and quieter tones partially lent from a university I attended in the past - namely NUI Maynooth https://www.maynoothuniversity.ie/. The teal #006778 and lighter #f5f8f8 notes sustained throughout the project. They contrasted well and also worked nicely with the images on each of the pages. That said, I think the overall effect gives too much to the ligher side of things, so this had to be offset by a darker #333.

The font family for the project was Arial, Helvetica, sans-serif. The Chrome browser rendered Arial on inspecting the Developer console. The font seemed to me straightforward, unfussy, readable, and what the website required, it being academic-based. This was also something I didn't overthink too much.

<h2>Navigation, Main Pages & Footer</h2>

The navigation menu holds 6 links, with a logo that actively brings a user back to the Home page. I felt it more authentic to find a logo for the navigation so this was found at https://iconscout.com/. I needed to wrap the logo image in an <a> tag to allow returning Home from the other links.

The Home page gives an overview of the university with a couple of buttons to explore courses and tell the user about it. Both buttons bring a user to the Courses page and About page respectively.

There is a highlights section with nested classes, utilising a CSS grid display of cards containing images. There is a 250px minimum inserted into the grid to ensure it collapses to a single column on smaller screens. This occurs again in the Courses page. The images were acquired from pixabay.com.

The Hero section of images also uses CSS grid display on repeat with 1 shared fraction of space repeated (2x2 images)

The Admissions page follows a similar layout and technique with a target="\_blank" forwarding to an external CAO application page.

The Footer section also employed CSS grid display, again with grid-template-column minmax to reduce down on a mobile screen. Once understood and learned, I found this technique very useful, which is why it was repeated on a lot of the pages.

Apart from varying different elements in the stylesheets, like colours, line-heights and margins, the techniques used were repeated to good effect through all the pages. The buttons responded to the next page and there was a nice flow from Home to Contact pages. At times I felt this was unadventurous, but it rendered well and served its designed purpose.
