The following document describes the requirements for this project. Make sure to follow all the requirements precisely
to ensure successful completion.

## Goals

This project is the personal website of Dirk Ornee, owner of this project. The website is meant as a portfolio and
showcase of his work. He is a drummer and producer. I will launch this website on the internet and make it accessible to
the public.

## Design

To have an idea of the design (this doesn't need to be followed exactly, but the gist should be the same) have a look at
the images folder, there are images of a template that I'd like to follow.

### Home

The homepage is a simple page with my name, title 'Musician and Mixing Engineer' and a picture of me. Use
`assets/images/Dirk Ornee profile.jpg` for the main image.

### Work

The work page is a list of all the projects that I have worked on. This will be video (YouTube) and audio links. Use
placeholders for YouTube embeds for now. For audio, use the standard HTML5 `<audio>` player. Look at
`requirements/images/work-desktop.png` for layout inspiration.

### Contact

The contact page is a form where you can send me an email. Since we are using a static site on GitHub Pages without
JavaScript, we will use **Formspree** (free plan) for form handling. The form should include Name, Email, Subject, and
Message fields. Look at `requirements/images/contact-desktop.png` for an example.

### Instagram

Instead of a live JS-based feed, the Instagram page features a static grid of curated images. This ensures the site
remains fast and adheres to the no-JS-by-default rule. A "Follow @dirkornee" button links directly to the full Instagram
profile.

## Technical Requirements

- Navigation: The website will use separate HTML files for each section (Home, Work, Contact, Instagram) to allow for
  JavaScript-free navigation transitions.
- JavaScript: Strictly forbidden on most pages. Exceptions made for the Instagram grid (static but links to profile) and
  the Contact page (uses EmailJS for form submission).
- EmailJS: Used on the contact page with Service ID `service_swyv7qs`, Template ID `template_q3ijbm1`, and Public Key
  `ui8kGY2PrPJsqNjFr`.
- HTML/CSS: Use all modern standards.
- Hosting: GitHub Pages.
- Frameworks/Libraries: No JS frameworks. Use **FontAwesome** for icons.
- Responsiveness: Mobile-first design. Refer to `requirements/images/home-mobile.png`.
- Assets: Use logos from `assets/logo/` and profile picture from `assets/images/Dirk Ornee profile.jpg`.
