# nexcent landing page

this project brings a modern figma landing page design to life as a responsive website. the goal is to deliver a clean, professional look that adapts smoothly across mobile, tablet, and desktop screens.

## original design source
🎨[ figma landing page by muntasir billah](https://www.figma.com/community/file/1222060007934600841/responsive-landing-page-design-website-home-page-design-agency-website-ui-design)

## key features

- ✅ fully responsive layout — adaptive design for all screen sizes.
- ✅ clean, modern aesthetic — faithful to the original figma design.
- ✅ modular structure — html, css, and javascript separated for easy maintenance.
- ✅ icon integration — uses remix icon library for consistent visual style.

## what this project practices

- translating figma designs into semantic html.
- organizing css with a clear, maintainable structure.
- preparing javascript for future interactive enhancements.
- using flexbox and basic responsive techniques to keep the layout clean and adaptable.

## how to run

- ensure you have the resources folder with all images in the same directory as index.html.
- open index.html in a browser.
- styles are in style.css; scripts are in script.js.

## long screenshot

here's a preview of the full-length layout: <img width="1763" height="4226" alt="image" src="https://github.com/user-attachments/assets/8b6f73fd-d14d-4717-9ecd-3b68d292cd46" />

## notes

- placeholder text (lorem ipsum) is used in content blocks and can be replaced with final copy.
- the design includes a header, hero section, client logos, feature cards, stats, marketing section, and footer.
- icons are loaded via the remix icon cdn for simplicity.

## ❗improvements and fixes

- social icons in footer now look and feel like buttons (hover lift, shadow, color change) and show a pointer cursor.
- added a small active effect for social icons.
- made footer spacing nicer and centered on mobile.
- added smooth scrolling for links.
- fixed the hamburger menu so it closes when you click a link.
- tweaked some hover effects and spacing to make everything look smoother.
- increased footer text contrast — headings are pure white, body text uses a light blue-grey tone for better readability on the dark background.
- darkened the footer background slightly from #263238 to #1c2a30 so light text stands out more.
- enlarged footer links from 0.7rem to 0.85rem and added a hover state that brightens them to white.
- replaced the semi-transparent grey social icon backgrounds with a subtle white tint (rgba(255,255,255,0.15)) for better visibility.
- added a focus-within highlight on the email subscribe form — the border turns green when the input is focused.
- styled the email input with a visible border, placeholder color, and proper focus outline so text is readable inside the dark footer.
- moved the subscribe button's inline styles into a dedicated .subscribe-btn class in css for cleaner markup.
- changed the email input type from text to email for basic browser validation.
- added responsive max-width and wrapping for the subscribe form on smaller screens.
- used &copy; entity instead of a raw copyright symbol in the footer html for correct rendering.
