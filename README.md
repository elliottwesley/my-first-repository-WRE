16 April 2020
Revamped the layout of my portfolio.  Rather than two columns with a bunch of links between them, the main page is congregated with large buttons that lead to subpages with descriptions (will do these soon), project images (will do these soon), and links to the projects themselves.  As part of the remake, I've removed a decent portion of the links that were on the old portfolio as I want the new portfolio to favor actual projects rather than assignments.  The laboratory reports, though, are still included.

17 May 2019

Added portfolio_spring2019.zip.
Removed Web of Colors as it is part of the portfolio.



13 Dec 2018 - My project from CMST 135 (Web of Colors)

/*As I did not take CMST 103, I did not include a p5js sketch with my project.*/

The purpose of my final project, Web of Colors, is to provide a definition of the RGB or additive color scheme and analyze the color palettes that can be attained from various numbers of intensities for each additive primary.

Pages on the site include the following:
 - index.html
    This is the home page.  It provides an introduction to the website in the form of an explanation to its purpose.
    
 - rgb.html
    This page defines and exemplifies the additive color scheme.
    
 - contact.html
    This page comprises a form with four elements: a name input, an email input, a color well, and a text box for comments.
    
 - Analysis pages
  - binary.html
  - trinary.html
  - base_four.html
  - base-five.html
  - base-six.html
    These pages are a study of the RGB gamut in the form of cubic color palettes progressively increasing in size.

For bonus features, I incorporated into the site included a dropdown menu in the nav section to accommodate the analysis pages.

Design decisions included floating the navigation section to the right to deviate from past projects in the class.  I chose a color scheme based on the color green because the human eye can distinguish different shades of it the most easily.  In an attempt to satisfy contrast, I make the background colors very dark and the text lighter than a fully intense RGB green.  To account for tablet and mobile phone view, I programmed the navigation section to appear horizontally beneath the page header when entering tablet view, and to decrease in size when entering mobile phone view.

These were the challenges I encountered as I constructed my site:
 - The nav section in mobile views.  Earlier drafts of my site had the navigation buttons not appear uniform with one another in text size or in button height because of text wrapping.  CSS and some edits in HTML resolved this.
 - Images.  Despite making all of the images in Google Drawings and the Pixlr photo editor, each image would have been too large to see entirely on a mobile phone's display.  To rectify this, I programmed within the "less than 768 pixels wide" section for images to take up a percentage of the width of the display, and for the height to resize as well.

What I learned/got out of this exercise
 - Designing a website actually doesn't take very long; all you need is a reference book (just in case) and motivation.
 - Don't apply too much CSS at once--if the aesthetics don't look the way you want, which is very likely if you're beginning from scratch, you'll have a harder time looking for where the mistakes are.
 - You can't center images with CSS directly assigned to the img element.
