Endangered Species Population & Conservation: Visualizing Protection Impact
Essential Question
"How has the population of endangered species (tigers, polar bears) changed in protected vs. non-protected areas over the past 50 years, and what does this reveal about conservation effectiveness?"
Data Sources
1. World Wildlife Fund (WWF) Population Data

Source: WWF Living Planet Index
Format: CSV
Description: Global species population trends (1970-2020).
Usage: Core population tracking baseline.

2. IUCN Red List Database

Source: IUCN Red List
Format: JSON
Description: Species conservation status & assessments.
Usage: Track threat levels and population viability.

3. Protected Planet Database

Source: UN Environment Programme
Format: GeoJSON
Description: Protected area boundaries & effectiveness.
Usage: Compare protection status impacts.

4. Species-Specific Surveys

Source: Global Tiger Initiative
Format: CSV
Description: Detailed population surveys.
Usage: Validate broader datasets.

Visualization Approaches
1. Interactive Population Tracker

Tech Stack: React + Recharts
Features:

Species selection dropdown
Protected vs. unprotected comparison
Timeline analysis (1970-2020)

2. Conservation Impact Dashboard

Tech Stack: React + Shadcn UI
Features:

Population metrics cards
Protection effectiveness indicators
Geographic distribution maps

Project Structure  
endangered-species-vis/   
├── data/  
│ ├── raw/ # Original datasets   
│ └── processed/ # Cleaned data   
├── src/   
│ ├── components/ # React components   
│ ├── utils/ # Data processing   
│ └── App.js # Main dashboard   
├── public/  
│ └── assets/  
└── package.json  
