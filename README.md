# WEDE5020
POE FULL
TECH4CHANGE 

Website Development — Portfolio of Evidence (POE) 

Thelile Hlengiwe Khumalo  |  ST10535427 

WEDE5020  |  Parts 1, 2 & 3 (JavaScript) 

 

PART 1 — WEBSITE PLANNING 

 

1. Website Choice 

Organisation selected: Tech4Change 

GitHub repository: https://github.com/Thelile/WEDE5020-PART2 

2. Business Description 

Tech4Change is a South African social enterprise that empowers communities through technology. The organisation provides digital skills training, coding workshops, and IT support with the aim of bridging the digital divide. Core initiatives include: 

Digital skills development 

Innovation challenges for young people 

ICT infrastructure support for underserved areas 

Tech4Change was founded by passionate individuals who recognised the need to equip communities with technology skills. The organisation has grown to address digital inclusion and youth empowerment at scale, and is based in Durban, KwaZulu-Natal. 

3. Reasons for Choosing This Organisation 

The following factors informed the selection of Tech4Change as the subject organisation: 

Bridging the Digital Divide: The organisation actively addresses the technology gap in South Africa. 

Youth Empowerment: Training and mentorship opportunities help young people participate in the digital economy. 

Innovative Solutions: Tech4Change supports youth innovators in developing technology solutions with social impact. 

Community Focus: The organisation works directly with local communities to address specific needs. 

Growing Demand for Tech Skills: By 2026, South Africa will require expertise in AI, data engineering, cloud architecture, cybersecurity, and fintech. 

Key areas where technology is driving change in South Africa include renewable energy, smart cities, and digital inclusion. 

4. Website Goals and Objectives 

The primary goal of the Tech4Change website is to empower communities through technology. Specific objectives include: 

Provide digital skills training information to underserved communities. 

Promote innovation and technology entrepreneurship. 

Bridge the digital divide in South Africa. 

Support social impact projects through technology solutions. 

Allow visitors to submit service enquiries, volunteer applications, and sponsorship requests online. 

5. Timeline and Milestones 

The project followed the milestones below: 

2023 — Launch of digital literacy programme 

2024 — Events hosted; mentorship programme launched 

2025 — Expanded skills offerings; new technical training introduced 

2026 — Programme review and planning for future iterations 

 

6. Budget 

The following budget was developed for the website project (client: THT Company, Durban): 

 

No. 

Details 

Est. Hrs 

Rate 

Amount (ZAR) 

Amount (USD) 

1 

Tech4Change – Design 

15 

R3,000 

R16,000 

— 

2 

Domain Registration 

8 

R2,000 

R7,000 

— 

3 

About Us Page 

12 

R4,000 

R9,000 

— 

4 

Services Page Layout & Content 

3 

R1,000 

R10,000 

— 

5 

JavaScript – Interactive Features 

10 

R2,500 

R9,500 

— 

6 

JavaScript – Form Validation & Map 

8 

R2,500 

R8,500 

— 

7 

JavaScript – Carousel & Accordion 

6 

R2,000 

R6,000 

— 

8 

Testing, QA & Final Deployment 

5 

R3,000 

R8,000 

— 

 

Exchange rate reference: R37.40 per USD. Project code: THT01233217. 

7. Website Pages and Content 

The site consists of five main pages, structured as follows: 

A. Home (index.html) 

Logo and branding 

 

Slogan / tagline 

Navigation links to all pages 

Programme highlight carousel 

Live post search 

B. About (about.html) 

Organisation mission statement 

Core values accordion (Clarity, Consistency, Community) 

Activities and programmes 

Photography and visual content 

C. Contact (contact.html) 

Contact form with SA phone validation 

Interactive Leaflet map — Durban office location 

Geolocation support 

Copyright notice 

D. Amy Foundation (amyfoundation.html) 

Programme focus and learning objectives 

Mentorship structure and support resources 

Growth tracking content 

E. YouthBuild (youthbuild.html) 

Project goals and skills overview 

Mentorship and impact sections 

8. Sitemap 

The sitemap below illustrates the navigation structure. Home (index.html) acts as the root, linking to About, Contact, Amy Foundation, and YouthBuild. All pages share a common footer containing contact details, email, and copyright information. 

 

