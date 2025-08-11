```text
   _____ _                                          _     _               
  / ____| |                                        | |   (_)              
 | |  __| | __ _ ___ ___ _ __ ___   ___  _ __ _ __ | |__  _ ___ _ __ ___  
 | | |_ | |/ _` / __/ __| '_ ` _ \ / _ \| '__| '_ \| '_ \| / __| '_ ` _ \ 
 | |__| | | (_| \__ \__ \ | | | | | (_) | |  | |_) | | | | \__ \ | | | | |
  \_____|_|\__,_|___/___/_| |_| |_|\___/|_|  | .__/|_| |_|_|___/_| |_| |_|
                                             | |                          
                                             |_|                          
                                                                                                                                                                                                  
Kagi Search — Custom Glassmorphism CSS
```
A polished, animated glassmorphism theme for the Kagi search engine. Clean UI, subtle motion, consistent styling across results, images, videos, news, and podcasts.

## Highlights (GIFs)

- Search results
![Kagi CSS – Search Results](images/search-results.gif)

- Top navigation
![Kagi CSS – Top Bar](images/top-bar.gif)

- Summarizer
![Kagi CSS – Summarizer](images/summarizer.gif)

- Shield popup
![Kagi CSS – Shield Popup](images/shield-popup.gif)

## Gallery (Static Images)

- Start page
![Start Page](images/startpage.png)

- Search results
![Search Results](images/search-results.png)

- Comments UI
![Comments](images/update-comments.png)

- Domain info
![Domain Info](images/update-domain-info.png)

- Dropdowns
![Dropdown](images/update-dropdown.png)

- Hover highlights (Interesting Finds)
![Hover Highlights](images/update-hover-interessante-funde.png)

- Translator widget
![Translator](images/update-translate-widget.png)

- URL highlight
![URL Highlight](images/update-url-highlight.png)

- OUTDATED Assistant (sidebar)
![Assistant Sidebar](images/update-assistant-sidebar.png)

- OUTDATED Assistant (panel)
![Assistant Panel](images/update-kagi-assistant.png)

## Overview

kagi-css is a custom stylesheet that gives Kagi a refined glassmorphism look with smooth transitions and a cohesive UI. The CSS is well-commented so you can quickly tweak colors, effects, and spacing to your taste.

## Features

- Glassmorphism visuals for navigation, settings, and key UI elements
- Thoughtful documentation and structure for easy customization
- Smooth animations and hover effects
- Enhanced buttons, search bar, and results layout
- Responsive across desktop and mobile
- Easy color customization via variables at the top of the file
- Uniform styling for results, images, videos, news, and podcasts

## File Options

Choose one approach:

- All-in-one: custom.css (includes the most important elements from all sections)
- Add-ins (pick as needed; currently not all can be used together):
  - video-section-addin.css – for the Video tab
  - podcast-section-addin.css – for the Podcast tab
  - news-section-addin.css – for the News tab

Note: The main search page includes key content from the all-in-one solution.

## Installation

1) Download custom.css (or the add-in you want) from this repository.
2) In Kagi, enable custom CSS: https://kagi.com/settings?p=custom_css
3) Paste the entire CSS into the input field.
4) Save and refresh Kagi.

Important: Kagi has a character limit for custom CSS. If the full stylesheet does not fit, use the smaller add-ins or trim features you do not need.

Recommended setting: Set URL placement to “Above Title” under Appearance for best visual alignment.

![URL Positioning](images/url-positioning.png)

## Animations

- Results fade-in as they load
- Pleasant hover transitions on links and buttons
- Subtle tile and component motion for a lively feel

## What’s New

The latest update improves the Quick Answer visuals for better emphasis and readability.

![Quick Answer Update](images/quick-search-update.gif)

## Roadmap

### Near-term
- [x] Consolidate add-ins into a modular, optional build (per-tab bundles)
- [ ] Accessibility contrast pass (WCAG AA) and focus-visible tweaks
- [ ] Optional compact density mode (tighter paddings and gaps)
- [x] Variable cleanup: unified spacing/radius/opacity scales
- [ ] Always update to the latest changes of Kagi
- [ ] Fix z-index bugs

### Mid-term
- [ ] Theme variants: Light (have to update it), Dark+ (already there, see https://github.com/realrogue/kagi-darker), automatic light/dark mode switch
- [ ] Per-tab refinements (Images, Video, News, Podcasts)
- [ ] Reduced motion mode (prefers-reduced-motion support)
- [ ] Improved mobile layout and touch targets

## Tips & Notes

- Character limit: If you hit Kagi’s limit, choose targeted add-ins or remove sections you don’t need.
- Mobile: The theme is responsive, but visual density differs from desktop; adjust variables if desired.
- Not affiliated with Kagi. This is a community theme.

## Contributing

Issues and ideas are welcome. If you spot a bug or have suggestions, reach out on Discord in kagi-discussions → “UI Design Ideas for my custom css”.

Discord thread: https://discord.com/channels/1256077108111868035/1265596713083732060

## Credits

Created by pdanzma. Inspired by modern search UIs (e.g., Google and Brave) with many original touches.

## License

See LICENSE file for terms. Feel free to fork this project and change it to your needs :)
