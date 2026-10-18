# WWII Front Lines 1944–45

Interactive map of 98 daily G-3 situation maps of the US 12th Army Group (June 1944 – May 1945), placed on one modern France–Germany map.

**Live site:** https://sumitprahangdale-lab.github.io/ww2-situation-maps/

**Status:** work in progress.

## What it shows

- A date slider that steps through the maps, with modern, overlay and historic map views
- The front line of each day in red, with the previous five maps colour-coded
- Daily ground notes for 12th Army Group, 21 Army Group and 6th Army Group
- Daily Eighth and Ninth Air Force notes, about 700 named air targets, and schematic attack routes from base areas to targets

## How it was made

1. **Map preparation (QGIS).** The front lines and annotations on the scanned situation maps were traced, smoothed and refined with QGIS tools.
2. **Georeferencing.** Each map sheet was georeferenced to a modern basemap using its graticule and city control points, with a conic projection model. The fit is typically 0.5–3 km, depending on the sheet scale.
3. **Automation.** The workflow was then automated so it could be applied to all 98 maps.
4. **Chronology data.** Ground and air events for each map date were collected from the published chronologies listed below. AI tools were used to help extract and condense this information from the books, and to locate the air targets at town level.
5. **Website.** The website, its data files and the interactive features were built with AI assistance.

The air routes are schematic: each line runs from the force's base area to the target. The chronologies do not record the actual courses flown.

## Sources

- **Situation maps:** HQ 12th Army Group (HQ FUSAG until July 1944) G-3 situation maps, Library of Congress, Geography & Map Division (G5701.S7 svar .A4)
- **Ground events:** Mary H. Williams, *Chronology 1941–1945*, United States Army in World War II, Center of Military History ([HyperWar edition](https://ibiblio.org/hyperwar/USA/USA-SS-Chronology/index.html))
- **Air operations:** Kit C. Carter & Robert Mueller, *The Army Air Forces in World War II: Combat Chronology 1941–1945*, via the [USAAF chronology on Aircrew Remembered](https://aircrewremembered.com/USAAFCombatOperations/)
- **Place coordinates:** GeoNames
- **Modern basemap:** Natural Earth

## Planned

- Fill the gaps in the series, including the Battle of the Bulge (December 1944 – January 1945)
- Link the front lines and air targets to recorded ordnance finds, to help estimate which munition types and which forces are to be expected at a site

Collaboration and data on recorded ordnance finds are welcome. Contact me via GitHub or LinkedIn.

— Sumit Prahangdale
