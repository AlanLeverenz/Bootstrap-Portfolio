# Bootstrap-Portfolio
Bootstrap version of portfolio.

Nav Bar. The nav bar code was modified by removing the button and div with the collapse classes. The "lg" class was replaced by "sm" to keep the nav bar items inline for larger screen widths. At "sm" the nav bar links stack up vertically because they are child elements of the nav element, but at least they are still visible. The original code had a collapse button that when clicked, only displayed the <li> items for a split second below the nav bar. I activated the corresponding nav bar <li> item depending on the page being displayed. 

About. I started off splitting the image from the paragraphs into 2-column and 10-column divs. I later changed it to a single 12-column row to allow the About image to be floated alongside the text.

Portfolio. I used the <card> element to display the images and their labels. I inserted style="flex-wrap:wrap" in the card container to keep the <card-deck> element from using a single row for displaying the images. I inserted a "min" class that set the minimum width of the cards and controlled their sizing when the screen size changed. Otherwise, as the screen width was reduced, the card widths were also reduced, creating an undesirable result.

Contact. The easiest Bootstrap code to apply was the form for the Contact page. Removing a few lines of code from the copied Bootstrap form was all that was needed.

Footer. I fixed the footer at the page bottom. I also inserted a background-color and z-index to keep elements scrolled over it from appearing inside the footer.




