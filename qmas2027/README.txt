QUANTUM MATTER ACROSS SCALES - conference website (aqua version)
=================================================

The whole site is one file: index.html. Open it in a browser to preview it.

TO PUBLISH
Upload the whole folder (index.html + images/) to any web hosting: the
university web space, GitHub Pages, Netlify, etc. No server-side software
is needed.

TO EDIT THE TEXT
Open index.html in any text editor. Each page is a <section> with an id
(page-home, page-speakers, ...; the menu links use #home, speakers, registration, programme, venue, accommodation, organizers,
sponsors). Everything still in [square brackets] or marked "placeholder" or
"to be announced" needs real content:
  - registration deadline and registration form link
  - programme times and titles
  - accommodation
  - the short description on the Home page

TO ADD THE SPONSOR LOGOS
Copy the logos into images/ and, in the "sponsors" section, add for each one:
   <img src="images/unipd-logo.png" alt="University of Padova" height="60">

LAST UPDATED
The date at the bottom of the page is automatic: it is the date index.html was
last changed on the server. Upload a new version and it updates by itself.
Nothing to edit. (If the server gives no date, the line is simply hidden.)

PHOTO
The Home page photo is images/padova-prato-della-valle.jpg, with a smaller WebP
copy (padova-prato-della-valle.webp) that modern browsers load first. To change
the photo, replace both files (same names), or delete the .webp file and the
<source> line above the <img> tag at the top of the Home section.

BOOK OF ABSTRACTS
Put the PDF next to index.html with the name book-of-abstracts.pdf. The link
at the top of the Programme page points to that file.
