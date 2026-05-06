# Canada Adventure - September 2026 🍁

A shareable web brochure for our family trip to Victoria and Vancouver, BC.
Traveling party: Brandon, Megan, Nancy & Kirk.

**Dates:** September 11-18, 2026

## View the Brochure

Live site: `https://<YOUR-GITHUB-USERNAME>.github.io/<REPO-NAME>/`

Or open `index.html` directly in any browser.

## What's Inside

- **Day-by-day itinerary** with start times, activities, and all the confirmed stops
- **Photos** of each destination
- **Links** to all attractions, restaurants, and bookings
- **Booking checklist** for advance reservations
- **Bonus stops** section for flexible add-ons

## Repository Structure

```
.
├── index.html              # Main brochure (this is what GitHub Pages serves)
├── images/                 # Web-optimized photos
│   ├── botanical_beach_tidal_pools.jpg
│   ├── butchart_gardens.jpg
│   ├── capilano_suspension_bridge.jpg
│   ├── richmond_night_market.jpg
│   ├── stanley_park.jpg
│   ├── victoria_butterfly_gardens.jpg
│   └── victoria_vrbo_front_door.jpg
├── _archive/               # Original source docs (not deployed)
│   ├── Canada_Trip_Brochure.html
│   ├── Canada_Trip_Draft_v1.md
│   ├── Canada_Trip_Itinerary.md
│   └── [original PNG photos]
├── .gitignore
├── LICENSE
└── README.md
```

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g., `canada-trip`)
2. Initialize this folder as a git repo and push:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Canada trip brochure"
   git branch -M main
   git remote add origin https://github.com/<YOUR-USERNAME>/<REPO-NAME>.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**
4. Under "Source," select **Deploy from a branch**
5. Select branch: `main`, folder: `/ (root)`, click **Save**
6. Wait 1-2 minutes, then visit `https://<YOUR-USERNAME>.github.io/<REPO-NAME>/`

## Customization

To update the itinerary, edit `index.html` directly. The file is fully self-contained with inline CSS and uses only Google Fonts as an external dependency.

---

*Made with ❤️ for a family road trip.*
