# AMBMUN Website
## Pages
The following pages are currently accessible in the site: 
- index.html
- about.html
- committees.html
- contact.html
- faq.html
- rules.html
- schedule.html

All pages depend on the `fonts.css` file for fonts and the `style.css` file for universal styling

## Images
These images are used as placeholders and can be deleted after the backend implementation: 
- `dana placeholder.png`
- `ExampleCard.png`
- `Kasab.png`
- `Placeholder committee.png`

These images are nessecary for the website, either by design or by functionality
- `ambmunlogo.png`
- `Background.png`
- `Background2.png`
- `instagramlogo.png`
- `SG.png`

These images have notes
| Image | Notes |
| --- | --- |
| `Separator.svg` | This image exists in case the separator needs to be used again, the code can be copied from this file into the HTML directly to eliminate the time to call the image |
| `Schedule/` | This folder contains all the schedule image variants and need to be updated with the correct timing embedded into the image. Format of the images are provided below |

### Schedule Images Naming Convention
| File Name | Use Case |
| --- | --- |
| `Day <number>_none.png` | Used for when it is not currently the day specified and its not completed yet |
| `Day <number>_first_pending.png` | Used for when first session is ongoing |
| `Day <number>_second_pending.png` | Used for when second session is ongoing and all previous sessions are complete |
| `Day <number>_third_pending.png` | Used for when third session is ongoing and all previous sessions are complete |
| `Day <number>_fourth_pending.png` | Used for when last session is ongoing and all previous sessions are complete |
| `Day <number>_complete.png` | Used for when day is complete |

## Links
Register links were not provided when the website was created, to add the links for registration, replace `<a href="events.html" style="margin-right: 200px; margin-bottom: 5px; font-weight: bold; font-family: inter;">REGISTER</a>`'s href attribute with the link to the registration, it is located in the navbar after the navbar right div, also don't forget to change the registration button in the home page as well. 

## Dynamic Implementation
There are comments to specify what is the dynamic part of the website and which is editable. 
At every dynamic part of the site, there is a demo version of the element to showcase how it should be implemented, after the backend is implemented the demo should be removed to avoid filler example mixed in with the real data. 

---
Front end built by Mohamad Moukayed