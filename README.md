# Glassmorphism Style CSS File for Kagi Search Engine

Enhance your Kagi search experience with custom CSS animations and styles! It's a general overhaul of the search engine user interface and user experience.

![Kagi CSS Glassmorphism](images/search-results.gif)
---
![Kagi CSS Navigation](images/top-bar.gif)
---
![Kagi CSS Summarizer](images/summarizer.gif)
---
![Kagi CSS Shield-Popup](images/shield-popup.gif)

## Images
![Kagi CSS StartPage](images/startpage.png)
---
![Kagi CSS Search-Results](images/search-results.png)
---
![Kagi CSS Comments](images/update-comments.png)
---
![Kagi CSS Domain-Info](images/update-domain-info.png)
---
![Kagi CSS Dropdown](images/update-dropdown.png)
---
![Kagi CSS Hover-Funds](images/update-hover-interessante-funde.png)
---
![Kagi CSS Translator](images/update-translate-widget.png)
---
![Kagi CSS URL-Highlight](images/update-url-highlight.png)

## The Assistant (only for Ultimate-User)
![Kagi CSS Search-Results](images/update-assistant-sidebar.png)
---
![Kagi CSS Search-Results](images/update-kagi-assistant.png)


## Overview

kagi-css is a custom CSS file to beautify and liven up the Kagi search engine interface. With this stylesheet, you can enjoy a more visually appealing and dynamic search experience while using Kagi. Mainly inspired by Google and Brave Search, but with many exciting innovations of its own!

## Features

- **Glassmorphism**: A glass-inspired design for the settings and navigation bar
- **Documentation**: This css file has been documented quite accurately, which is why it is relatively easy to make changes
- **Custom Animations**: Smooth transitions and eye-catching effects
- **Enhanced UI Elements**: Improved buttons, search bar, and results layout
- **Responsive Design**: Looks great on both desktop and mobile devices
- **Easy color changes**: There is a field at the beginning where you can easily change the most important colors as you wish
- **Uniform Design**: The design now extends to almost all pages, be it results, images, videos, news or podcasts.
  
```
:root{
  --button-color:#F4B644; /* Primary color for the buttons */
  --button-hover-color:#E6AB40; /* Secondary color for the buttons - when hovering - should be slightly darker than the button color */
  --source-highlight-color:#D9A23C; /* Color of the sources and the small annotations for the references in the quick reply */
  --sri-hover-color:#F4B644; /* Color for hovering over search results */
  --color-search-input:#1e2028; /* Color for Search Box */
  --color-search-input-border:var(--graphite-900);
  --time-stamp:rgba(69,69,73,0.8); /* Color for timestamp with alpha value */
  --m_sri_gap_color:#222222!important;
  --app-text:#fdfdfd!important;
  --app-bg:#17191e;
  --inline-widget-bg:#1e2028;
  --primary-25:#1e2028; /* Adjustment for The Assistant */
  --primary-50:#1e2028; /* Adjustment for The Assistant */
  --primary-70:#17191e /* Adjustment for The Assistant */
}
```

## Installation

1. Download the `custom.css` file from this repository.
2. Enable custom CSS in Kagi Settings.
3. Paste the code into the inputfield at: [Link](https://kagi.com/settings?p=custom_css)
4. Save and enjoy your enhanced Kagi experience!

optional: It is planned that the "URL Placement” setting will be set to “Above Title” under the “Appearance” item.

![URL Positioning](images/url-positioning.png)

## Animations

kagi-css includes several animations to make your search experience more dynamic:

1. **Results Fade-In**: Search results smoothly fade in as they load.
2. **Hover Effects**: Buttons and links have pleasant hover transitions.
3. **Search Tiles**: Also have beautiful animations.

## Any ideas / comments?

If you have an idea that would extend / complete the look of Kagi or if you have found a bug, please write to me on Discord or write in Discord: kagi-discussions -> “UI Design Ideas for my custom css”. [Link](https://discord.com/channels/1256077108111868035/1265596713083732060)

# Enjoy your enhanced Kagi search experience!
