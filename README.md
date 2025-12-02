# Centered Bookmarks

Centers the bookmarks toolbar under the search bar for a cleaner, balanced look in Zen Browser.

## Features

- Centers all bookmarks in the bookmarks toolbar
- Adds consistent spacing between bookmark items
- Maintains responsive design
- Non-intrusive styling

## Installation

### Manual Installation

1. Open Zen Browser and navigate to `about:support`
2. Find the "Profile Folder" and click "Open Folder"
3. Create a folder named `chrome` if it doesn't exist
4. Copy `userChrome.css` into the `chrome` folder
5. Restart Zen Browser

### Via Zen Mods (if approved)

Install directly through the Zen Browser Mods Store once this mod is approved.

## Customization

You can adjust the spacing between bookmarks by editing the `userChrome.css` file and changing the `margin-inline` value:

```css
#PlacesToolbarItems > .bookmark-item {
  margin-inline: 4px !important; /* Adjust spacing here */
}
```

## Compatibility

- Compatible with Zen Browser (all versions)
- Works with other userChrome mods
- No preference configuration required

## Screenshots

<img width="1466" height="112" alt="{A34063B6-415C-4974-9826-637406311F10}" src="https://github.com/user-attachments/assets/1c05c787-1e3e-424b-a190-e307b85ede3c" />


## Support

If you encounter any issues or have suggestions, please open an issue on the GitHub repository.

## License

MIT License - See LICENSE file for details