Call: 076 122 3445  |  Email: tech4change@gmail.com  |  © Tech4Change Digital Company 

 

PART 2 — CSS IMPROVEMENTS 

 

Part 2 focused on transforming the initial static HTML structure into a polished, professional, and consistently styled website. All changes were implemented via an external stylesheet (Style.css) and applied uniformly across every page. 

1. Page Structure 

All pages now share the same layout pattern: a centred header, horizontal navigation bar, a max-width content wrapper, and a unified footer. This consistency helps visitors navigate the site intuitively and makes the codebase easier to maintain. 

2. Header and Navigation 

The logo is centred on every page, providing a stable visual anchor. The navigation menu was redesigned from a vertical bullet list to a horizontal row of pill-shaped buttons. Bullets were removed, spacing was added, and hover states were introduced. This makes the menu feel modern and reduces visual clutter. 

3. Content Layout and Card System 

Page content is wrapped in a centred container with a maximum width to prevent text stretching on large screens. All major sections were converted into visual 'cards' using: 

White backgrounds for readability 

Brown borders and rounded corners for warmth and structure 

Gentle box shadows to create depth and separation 

Cards are used for hero sections, contact forms, the map, and general content blocks. 

4. Carousel 

The programme highlight carousel was improved so that each slide remains visible for a longer period before advancing. The slides now occupy a full card-width area, and the transition is smooth. Controls include previous/next arrows and dot indicators, all keyboard-accessible. 

5. Contact Form 

The contact form was styled as a card with consistent label spacing, brown-bordered input fields, a cadet-blue focus ring, and a prominent submit button with a hover effect. These changes make the form more inviting and easier to use. 

6. Colour Palette 

The colour scheme was chosen deliberately: 

Brown — used for borders, headings, and buttons; conveys warmth and stability 

White — content area backgrounds for clean readability 

Cadet Blue — header, footer, and accent elements; conveys trust and modernity 

7. SEO and Accessibility 

The HTML structure was improved to use semantic tags (header, main, section, footer) so search engines can interpret page layout correctly. Headings follow a consistent hierarchy. The logo includes descriptive alt text, navigation links are descriptive, and all contact form fields have associated labels for screen-reader compatibility. 

 

PART 3 — JAVASCRIPT 

 

Part 3 adds interactivity and dynamic behaviour to the Tech4Change website through a single script file (script.js). All JavaScript is written in strict mode and wrapped in an immediately invoked function expression (IIFE) to avoid polluting the global scope. Each module checks for its target element before executing, making the file safe to include on every page. 

1. Overview of JavaScript Modules 

The table below summarises all ten modules included in script.js: 

 

Module / Function 

What It Does 

Where It Runs 

setFooterDatetime() 

Displays and updates the live date/time in the footer every 30 seconds 

All pages 

initNavToggle() 

Toggles the mobile hamburger menu open/closed; closes on link click 

All pages 

markActiveNavLink() 

Highlights the nav link matching the current URL using aria-current 

All pages 

initAccordions() 

Expands/collapses core values panels with smooth max-height animation 

About page 

initCarousels() 

Auto-plays programme slides with prev/next arrows, dots, and touch swipe 

Home / YouthBuild 

initContactForm() 

Validates name, email, SA phone number, and message; shows inline errors 

Contact page 

initMap() 

Renders a Leaflet map centred on the Durban office; supports geolocation 

Contact page 

initEnquiryForm() 

Returns instant cost + lead-time quotes; toggles service dropdown by type 

Enquiry page 

initPostsSearch() 

Filters blog post cards in real-time as the user types (150 ms debounce) 

Home page 

escapeHtml() 

Sanitises user input before inserting into the DOM — prevents XSS attacks 

Global helper 

 

2. Module Detail 

2.1 Footer Date/Time — setFooterDatetime() 

This function queries all elements with the class .footer-datetime and renders the current date and time in a human-readable format. It updates every 30 seconds using setInterval so that the displayed time stays current without a page refresh. 

function setFooterDatetime() { 
  var targets = document.querySelectorAll('.footer-datetime'); 
  if (!targets.length) return; 
  function render() { 
    var now = new Date(); 
    var text = 'Page rendered ' + now.toLocaleDateString(...) + ' · ' + now.toLocaleTimeString(...); 
    targets.forEach(function(el) { el.textContent = text; }); 
  } 
  render(); 
  setInterval(render, 30000); // refresh every 30 seconds 
} 

