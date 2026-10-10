# Avanish Prakash - Assignment 1  
Link to my live website: https://localcashier.github.io/Assignment-1/

## Overview of this README File 
The following website is built with 4 HTML documents that were created using languages like HTML5 and CSS; 
It includes separate pages such as About Me, Projects, and Contact Me. My website is all based on a float-based layout, linear gradients,
a custom color scheme, which I will later go in depth about the color I used. This website is fully accessible on Desktops, Phones, and tablets. 


## GUI/Interface 

### I) The following site is a combination of fluid design and media queries so that it can be fully responsive on browsers. 
Throughout the assignment, Flexbox was never used, and all layouts are built using normal flow boxes with 'float'and 'clear' 
only, combined with fluid percentage-based widths. 

**Fluid Design** - Elements like the 'main' content box use percentage widths (width 80%) and not fixed pixel widths,
for the layout to stretch out naturally so that it can fill the available screen space for each viewport.

**Media Queries **and CSS Files - All CSS files are used in this website, and one can be used for each of the following viewports, 
linked through media queries. 

**css/full.css** —  This CSS file is for Desktop only, as it applies at min-width: 960px (desktop/laptop). 960px was chosen as the breakpoint 
as it is basically a standard width for any desktop screen  where a page has enough horizontal room to show full-width text 
and larger images comfortably without feeling cramped.

**css/tablet.css** -   This CSS file  utilizes  the  min-width: 481px and the max-width: 959px (tablet). 
This range will cover typical tablet screens between phone and full desktop sizes, like iPads or Samsung tablets
Nav links stay inline since there's still enough width for a horizontal row.

**css/phone.css** — this CSS file applies at max-width: 480px (mobile). Below this width, navigation links switch from
inline to stacked (display: block). As there isn't enough horizontal room to fit them side-by-side, 
the profile photo stops floating and goes full-width instead of wrapping text beside it. 

### II) Gradients 

- **Linear gradient:** applied to the body tag on all pages – background: linear-gradient(160deg, azure 0%, aliceblue 50%, beige 100%);` – for a subtle vertical color change from top to bottom.
- **Angle linear gradient:** applied to the header#banner tag (top navigation bar) on all pages – `background: linear-gradient(135deg, tan, blanchedalmond); – for a 135° diagonal gradient.
- The third type of gradient is applied to the main  content box – background: linear-gradient(to bottom, azure, aliceblue);

### III) Color scheme 

 


 
