# README

### Overview

Output is a journaling app that automatically creates daily entries by weaving a user's digital life into a personalized and secure time capsule of their lived experiences.

### Problem

In our digital lives, we leave behind a vast trail of information, yet we rarely pause to reflect on the everyday moments that shape our lives. Traditional journaling can feel cumbersome, while social media often prioritizes curated highlights. Output aims to bridge this gap by providing a private, effortless way to document and appreciate the beauty of the mundane.

### User Profile

The ideal user is anyone interested in self-reflection and personal archiving. They may be:

- Journaling enthusiasts seeking a digital alternative
- Memory keepers who want to preserve everyday moments
- Those curious about their digital footprint and daily patterns

⠀The app must be intuitive, private, and customizable to cater to different preferences.

### Features

- **Automatic Entry Creation:** Gathers data from various sources (photos, location, weather, etc.) at the end of each day to generate a draft entry.
- **Curation Tools:** Allows users to edit, add, or remove content from the entry, personalizing it to their liking.
- **Timeline View:** Presents a visual overview of the day, with data points plotted chronologically.
- **Card-Based Layout:** Organizes data into interactive cards for easy browsing and exploration.
- **Mood Tracker:** Enables users to log their mood throughout the day and associate emotions with specific moments.
- **Privacy Controls:** Ensures all data is stored locally on the device, with options to share or keep entries private.

⠀Implementation

### Tech Stack

- **Frontend:** React Native (for cross-platform compatibility)
- **UI Library:** React Native Paper (for material design components)
- **Navigation:** React Navigation

### APIs (Potential, for Future Development)

- **Photos:** Native device photo library API
- **Location:** Native device location services API
- **Weather:** OpenWeatherMap API

### Sitemap

- **Home:** Timeline of daily entries
- **Entry View:** Detailed view of a single entry
- **Settings:** Customize data sources, privacy, and preferences

### Mockups

- [\[Link to Figma mockup\]](https://www.figma.com/proto/6ZwyHB6SmR5IIusfF263Dv/Process?node-id=0-1&t=Ksuhms2sDzIC5d4l-1)

### Data

- **Daily Entry:** Collection of text, images, location, weather, and mood data, stored locally on device.

### Endpoints (N/A for MVP)

- Not applicable for the initial prototype, as data will be stored locally.

### Auth (N/A for MVP)

- Not applicable for the initial prototype, as there will be no user accounts or sharing features.

### Roadmap

- **Week 1:** Design Figma mockups, set up basic React Native project structure.
- **Week 2:** Implement core UI components (timeline, card layout).
- **Week 3:** Add functionality for creating and viewing static entries.
- **Week 4:** Integrate mood tracker and basic curation tools.

### Nice-to-Haves

- Advanced data analysis and insights
- Integration with external APIs for data collection
- Cloud syncing and backup
- Transactions linked to vendor
- Option to see raw chronological (think Whoop landscape mode heart rate screen)
- Social sharing/viewing features
- Weather
- Geolocation
- Relational analysis
  - Data production per location patterns/habits
  - “Vibe” of photo heavy days, movement heavy days, email heavy days, etc (maybe we don’t need this because we already know this, but also sometimes seeing the numbers is valuable, but also this may not be the point, but also we don’t know the point yet and it will emerge—it will reveal itself through effort and building)
- Prompt copy slightly changes each day