2.2 Mobile Navigation Toggle — initNavToggle() 

On small screens, the navigation is hidden behind a hamburger button (.nav-toggle). Clicking the button toggles the .is-open class on .site-nav and updates the aria-expanded attribute for accessibility. Clicking any navigation link automatically closes the menu. 

toggle.addEventListener('click', function () { 
  var isOpen = nav.classList.toggle('is-open'); 
  toggle.setAttribute('aria-expanded', isOpen ? 'true' : 'false'); 
}); 

2.3 Active Navigation Link — markActiveNavLink() 

This function compares each navigation link's href attribute against the current page filename. The matching link receives aria-current='page', which is used by both screen readers and the CSS to apply a visual highlight. 

2.4 Accordion — initAccordions() 

The About page uses an accordion to display the organisation's core values (Clarity, Consistency, Community). Each accordion button toggles its associated panel open or closed using a smooth CSS max-height animation. The aria-expanded attribute updates on each click for screen-reader compatibility. 

btn.addEventListener('click', function () { 
  var expanded = btn.getAttribute('aria-expanded') === 'true'; 
  btn.setAttribute('aria-expanded', String(!expanded)); 
  panel.style.maxHeight = expanded ? '0px' : panel.scrollHeight + 'px'; 
}); 

2.5 Carousel — initCarousels() 

Programme highlight slides auto-advance every 6 seconds. The module builds previous/next arrow buttons and dot indicators dynamically, and supports touch swipe gestures (delta > 40 px). Auto-play pauses on mouse hover or keyboard focus, and is disabled entirely when the user has prefers-reduced-motion enabled. 

// Auto-play (respects prefers-reduced-motion) 
function startAutoplay() { 
  if (prefersReducedMotion) return; 
  stopAutoplay(); 
  timer = setInterval(function () { goTo(current + 1); }, 6000); 
} 
 
// Touch swipe support 
viewport.addEventListener('touchend', function (e) { 
  var delta = e.changedTouches[0].clientX - startX; 
  if (Math.abs(delta) > 40) { goTo(current + (delta < 0 ? 1 : -1)); } 
}); 

2.6 Contact Form — initContactForm() 

The contact form validates four fields before allowing submission. Each validation failure attaches an inline error message and adds a .has-error class to the field wrapper. A simulated send (500 ms timeout) replaces the form with a personalised confirmation message, because the site is static and has no back-end. 

Validation rules: 

Name — minimum 2 characters 

Email — must match the pattern user@domain.tld 

Phone — must match South African format: 0XXXXXXXXX or +27XXXXXXXXX 

Message — minimum 10 characters 

var phonePattern = /^(0\d{9}|\+27\d{9})$/; 
 
if (!phonePattern.test(phone.value.trim())) { 
  setFieldError(phone, 'Use a South African number, e.g. 0761223445 or +27761223445.'); 
  problems.push('phone'); 
} 

2.7 Leaflet Map — initMap() 

The contact page renders an interactive Leaflet.js map centred on the Tech4Change Durban office at coordinates -29.8587, 31.0218. A popup marker labels the office location. A 'Locate Me' button uses the browser Geolocation API to re-centre the map on the user's position, with a graceful fallback message if permission is denied. 

var officeCoords = [-29.8587, 31.0218]; 
var map = L.map(mapEl, { scrollWheelZoom: false }).setView(officeCoords, 13); 
 
L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', { 
  maxZoom: 19, 
  attribution: '© OpenStreetMap contributors' 
}).addTo(map); 
 
L.marker(officeCoords).addTo(map) 
  .bindPopup('<strong>Tech4Change</strong><br>Durban, South Africa').openPopup(); 

2.8 Enquiry Form — initEnquiryForm() 

The enquiry form returns instant pricing and availability information based on the visitor's selections. Three service types are supported — website design (R4,500–R12,000), digital skills training (R350–R900 per learner), and consulting (R600/hour). When the enquiry type is not 'service', the service dropdown is hidden automatically using a change event listener. 

