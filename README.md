# Avanish Prakash - Assignment 1  
Link to my live website: https://localcashier.github.io/Assignment-1/

## Overview of this README File 
The following website is built with 4 HTML documents that were created using languages like HTML5 and CSS; 
It includes separate pages such as About Me, Projects, and Contact Me. My website is all based on a float-based layout, linear gradients,
a custom color scheme, which I will later go in depth about the color I used. This website is fully accessible on Desktops, Phones, and tablets. 


## GUI/Interface 

### I) This site combines fluid design and media queries so it is fully responsive across browsers. 
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

- **Linear gradient:** applied to the body tag on all pages – background: linear-gradient(160deg, azure 0%, aliceblue 50%, beige 100%); – for a subtle vertical color change from top to bottom.
- **Angle linear gradient:** applied to the header#banner tag (top navigation bar) on all pages – `background: linear-gradient(135deg, tan, blanchedalmond); – for a 135° diagonal gradient.
- The third type of gradient is applied to the main  content box – background: linear-gradient(to bottom, azure, aliceblue);

### III) Color scheme 
<img width="1600" height="2400" alt="AdobeColor-My Color Theme" src="https://github.com/user-attachments/assets/f584a462-e08d-44e7-a463-99e4227e066c" /> 

I used the following colors because I like this similar palette that moves from blue/whites into warm tones, which makes the gradients blend smoothly rather than clash. Whereas tan, on the other hand, is used consistently for borders and accents across every page.

## Testing and Validation  
<img width="947" height="476" alt="Nu Html Checker" src="https://github.com/user-attachments/assets/01bec4b8-68e0-40e2-8d59-dbb79c78aba6" />


<img width="935" height="496" alt="W3C CSS Vaildator Results" src="https://github.com/user-attachments/assets/67ed5a8e-b85d-4cd0-9f45-ce8592e46528" />


<img width="944" height="494" alt="Line Checker" src="https://github.com/user-attachments/assets/39b3dcfd-4f3a-4966-a740-dfb47d57e46d" />



<img width="892" height="487" alt="Spell Check" src="https://github.com/user-attachments/assets/002a9b20-19fa-4094-81c1-e73f744e7696" />

<img width="946" height="511" alt="Wave Screenshot (2)" src="https://github.com/user-attachments/assets/bb15a9af-2e5c-4779-a323-1a23d47fcf40" />

<img width="953" height="497" alt="Wave Screenshot (3)" src="https://github.com/user-attachments/assets/02a437c3-3d7e-4263-be49-73e4769e69b5" />

<img width="954" height="502" alt="Wave Screenshot (1)" src="https://github.com/user-attachments/assets/411c06c0-1de9-4113-92c6-2be868c560a2" />


## Version Control 

This project was built and tracked by committing the  website at different stages during development. If you want to view the full commit history, it is posted below. 
https://github.com/localcashier/Assignment-1 


## Citations 

This website was built using  concepts that were taught in class lectures and notes by Professor Ahmed Sheikh from weeks 1 to 4,  and PDF files 
 
