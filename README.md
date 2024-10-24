# Academic Profile Website

This is an academic profile website built using Jekyll and the Academic Pages template.

## Project Structure

```
.
├── _data/                  # Site configuration data
│   └── navigation.yml      # Navigation menu configuration
├── _pages/                 # Main content pages
│   ├── about.md           # Home page / About me
│   ├── research.md        # Main research page
│   ├── research/          # Individual research topic files
│   │   ├── _research_alos2.md
│   │   ├── _research_landslides.md
│   │   └── ...
│   └── teaching.md        # Teaching page
├── images/                 # Image assets
│   ├── research/          # Research-related images
│   └── teaching/          # Teaching-related images
└── _config.yml            # Main site configuration
```

## Content Organization

- Research topics are organized into individual markdown files in `_pages/research/`
- Images are organized by category in `images/`
- Navigation and site structure are configured in `_data/navigation.yml`

## Adding Content

### Research
1. Add images to `images/research/`
2. Create or update research topic file in `_pages/research/`
3. Update main research page if needed

### Teaching
1. Add images to `images/teaching/`
2. Update teaching gallery in `_pages/teaching.md`

### Profile
1. Update profile image in `images/profile.png`
2. Update banner image in `images/banner.jpg`
3. Modify about content in `_pages/about.md`
