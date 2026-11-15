[README.md](https://github.com/user-attachments/files/34888956/README.md)
# my-first-website

## Accessibility

Tested the published Home, Projects, and About pages with WAVE on November 15, 2026.

| Page | Errors | Contrast errors | Alerts |
| --- | ---: | ---: | ---: |
| Home (`index.html`) | 0 | 0 | 0 |
| Projects (`projects.html`) | 0 | 0 | 0 |
| About (`about.html`) | 0 | 0 | 0 |

### Fix log

No new fixes were necessary during this review because all three pages returned zero WAVE errors and their current text/background combinations passed WCAG AA for the text sizes used.

### Contrast verification

Checked the stylesheet's text/background color combinations using the WebAIM Contrast Checker.

| Text use | Foreground | Background | Contrast ratio | WCAG AA result |
| --- | --- | --- | --- | --- |
| Body text on cream | `#38261F` | `#F8E1B6` | 11.2:1 | Pass |
| Body text on peach | `#38261F` | `#E9A992` | 7.20:1 | Pass |
| Headings on cream | `#A9412C` | `#F8E1B6` | 4.72:1 | Pass |
| Large headings on peach | `#A9412C` | `#E9A992` | 3.03:1 | Pass for large text |
| Notes on cream | `#542719` | `#F8E1B6` | 9.77:1 | Pass |
| Notes and footer text on peach | `#542719` | `#E9A992` | 6.27:1 | Pass |
| Unvisited navigation links on cream | `#0000EE` | `#F8E1B6` | 7.35:1 | Pass |
| Visited navigation links on cream | `#551A8B` | `#F8E1B6` | 8.61:1 | Pass |

Gestalt Principles
- Proximity: I used 8px gaps between headings and related text, with 32px spacing after main sections, to group related information and separate different topics.
- Similarity: I used matching bold, underlined navigation links with the same padding, colors, and interaction styles on every page so visitors can recognize the same controls throughout the site.
