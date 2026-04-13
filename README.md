# 🎣 Minnesota Fish Tracker

A comprehensive progressive web app for tracking fishing catches in Minnesota waters. Features species identification, trophy detection, scientific analysis, AI fishing guide, and detailed catch logging with photo support.

![Version](https://img.shields.io/badge/version-1.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-web-orange)

## 🌟 Features

### 📊 **7 Main Tabs**
- **Species** - Browse all 22 Minnesota game fish with scientific data
- **Log** - Capture catches with photos and environmental conditions
- **History** - View all logged catches with statistics
- **Analytics** - Graphs and insights on your fishing patterns
- **Patterns** - Success rate analysis by species, location, and conditions
- **Forecast** - Date-specific fishing conditions and bite predictions
- **AI Guide** - Expert bass fishing advice based on real pro knowledge

### 🐟 **Fish Species Coverage (22 Total)**
- **Bass:** Largemouth, Smallmouth, Rock Bass
- **Pike Family:** Northern Pike, Muskellunge, Chain Pickerel
- **Walleye Family:** Walleye, Sauger
- **Panfish:** Bluegill, Pumpkinseed, Black Crappie, White Crappie, Yellow Perch
- **Trout:** Brook, Brown, Rainbow, Lake Trout
- **Catfish:** Channel, Flathead
- **Other:** Lake Sturgeon, White Bass, Yellow Bass

### 🎯 **Advanced Features**

**Auto-Generated Fish Names (200+ names)**
- Every catch gets a personality name
- 70+ bass names inspired by Flair & BamaBass (Bertha, Hoss, Sheila, Bubba, Zeus, etc.)
- 18-25 names per species
- Click to edit any name
- Trophy fish get "Trophy" prefix

**Scientific Calculations**
- Fulton's K-Factor (condition/health)
- Estimated age based on length
- Moon phase tracking
- Solunar feeding periods
- Time of day classification

**Trophy Detection**
- Automatic Master Angler qualification
- Minnesota DNR trophy standards
- Trophy badge display

**Environmental Logging**
- Water temperature
- Air temperature
- Barometric pressure & trend
- Wind speed & direction
- Sky conditions
- Water clarity
- Depth & structure
- Fight time
- Release condition

**Photo Management**
- Take live photos
- Upload old pictures with manual date entry
- Multiple photos per catch
- Full-screen photo viewer

**Data Analysis**
- Success rates by species
- Location performance
- Lure effectiveness
- Moon phase correlations
- Seasonal patterns

**AI Fishing Guide**
- Real-time bite predictions
- Lure recommendations
- Location strategy
- Technique guides
- Water temperature science (Kevin VanDam insights)
- Barometric pressure effects
- Time of day tactics

**Date-Specific Forecast**
- Ice-out tracking (April 20 - May 5 typical)
- Pre-spawn, spawn, post-spawn windows
- Solunar major/minor periods
- Hourly bite ratings
- Season-specific tactics

## 🚀 Installation

### **Option 1: GitHub Pages (Recommended)**
This repository is hosted on GitHub Pages. Simply visit:
```
https://[your-username].github.io/fish-tracker/fish-ultimate.html
```

Then bookmark or "Add to Home Screen" on mobile.

### **Option 2: Download Locally**
1. Download `fish-ultimate.html`
2. Open in any modern browser (Chrome, Firefox, Safari, Edge)
3. Bookmark for easy access
4. Works 100% offline

### **Option 3: Mobile App Experience**
**iPhone:**
1. Open the link in Safari
2. Tap Share button
3. "Add to Home Screen"
4. App icon appears on home screen

**Android:**
1. Open the link in Chrome
2. Menu (⋮) → "Add to Home screen"
3. App icon appears on home screen

## 💾 Data Storage

- **All data stored locally** in browser's localStorage
- No internet required after initial load
- No server, no database, no login needed
- Export catches to CSV anytime
- Backup/restore functionality included
- Photos stored as base64 in localStorage

## 📱 Compatibility

**Browsers:**
- ✅ Chrome 90+
- ✅ Safari 14+
- ✅ Firefox 88+
- ✅ Edge 90+

**Devices:**
- ✅ iPhone (iOS 14+)
- ✅ Android (8.0+)
- ✅ Desktop/Laptop (any OS)
- ✅ Tablet

**Requirements:**
- JavaScript enabled
- localStorage enabled (default in all browsers)
- Camera permission for photo capture (mobile only)

## 🎮 Usage

### **Logging a Catch**
1. Go to **Log** tab
2. Select species from dropdown
3. Enter length (required)
4. Optionally add: weight, location, lure, photos
5. Date/time auto-populate (editable)
6. Environmental conditions optional
7. Tap **"Log Catch"**
8. Auto-generated fish name appears
9. Click name to edit anytime

### **Viewing History**
- **History** tab shows all catches newest first
- Tap photos for full-screen view
- See K-factor, estimated age, trophy status
- Each fish displays its unique name

### **Using AI Guide**
1. Go to **AI Guide** tab
2. Ask questions like:
   - "How's the day?"
   - "What lures should I use?"
   - "Where should I fish?"
   - "Tell me about water temperature"
   - "What's the best time of day?"
3. Get detailed, research-backed responses

### **Checking Forecast**
- **Forecast** tab shows today's conditions
- Ice status (April tracking)
- Season rating (1-5 stars)
- Current hour bite rating
- Solunar periods with exact times
- Specific tactics for current conditions

### **Analyzing Patterns**
- **Patterns** tab reveals what's working
- Success rates by species
- Top locations
- Best lures
- Moon phase effects
- Optimal conditions

## 📊 Data Export

**CSV Export:**
1. Go to **Analytics** tab
2. Scroll to bottom
3. Tap **"Export CSV"**
4. All catches download as spreadsheet
5. Includes all data fields

**Backup/Restore:**
1. **Analytics** tab → **Backup Data**
2. Saves JSON file with all catches
3. **Restore Data** loads from backup
4. Transfer data between devices

## 🧪 Technologies

- **HTML5** - Structure
- **CSS3** - Styling (no external libraries)
- **Vanilla JavaScript** - All functionality
- **localStorage API** - Data persistence
- **Canvas API** - Photo capture
- **Progressive Web App** - Offline capability

**No dependencies. No frameworks. Just pure web tech.**

## 🔒 Privacy

- **100% private** - All data stays on your device
- No tracking
- No analytics
- No cookies
- No external requests
- No user accounts
- Your data never leaves your browser

## 🐛 Known Issues

- localStorage has ~5-10MB limit (room for hundreds of catches with photos)
- Photos increase storage usage (compress if needed)
- Data tied to browser/device (use backup to transfer)

## 📝 License

MIT License - Feel free to use, modify, and distribute.

## 🙏 Credits

**Research Sources:**
- Kevin VanDam (7x Bassmaster Classic Champion)
- Field & Stream
- Bassmaster Elite Pros
- Mercury Marine
- Wired2Fish
- Dr. David Ross (Woods Hole Oceanographic)
- Minnesota DNR LakeFinder

**Fish Names Inspired By:**
- Flair (YouTube fishing channel)
- BamaBass (YouTube fishing channel)

## 📞 Support

For issues or questions:
1. Check **Troubleshooting** section above
2. Ensure browser supports localStorage
3. Try different browser if issues persist
4. Clear browser cache if UI problems occur

## 🎣 Happy Fishing!

Tight lines and full stringers! 🐟

---

**Version:** 1.0  
**Last Updated:** April 2026  
**Minnesota Fishing Seasons:** Consult MN DNR for current regulations
