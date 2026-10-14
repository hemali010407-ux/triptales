# TripTales — Your Journey, Your Story

> **A Complete, Responsive, Animated, All-India Travel Planning Web Application**  
> Inspired by MakeMyTrip, built with pure **HTML5, CSS3, JavaScript (ES6+), and JSON**.  
> Runs entirely in the browser without any backend servers, Node.js, PHP, or Python.

---

## 🌟 Official Branding
- **Website Name:** `TripTales`
- **Tagline:** `Your Journey, Your Story`
- **Hero Headline:**
  > *"TripTales — Your Journey, Your Story"*  
  > *"Discover destinations, plan your perfect getaway, and create memories within your budget."*

---

## 🚀 How to Run with VS Code Live Server

1. **Open the Project in VS Code:**
   - Launch Visual Studio Code.
   - Click **File > Open Folder...** and select the `TRIPTALES` directory (`c:\Users\aayus\OneDrive\Desktop\TRIPTALES`).

2. **Ensure Live Server Extension is Installed:**
   - Go to the Extensions panel (`Ctrl + Shift + X`).
   - Search for **Live Server** (by *Ritwick Dey*) and click **Install** if not already installed.

3. **Launch the Website:**
   - Right-click on `index.html` in the file explorer sidebar.
   - Click **"Open with Live Server"** (or click **"Go Live"** in the bottom status bar).
   - Your default web browser will open `http://127.0.0.1:5500/index.html` automatically!

4. **Zero Setup & No API Keys Required:**
   - Everything runs instantly in the browser.
   - No `npm install`, no database setup, no API keys needed.
   - If opened over `file://` where local CORS might restrict JSON fetching, the application automatically loads an embedded verified fallback dataset seamlessly.

---

## 🗺️ Key Features & Pages

### 1. Homepage (`index.html`)
- **Modern Sticky Navbar:** Glassmorphism, animated logo icon, links with active state, and a live counter badge for saved trips.
- **Hero Section:** Official branding with quick CTA buttons: *"Plan Your Trip"* and *"Explore Destinations"*.
- **MakeMyTrip-Style Search Bar:** Inputs for Origin City, Destination, Departure Date, Return Date, Travellers, and Budget per Person with autocomplete datalists.
- **Popular Destinations Showcase:** Dynamic cards with category filter pills (Mountains, Beaches, Heritage, Nature, Spiritual, Adventure).
- **AI-Powered Travel Assistant:** Interactive chat window that understands natural language queries (e.g. *"Plan a 4-day Goa trip from Ahmedabad for 5 people within ₹7,000 per person"*) and instantly calculates costs and schedules.
- **Personalised Trip Planner:** Form mode allowing granular customization of days, travellers, budget, and travel preferences.
- **Trending Curated Tour Packages:** Highlights for Golden Triangle, Kerala Backwaters, Manali Snow Escapes, etc.
- **Responsive Footer:** Official links for IRCTC and State Roadways.

### 2. Destination Explorer (`destinations.html`)
- **All-India Coverage:** Over 35+ destinations spanning every region:
  - **North:** Manali, Shimla, Srinagar, Leh-Ladakh, Rishikesh, Varanasi, Agra, Delhi, Amritsar
  - **West:** Jaipur, Udaipur, Jaisalmer, Ahmedabad, Kutch, Dwarka, Mumbai, Pune, Goa
  - **South:** Munnar, Alleppey, Ooty, Coorg, Bengaluru, Chennai, Hyderabad, Hampi
  - **East:** Kolkata, Darjeeling, Puri
  - **North-East:** Gangtok, Shillong, Cherrapunji, Tawang
  - **Islands / UTs:** Andaman & Nicobar, Lakshadweep
- **Multi-Filter & Real-Time Search:** Search by name, state, or attraction; filter by region, budget bracket, duration; sort by cost or name.
- **Interactive Destination Modal:** Deep dive into attractions, sample hotels, travel tips, and direct *"Plan Trip Here"* links.

### 3. Curated Packages (`packages.html`)
- Handcrafted circuits including Rajasthan Heritage, Kerala Backwaters, Himalayan Escapes, and Andaman Island Paradise.
- Includes duration, inclusion tags, sample pricing benchmarks, and customizer buttons.

### 4. Hotels & Stays Directory (`hotels.html`)
- Filter stays by destination and budget tier (Budget / Hostels, Mid-Range / Boutique, Luxury / Palaces).
- Realistic price estimates, ratings, amenities, and direct planning shortcuts.
- Transparent disclaimer distinguishing sample benchmark prices from live availability.

### 5. Transport & Routes Hub (`transport.html`)
- Compare Flights, Indian Railways, and State Roadways buses between major Indian origin hubs and destinations.
- Official direct links to **IRCTC**, **GSRTC**, **KSRTC**, **MSRTC**, **HRTC**, and domestic flight carriers.

### 6. My Trips (`my-trips.html`)
- **Local Storage Engine:** Saves your generated itineraries directly in your browser's `localStorage` (`triptales_saved_trips`).
- View day-by-day itineraries, expense breakdowns, and trip details.
- **Export & Print:** Export your trip as a formatted `.json` file or use `window.print()` for a print-ready itinerary document.
- Delete individual trips or clear all saved trips.

---

## 📁 File Structure

```
TRIPTALES/
│── index.html              # Homepage with hero, search, planner & AI assistant
│── destinations.html       # All-India destination search, filter & explorer
│── packages.html           # Curated travel packages and customizer
│── hotels.html             # Hotel directory with destination & tier filters
│── transport.html          # Transit route hub with official booking links
│── my-trips.html           # Saved trips manager with print & export features
│── README.md               # Documentation and Live Server setup instructions
│── css/
│   └── style.css           # Modern styles, variables, cards, modals & print rules
│── js/
│   ├── app.js              # Core engine, JSON fetcher, fallback, modal system
│   ├── destinations.js     # Search, multi-filtering & sorting logic
│   └── planner.js          # Trip planner, budget calculator & AI chat assistant
└── data/
    └── destinations.json   # Comprehensive all-India destination database
```

---

## 🎨 Design System & Highlights
- **Color Palette:** Deep Royal Blue (`#0f4c81`), Sunset Coral (`#ff6b4a`), Warm Gold (`#f59e0b`), Emerald Teal (`#0d9488`), and Slate Neutrals.
- **Typography:** *Plus Jakarta Sans* for clean UI and *Playfair Display* for editorial elegance.
- **Micro-Interactions:** Subtle card elevations, hover zoom on destination photography, interactive chips, animated badges, and toast notifications.
- **Zero Dead Buttons:** Every button, filter, tab, and form functions and provides real interactivity.

---

© 2026 **TripTales** — *Your Journey, Your Story*.
