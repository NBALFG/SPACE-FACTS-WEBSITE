# Space Facts Website Project Plan

## Overview
A comprehensive website dedicated to facts about space, including planets, the solar system, galaxies, moons, and the universe. The site will feature a homepage explaining its purpose, a navigation bar with dropdowns for each major category, and a search bar for easy navigation. All pages will be built using HTML and CSS and reside in the `moonfacts` folder.

## Structure
- **Homepage (index.html)**: Introduction to the website and its purpose.
- **Navigation Bar**: 5 dropdowns and a search bar:
  1. **Planets**
     - Categories: Terrestrial, Gas Giants, Dwarf Planets
     - Each category contains links to dedicated HTML pages for each planet
  2. **Solar System**
     - Sun, Solar Eclipse, Asteroid Belt, Kuiper Belt, Asteroids, Comets
     - Each with a dedicated HTML page
  3. **Galaxies**
     - Milky Way, Andromeda
     - Each with a dedicated HTML page
  4. **Moons**
     - Categories for moons of solar system planets (e.g., Earth's Moon, Jupiter's Moons, etc.)
     - Each category with a dedicated HTML page
  5. **Universe**
     - Black Holes, Stars, Nebulas, Exoplanets
     - Each with a dedicated HTML page
  6. **Search Bar**
     - Allows users to search and navigate to any HTML page

## File Layout (in `moonfacts/`)
- `index.html` (homepage)
- `style.css` (main CSS for the site)
- `planets/` (folder for planet pages)
  - `terrestrial/` (Mercury, Venus, Earth, Mars)
  - `gas-giants/` (Jupiter, Saturn, Uranus, Neptune)
  - `dwarf-planets/` (Pluto, Eris, Haumea, Makemake, Ceres)
- `solar-system/` (Sun, Solar Eclipse, Asteroid Belt, Kuiper Belt, Asteroids, Comets)
- `galaxies/` (Milky Way, Andromeda)
- `moons/` (Earth's Moon, Jupiter's Moons, etc.)
- `universe/` (Black Holes, Stars, Nebulas, Exoplanets)

## Implementation Steps
1. Create homepage with navbar and search bar
2. Implement dropdowns and link structure
3. Create dedicated HTML pages for each topic
4. Style the site with CSS
5. Implement search functionality (HTML/CSS only)

## Notes
- All navigation and search will be static (HTML/CSS only, no JavaScript unless later requested)
- Each fact page will contain information and images relevant to the topic
- Consistent design and navigation across all pages 