Ireland Energy Grid Mapping Tool  

This project is an interactive web map of Ireland’s electricity grid and renewable energy resources.  
It allows users to explore power stations, transmission lines, interconnectors, congestion hotspots, and renewable facilities (wind, solar, hydro).  

 Runs in any modern browser.  
Works offline once set up.  
 Easy to update when new datasets are available.  

---

What You Get
- 🗺️ Interactive Map (zoom, pan, click features for details)  
- 🧭 Layer Controls (switch on/off lines, stations, wind farms, etc.)  
- 📊 Live Grid Stats (simulated with random updates)  
- 🎨 egend & Stylin for clarity  
- ⚡ Ready for Future API Integration 



 How to Run This Project Locally



 1. Install Prerequisites  
- Make sure you have Python 3.9+ installed → [Download here](https://www.python.org/downloads/).  
- Make sure you have Git installed → [Download here](https://git-scm.com/downloads).  

To check:
bash
python --version
git --version


2. Clone (Download) the Project

Open a terminal (Command Prompt, PowerShell, or Git Bash) and run:

git clone https://github.com/YOUR_USERNAME/ireland-energy-grid.git
cd ireland-energy-grid


Now you have the project files on your laptop.

3. Run Locally 
If you just want to open the map with datasets (no backend):

python -m http.server 8000
Then open your browser and go to:
 http://localhost:8000

That’s it — you’ll see the interactive map.

Credits
Data: EirGrid, CSO Ireland, SEAI

Mapping: Leaflet.js + OpenStreetMap

Developed with ❤️ in Python + JavaScript

Hosting Online
You can put this project online using:
GitHub Pages 

Netlify / Vercel this is the link to the netlify (https://68ca7d3d4db08e77252a7f0a--melodic-phoenix-781409.netlify.app/)
