## Custom Stylized Google Maps Basemap

---

[Go to interactive map](./givewell_google_styling.html)

## Overview:
I sourced and downloaded the GiveWell logos for color reference - extracting key branding colors to generate a custom color palette. Following this, I designed a bespoke Google basemap, adjusting color schemes to match those extracted from the logo. I documented the JSON styler information in a downloadable file so that the non-profit may use the style for future web development.

### Reference Logos:
![givewell_logo1](./img/givewell_logo1.png)
![givewell_logo2](./img/givewell_logo2.png)

### Color Palette Used 
- #FCB81B (orange)
- #29C5F1 (light blue)
- #669BB3 (teal)
- #3A3A3A (grey)
- #FBFAFF (white)

![palette](./img/Google_Basemap_Colors_Givewell.png)
## Customized Basemap
![basemap_screenshot](./img/screenshot_med.png)
![basemap_screenshot_big](./img/screenshot_big.png)
![basemap_screenshot_small](./img/screenshot_small.png)

### Styling 
| Feature Type              | Hex Code |
|---------------------------|----------|
| geometry                  | #ebe3cd  |
| geometry.fill             | #fcb81b |
| labels.text.fill          | #000000  |
| labels.text.stroke        | #669bb3  |
| administrative            | #c9b2a6  |
| administrative.land_parcel| #dcd2be  |
| landscape                 | #dfd2ae  |
| landscape.natural         | #dfd2ae  |
| poi                       | #dfd2ae  |
| poi.business              | #ffffff  |
| poi.park                  | #a5b076  |
| poi.sports_complex        | #ffffff  |
| road                      | #f5f1e6  |


[Download JSON Styler](./homeworks/givewell_styling.json)