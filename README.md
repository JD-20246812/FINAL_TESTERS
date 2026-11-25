# MindBridge PH

A mental health service directory for the districts of Baguio City, built for HUMCOM 1 under **UN SDG 11: Sustainable Cities and Communities**.

Plain HTML, CSS and JavaScript. No frameworks, no build step. Each page is self-contained: its styles, script and pictures are inside the `.html` file, so the site looks the same wherever it is uploaded.

## Files

```
index.html                 Home
service.html               District directory + appointment calendar
districts.html             Districts overview (20 districts)
about.html, help.html, crisis.html, understanding.html, selfcare.html,
breathing.html, students.html, community.html, videos.html, faq.html,
accessibility.html, contact.html, sdg11.html, references.html
media/                     5 original videos (.mp4), English captions (.vtt) and posters (.jpg)
```

## How the directory works

The Service page lists Baguio City in **20 districts**. Open a district to see its barangays and areas, then pick one to see the facility there. A facility is shown only in the barangay or area its own address names, for example:

| Barangay or area | Facility |
| --- | --- |
| Baguio General Hospital Compound (District 4) | Baguio General Hospital and Medical Center |
| Military Cut-off (District 13) | Baguio Medical Center |
| Mines View, Pacdal (District 1) | Mines View and Pacdal Health Centers |
| Teodora Alonzo (District 18) | Lucban Health Center and the CHSO Wellness Clinic |

Other hospitals and counseling offices are under **City-wide services** (Notre Dame de Chartres Hospital, Pines City Doctors' Hospital, Saint Louis University Hospital of the Sacred Heart, UP Baguio and University of Baguio counseling offices, and the Philippine Mental Health Association Cordillera Chapter). Barangays with no listed facility say so and point to the hotlines.

Health center hours and phone numbers come from a 2020 city listing, so confirm them by phone. To edit the data, search for `var DATA` and `var F` inside `service.html`.

## Run locally

Open the folder in VS Code, install **Live Server**, right-click `index.html` and choose **Open with Live Server**.

## Publish on GitHub Pages

1. Create a repository and upload all files (or use `git add .`, `git commit`, `git push`).
2. Go to **Settings, then Pages**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
3. Wait a minute or two, then open the live address. Press Ctrl+F5 if you still see the old version.

## Before submitting

- Replace the remaining placeholder line on `references.html`.
- Re-check hotline numbers and facility details right before submitting.
