# Dev Pulse 

An introductory web development project consisting of building a website for a hypothetical company

## Architectural Blueprint (4 click user journey funnel)
1. User lands on page and is presented with a sticky navigation bar with high contrast CTA button. Also containing a high contrast 'Deploy Free Cluster' CTA button in the Hero section.
2. User can scroll or select 'Pricing' from nav bar to be directed to a 3-tier pricing matrix.
3. User may scroll or click the 'compatibility' nav bar button to specify product needs to calculate ideal price tier.
4. User may choose an option to be redirected to a registration form. The user can then populate the form with their credentials and desired tier.

## Don Norman Usability & Constraint Audit

| Norman Principal | UI Component/Feature Context | Specific HTML element/attribute |
|------------------|------------------------------|---------------------------------|
| Signifier | Primary Action Button | ```<a href="#register" class="btn btn-primary">``` |
| Signifier | Recommended Tier Indicator | ```<div class="popular-tag">``` |
| Physical/System Constraint | Workload Estimator: Node Count | ```step="1" min="1" max="100"``` |
| Physical/System Constraint | Operator Contact Field | ```required``` |
| Feedback Loop | Form Submission / Live Anchors | ```Button will change color/contrast/size when clicked``` |

## Commit History
This repo originally held both the ApexPay in-class demo and the DevPulse project. ApexPay demo and other assets have been removed.
**Below is a list of commits for the DevPulse project assignment 1B specifically:**

```bash
6011cc4 Resolve skipped heading level, add media section for mobile devices.
08a33c1 Fix broken img reference link from repo refactoring.
d7468e4 Adjust margins in product features.
21c8335 Add icons for product features. Swap translate for scale transform animations.
b6ef8d6 Style sections and elements. Apply chosen color scheme.
6c85851 Update stylesheet to include all dev pulse html elements.
d67848e Add proper indendation to pricing matrix banners.
138ba64 Fill in pricing matrix, tier calculator, and registration sections.
0aa4310 Populate header nav bar and hero section.
```

## References

Royalty free 'agp_studios-earth.gif' sourced from [Pixabay](https://pixabay.com/gifs/earth-map-geography-scifi-hud-24613/).