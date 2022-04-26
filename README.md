# NLP4RE Workshop Website

The NLP4RE website uses basic HTML, CSS, and JS. This allows for easy editing and maintenance on any system. Simply download the files, load the local index.html into your web browser, and edit the local files. No compiling or processing needed. It is a scrolling single-page website, and it scales to smaller devices by moving content around.

The website is broken up into sections. Here is a brief description of each, with some notes for how to edit them
- Header
  - In this section you can edit the top nav menu items. Make sure there are matching page elements with the correct IDs so that clicking the menu items will scroll the page to the correct location.
  - You also edit the workshop name and important details such as the workshop date, and deadlines.
- Home
  - Workshop Overview and Contributions are here.
  - Update the REFSQ website link in this section.
- Call for Papers
  - This is where you would edit the types of papers accepted at the workshop.
  - Good to double check the links in this section to make sure they are still working.
- Keynote
  - You need to upload a photo `assets/images/keynote-profile.jpeg` before working on this section. Match the size of the existing `keynote-profile.png` if you want similar sizing on the website. Otherwise, adjust the width element in the HTML.
- Program
  - This section has rather important styling, so be carfeul what you copy-paste and delete when changing the schedule listed here.
  - There is a "click to show/hide" functionality available for this section, but it is commented out. You could use this space to add the abstracts or links to pre-prints, etc.
- Video
  - There is a commented-out section to include a video. You may consider making and adding such a thing to increase engagement with the workshop.
- Team
  - This is perhaps the most finicky section. Choosing the icons for contact and socials, as well as sizing the people such that they fit nicely on most screen sizes. It is recommended to keep the settings as they currently are. If you have more or less people, you will have to play with how many people are in each "row".
  - The available contact icons are not so many. You can search the CSS for a full list, but there are also a set of commented-out icon names available at the top of the organisation section.
  - The Program Committee is easy to change. You just need the names and affiliations of each member, and set them between the `li` tags. This is easy to automate with a simple text-editor and some hotkeys to paste the `li`s at the beginning and end.
  - The Paste Years footer should be updated to include THIS year, after the existing years. This is an easy copy-paste and change of the URL.

Other Notes
- This website was purchased even though it was likely not necessary (this workshop is not a for-profit venue). The license details are available in this repository in case they are requested by the issuing company
