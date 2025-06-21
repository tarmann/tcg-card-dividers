# One Piece Card Divider Generator

This project is a web-based tool for generating printable card dividers for the One Piece Card Game. It allows you to easily create dividers for all main expansions and starter decks, with support for color-coding and custom set names.

## Features

- **Easy Input:** Enter set ID, set name, and optional colors for each divider, one per line.
- **Automatic Layout:** Dividers are arranged 4 per row, sized for standard card storage boxes.
- **Fold Line:** Each divider includes a fold line for easy folding.
- **Color Stripes:** If a color (or multiple colors) is specified, colored stripes appear on the right side of the divider name.
- **Modern UI:** Clean, user-friendly interface for editing and printing.
- **All Expansions Included:** Includes all One Piece expansions up to OP12 and all starter decks by default.

## Usage

1. **Open `index.html` in your browser.**
2. The editor will show a list of all One Piece expansions and starter decks. You can edit, add, or remove lines as needed.
3. Each line should follow this format:
   - `Set ID; Set Name; Colors (optional)`
   - Example: `OP01; Romance Dawn` or `ST10; The Three Captains; Red/Purple`
4. Click the **Print** button to open the print dialog and print your dividers.

## File Structure

- `index.html` — Main web page and UI.
- `setNames.js` — Contains the default list of set names and starter decks.
- `README.md` — This documentation file.

## Customization

- **Adding Sets:** Add new lines to the textarea in the format described above.
- **Colors:** Supported colors include: Red, Blue, Green, Yellow, Black, Purple, White, Pink, Orange, Brown. You can use multiple colors separated by `/`, `,`, `&`, or spaces.
- **Styling:** You can further customize the look by editing the CSS in `index.html`.

## Printing Tips

- For best results, use A4 or Letter paper and set margins to minimum in your print dialog.
- Use heavier paper or cardstock for more durable dividers.

## License

This project is open source and free to use for personal, non-commercial purposes.
