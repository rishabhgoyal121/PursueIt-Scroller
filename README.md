# PursueIt Scroller

Interactive D3.js scrollytelling experience focused on visual storytelling, SVG-heavy animation, and narrative-driven data interaction patterns.

## Why I Built This

I built this project to explore advanced frontend storytelling patterns beyond standard app UIs, especially long-form scrollytelling with D3, custom SVG assets, and animation orchestration.

## Key Features

- Long-form scrollytelling interaction model
- D3-powered animation and DOM/SVG transitions
- Story modules organized under `js/stories/`
- Rich SVG asset usage for visual scenes and transitions
- Custom conductor/orchestration flow in `js/conductor.js`

## Tech Stack

**Frontend:** HTML, CSS, JavaScript  
**Visualization/Animation:** D3.js, custom scroll orchestration scripts  
**Assets:** SVG illustrations and custom visual libraries

## Architecture Notes

```txt
scroll progression -> conductor.js -> story modules -> D3/SVG scene updates
```

## Project Structure

- `index.html`: entry point and story canvas
- `css/`: styling and scrolling animation styles
- `js/conductor.js`: global orchestration for transitions and stages
- `js/stories/`: modular story segments and scene logic
- `js/anim-lib/` + `js/scrolling-lib/`: animation and scroll helper libraries
- `PursueIt-img/` + `img/` + `Trampoline-svg-crop/`: visual assets

## Run Locally

Because this is a static site, you can serve it with a simple local web server:

```bash
cd PursueIt-Scroller
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

## Screenshots

<!-- TODO: Replace placeholders with actual screenshots/GIFs from the live scrollytelling flow. -->
- [`docs/screenshots/intro-scene.png`](docs/screenshots/intro-scene.png) (placeholder)
- [`docs/screenshots/scroll-story-transition.png`](docs/screenshots/scroll-story-transition.png) (placeholder)
- [`docs/screenshots/d3-animation-scene.png`](docs/screenshots/d3-animation-scene.png) (placeholder)
- [`docs/screenshots/final-section.png`](docs/screenshots/final-section.png) (placeholder)

## Recruiter Summary

This project demonstrates:
- Advanced frontend interaction engineering
- Complex D3/SVG animation orchestration
- Strong visual storytelling implementation in a real, shippable static web experience

## Deployment

<!-- TODO: Add the exact deployed URL/workflow if this project is hosted publicly. -->
