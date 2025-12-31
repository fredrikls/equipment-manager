# Hockey Equipment Manager

A mobile-friendly web application for hockey equipment managers to select players for games and generate organized equipment lists.

## Features

- **Player Management**: Add, edit, and remove players from the roster
- **Multi-Selection**: Select multiple players for upcoming games
- **Smart Sorting**: Players are automatically sorted by jersey number
- **Equipment Lists**: Generate organized lists showing required jerseys and water bottles
- **Mobile Optimized**: Works great on phones and tablets with touch-friendly interface
- **Local Storage**: Rosters are automatically saved in your browser
- **Quick Import**: Paste player lists to quickly select or add players

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

### Adding Players
1. Click "Add Player" button
2. Enter player name, jersey number, and position (optional)
3. Click "Add" to save the player

### Selecting Players for a Game
1. Click on players in the list to select them (multi-select enabled)
2. Or double-click to toggle selection
3. Selected players are highlighted

### Generating Equipment Lists
1. Select the players playing in the upcoming game
2. Click "Generate Equipment List"
3. The application displays:
   - Jerseys needed (sorted by number)
   - Water bottles needed (sorted by number)
   - Summary with total counts

### Mobile Usage Tips
- **Add to Home Screen**: On iOS, tap the share button and "Add to Home Screen" for app-like access
- **Touch Gestures**: Tap players to select/deselect, use appropriate buttons for actions
- **Responsive Design**: The interface adapts automatically to your screen size

### Managing Rosters
- **Auto-Save**: Your roster is automatically saved in your browser's local storage
- **Persistent Storage**: Player data stays even after closing the browser
- **No Manual Save Needed**: Changes are saved instantly as you make them

### Quick Import (New Feature)
- **Paste Player Lists**: Copy and paste player names/numbers to quickly add or select them
- **Smart Parsing**: Supports multiple formats like "#7 John Anderson Forward" or "Mike Smith #11"
- **Bulk Operations**: Add multiple players at once or select existing players from pasted text

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
- **Large Touch Targets**: Easy to tap buttons and player items
- **Responsive Layout**: Adapts to any screen size
- **No Zoom Required**: Text is sized appropriately for mobile reading
- **Mobile Gestures**: Native touch interactions
- **PWA Support**: Install as a home screen app on iOS and Android

## Tips

- Players are automatically sorted by jersey number for easy equipment management
- Double-check player counts before heading to the game
- Your roster is automatically saved - no need to manually save
- The app prevents duplicate jersey numbers to avoid confusion
- On mobile, use "Add to Home Screen" for quick access like a native app
- Use the paste feature to quickly import player lists from emails or messages

## Browser Support

Works on all modern browsers:
- Chrome, Safari, Firefox, Edge
- iOS Safari (iPhone/iPad)
- Chrome Mobile (Android)
- Samsung Internet

No internet connection required after initial load - works completely offline!