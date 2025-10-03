Rabijan Ragupalan — Portfolio Website

Overview 
Portfolio includes 4 separate pages:  
- `index.html` → Home page  
- `about.html` → About Me (includes `Me.jpg` and `Video.mp4`)  
- `projects.html` → Projects  
- `contact.html` → Contact Me  


Files and assets used to create the portfolio
- HTML Files: `index.html`, `about.html`, `projects.html`, `contact.html`
- CSS Files: `base.css`, `mobile.css`, `tablet.css`, `desktop.css`
- Assets:  
  - `Me.jpg` → my photo  
  - `background.jpg` → site background image  
  - `Video.mp4` → introduction video  


Responsive Design
The website is responsive and uses fluid design.
I created separate CSS files for different viewports:

- Mobile (phones): `mobile.css` → `max-width: 599px`  
  - Stacks sections vertically and portrait above bio.
  - Most phones are under 600px wide in portrait mode.

- Tablet (small/medium screens): `tablet.css` → `600px – 1023px`  
  - Uses two-column layout (portrait + bio side by side, features in two columns).
  - Tablets are usually 600px portrait and just over 1000px landscape.  

- Desktop (laptops & larger): `desktop.css` → `min-width: 1024px`  
  - Expands content, features shown in multiple columns, more spacing.
  - Laptops and larger monitors are 1024px most of the time.  

These breakpoints were chosen because they match common device widths and demonstrate responsiveness.


Color Scheme
I used a blue / gray theme to match my background image which is textured royal blue.  
The palette was tested by Adobe Color:

- Textured Royal Blue: '#114FB2'
- Dark Blue (fallback background): '#0f375e'  
- Accent Blue:' #2b6ca3'  
- Gray-Blue: '#6d8ea6'
- Off-White (text): '#eaf6ff'
- Neutral Gray: '#2b333b'

This made sure of good readability against the blue background and because its darker its easier to view in the sun on a phone.


Gradients
- Linear Gradient: was used in the site header (`.site-header`) for a subtle effect.  
- Angled Gradient (135°): was used in the hero section (`.hero`) to create a diagonal overlay for readability on top of the background image.  



Semantic HTML
I used semantic elements across all pages:  
- `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<figcaption>`, `<footer>`



Resources
- https://developer.mozilla.org/en-US/docs/Web/CSS/color (for the rgba and linear Gradient)
-https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/textarea (to get the textarea cnd runnning)
-https://www.w3.org/WAI/standards-guidelines/aria/ (Accessibility features)



GitHub Repository: https://github.com/RabijanR/My-Portfolio.git
Portfolio Access Link: https://rabijanr.github.io/My-Portfolio/index.html 