var servicePricing = { 
  website:   { label: 'Website design',          cost: 'R4,500 – R12,000',       lead: '2–4 weeks' }, 
  training:  { label: 'Digital skills training', cost: 'R350 – R900 per learner', lead: 'Next cohort within 3 weeks' }, 
  consulting:{ label: 'Consulting & support',    cost: 'R600 / hour',             lead: '1–5 business days' }, 
}; 

2.9 Posts Search — initPostsSearch() 

The home page displays six blog post cards. A search input filters the visible cards in real time against each post's title, excerpt, and tag. A 150 ms debounce timer prevents excessive DOM updates while the user is still typing. If no posts match, a friendly empty-state message is shown. 

searchInput.addEventListener('input', function () { 
  clearTimeout(debounceTimer); 
  debounceTimer = setTimeout(function () { 
    render(filter(searchInput.value)); 
  }, 150); // debounce prevents rapid re-renders 
}); 

2.10 Security Helper — escapeHtml() 

All user-supplied text is passed through escapeHtml() before being inserted into the DOM. This converts the five characters that have special meaning in HTML (&, <, >, ", ') into safe XML entities, preventing Cross-Site Scripting (XSS) attacks. 

function escapeHtml(str) { 
  return String(str).replace(/[&<>"']/g, function (c) { 
    return { '&': '&amp;', '<': '&lt;', '>': '&gt;', 
             '"': '&quot;', "'": '&#39;' }[c]; 
  }); 
} 

3. JavaScript Best Practices Applied 

The following practices were followed throughout script.js: 

Strict mode ('use strict') prevents accidental global variable creation. 

IIFE wrapper isolates all variables and functions from the global scope. 

Defensive guards (if (!element) return) ensure no errors on pages missing a target element. 

All user input is sanitised with escapeHtml() before DOM insertion. 

ARIA attributes (aria-expanded, aria-current, aria-label) are kept in sync with UI state. 

prefers-reduced-motion media query is respected — carousel auto-play is disabled for users who need it. 

Touch events use { passive: true } to avoid blocking the browser's scroll thread. 

A 150 ms debounce on the search input prevents unnecessary layout thrashing. 

4. GitHub Repository 

All HTML, CSS, and JavaScript source files are version-controlled and available at: 

https://github.com/Thelile/WEDE5020-PART2 

 

REFERENCES 

 

Web Design and Structure 

Beaird, J., George, J. and Walker, A., 2020. The Principles of Beautiful Web Design. 4th edn. SitePoint. 

Krug, S., 2014. Don't Make Me Think, Revisited: A Common-Sense Approach to Web Usability. 3rd edn. New Riders. 

SEO and Metadata 

Enge, E., Spencer, S., Stricchiola, J.C. and Fishkin, R., 2015. The Art of SEO: Mastering Search Engine Optimization. 3rd edn. O'Reilly Media. 

HTML5 and Semantic Markup 

Pilgrim, M., 2010. HTML5: Up and Running. 1st edn. O'Reilly Media. 

CSS Styling 

McFarland, D.S., 2020. CSS: The Definitive Guide. 5th edn. O'Reilly Media. 

Cederholm, D., 2014. Bulletproof Web Design. 3rd edn. New Riders. 

User Experience and Accessibility 

Nielsen, J. and Norman, D.A., 2000. Usability on the Web: Designing Websites that Work. 1st edn. Morgan Kaufmann. 

Henry, S.L., 2007. Just Ask: Integrating Accessibility Throughout Design. 1st edn. ET Textbooks. 

JavaScript and DOM Programming 

Flanagan, D., 2020. JavaScript: The Definitive Guide. 7th edn. O'Reilly Media. 

Simpson, K., 2015. You Don't Know JS: Scope & Closures. 1st edn. O'Reilly Media. 

MDN Web Docs, 2024. Web APIs — Document Object Model (DOM). Available at: https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model [Accessed: June 2026]. 

Colour Theory and Design Psychology 

Stone, D., Jarrett, C., Woodroffe, M. and Minocha, S., 2005. User Interface Design and Evaluation. 1st edn. Morgan Kaufmann. 

Wheeler, A., 2012. Designing Brand Identity. 4th edn. Wiley. 

Organisation Reference 

Tech4Change, 2024. About Us. Available at: https://tech4change.org [Accessed: 17 April 2025]. 
