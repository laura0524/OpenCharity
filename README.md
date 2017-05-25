# OpenCharity
Open Charity project site files

Assumptions:
  
  I utilized the design entirely from the psd file - whenever there were discrepencies between the psd and the proposed design, I favored the psd file. For instance, I made the blog div 100% the width of the front page as it is in the psd file, rather than a 75% div with a #fff background as seen in the proposed site design.
  
  I assumed you didn't want us to use any Javascript or JQuery to enhance the functionality of the webpage. If you would like me to add the pop-up web form (for the join button) or the sliders for the members and blog section, I can do so. My assumption though was to do this entirely with css and html, so those buttons are just images at this point, but could easily become functional buttons. Because css and html make it simple to make the "about" and "blog" buttons usable, I did do this.
  
 I also set most fonts to simple sans-serif when the fonts provided were unavailable. I did not purchase museo-sans or open-sans, but did write them as the default font in my css file. Therefore, if I had access to those fonts, they would be the default for the webpage, but as it stands now, my page is defaulting to the secondary selection, which is sans-serif.

Approach/features:

I started by coding the whole site, from top to bottom locally using brackets as my text editor of choice. I made the header fixed using position:fixed in styles then created a gray background div that lies directly under it to avoid overlay between the other divs when scrolling. 
For the hero, I chose to use a linear gradient to achieve the desired filter effect rather than creating an overlay image. This will make it easier to change the text on the hero in the future without layering issues. 
I used pixels for height measurements to be exact, adding and subtracting when necessary due to padding, but used percents with all widths to make responsiveness easier to achieve.
Then, I used media queries to make the webpage responsive. I chose 4 breakpoints at which to shift the layout of the page. Rather than shrink everything, I chose to turn multi-column layouts into vertical layouts as the page shrinks in order to be more visually appealing for the user. Also, this protects the image size and makes readability much easier.

I utilized acquia devdesktop to install and test through drupal 7 locally before hosting my solution to check for any errors. Then, I chose to host my solution through ecowebhosting, as I already have a package purchased through them. However, ecowebhosting only utilizes Drupal 8, so my page is a Drupal 8 page, which is why the file structure in the repository looks a bit different (with yml files and .theme and .library etc). I do have all the files in the drupal 7 structure as well because I used Drupal 7 locally before hosting, so if you would like these I can add them to the repository. 

