# Hockey Equipment Manager

A mobile-friendly web application for hockey equipment managers to manage player rosters and generate organized equipment lists for games.

## Features

- **Load Players**: Import player rosters from JSON files using the file picker
- **Multi-Selection**: Select multiple players for upcoming games using checkboxes
- **Smart Sorting**: Sort players by selected status, jersey number, or player name
- **Equipment Lists**: Generate organized lists showing required jerseys and water bottles
- **Mobile Optimized**: Works great on phones and tablets with touch-friendly interface
- **Local Storage**: Rosters are automatically saved in your browser
- **Quick Selection**: Paste player lists to quickly select existing players

## How to Run

1. Open the `index.html` file in any modern web browser
2. **For desktop**: Double-click the file or drag it into your browser
3. **For mobile**: Transfer the file to your phone and open it in a mobile browser

## Mobile Features

- **Touch-friendly**: Large tap targets and responsive design
- **Mobile-optimized layout**: Adapts perfectly to phone screens
- **PWA-ready**: Can be added to your home screen for app-like experience
- **No installation required**: Works directly in your browser

## How to Use

### Loading Players
1. Click "Load Players" button
2. Select a JSON file containing your player roster
3. The app will automatically load and display the players

### JSON File Format
Your JSON file should contain an array of player objects with the following format:
```json
[
  {
    "name": "John Anderson",
    "number": 7,
    "position": "Forward"
  },
  {
    "name": "Mike Smith",
    "number": 11,
    "position": "Defense"
  }
]
```

### Selecting Players for a Game
1. Click the checkbox next to each player to select/deselect them
2. Use the sort controls to organize players as needed
3. Selected players are highlighted in blue

### Sorting Players
- **Selected Status**: Sort by selected/unselected (players at top/bottom)
- **Jersey Number**: Sort by jersey number (ascending/descending)
- **Player Name**: Sort alphabetically by name (A-Z/Z-A)

### Generating Equipment Lists
1. Select the players playing in the upcoming game
2. Click "Generate Equipment List"
3. The application displays:
   - Jerseys needed (sorted by number)
   - Water bottles needed (sorted by number)
   - Summary with total counts

### Mobile Usage Tips
- **Add to Home Screen**: On iOS, tap the share button and "Add to Home Screen" for app-like access
- **Touch Gestures**: Tap checkboxes to select/deselect players
- **Responsive Design**: The interface adapts automatically to your screen size

### Managing Rosters
- **Auto-Save**: Your roster is automatically saved in your browser's local storage
- **Persistent Storage**: Player data stays even after closing the browser
- **No Manual Save Needed**: Changes are saved instantly as you make them

### Quick Selection
- **Paste Player Lists**: Copy and paste player names/numbers to quickly select them
- **Smart Parsing**: Supports multiple formats like "#7 John Anderson Forward" or "Mike Smith #11"
- **Bulk Selection**: Select multiple existing players from pasted text

## Example Output

When you generate an equipment list, you'll see something like:

```
EQUIPMENT LIST FOR GAME
========================================

JERSEYS REQUIRED:
--------------------
 # 3 - Alex Johnson
 # 4 - Dave Brown
 # 7 - John Anderson
 # 8 - James White

WATER BOTTLES REQUIRED:
--------------------
 # 3 - Alex Johnson
 # 4 - Dave Brown
 # 7 - John Anderson
 # 8 - James White

SUMMARY:
--------------------
Total Players: 4
Jerseys Needed: 4
Water Bottles Needed: 4
```

## Mobile Optimization

The app is specifically designed for mobile use with:
- **Large Touch Targets**: Easy to tap buttons and checkboxes
- **Responsive Layout**: Adapts to any screen size
- **No Zoom Required**: Text is sized appropriately for mobile reading
- **Mobile Gestures**: Native touch interactions
- **PWA Support**: Install as a home screen app on iOS and Android

## Tips

- Use the sort controls to organize players efficiently
- Double-check player counts before heading to the game
- Your roster is automatically saved - no need to manually save
- On mobile, use "Add to Home Screen" for quick access like a native app
- Use the paste feature to quickly select players from emails or messages

## Browser Support

Works on all modern browsers:
- Chrome, Safari, Firefox, Edge
- iOS Safari (iPhone/iPad)
- Chrome Mobile (Android)
- Samsung Internet

No internet connection required after initial load - works completely offline!