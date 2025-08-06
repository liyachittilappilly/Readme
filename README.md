

# ReadMe - Study Assistant

A minimalist, pinkish cream-themed web application that reads text aloud, helping students listen to their notes while working on assignments. Save time by listening to your materials instead of constantly looking back and forth between your notes and your work.

<img src="Screenshot 2025-08-06 105830.png" width="500">

## Features

- **Text-to-Speech**: Convert any text into spoken words
- **Voice Selection**: Choose from multiple available voices on your system
- **Adjustable Reading Speed**: Control how fast the text is read (Slow, Normal, Fast, Very Fast)
- **Playback Controls**: Start, pause/resume, and stop reading
- **Spacebar Shortcut**: Press spacebar to pause/resume reading at any time
- **Responsive Design**: Works on both desktop and mobile devices
- **Minimalist Pinkish Cream Theme**: Clean, aesthetic interface with a soft color palette

## How to Use

1. Paste your notes or assignment text into the text area
2. Select your preferred voice from the dropdown menu
3. Choose your desired reading speed
4. Click "Start Reading" to begin
5. Press the spacebar to pause/resume reading at any time
6. Click "Stop" to end the reading session

## Technologies Used

- HTML5
- CSS3 with custom properties (variables)
- Vanilla JavaScript
- Web Speech API (SpeechSynthesis)

## How to Run

1. Clone this repository to your local machine
   ```bash
   git clone https://github.com/yourusername/text-reader.git
   ```
2. Navigate to the project directory
   ```bash
   cd text-reader
   ```
3. Open the `index.html` file in your web browser

Alternatively, you can use a local development server like Live Server in VS Code:
1. Install the Live Server extension in VS Code
2. Right-click on `index.html` and select "Open with Live Server"

## Browser Compatibility

This application uses the Web Speech API, which is supported in most modern browsers:
- Chrome (recommended)
- Edge
- Safari

Note: Some voices may not be available in all browsers.

## Customization

### Changing the Background Image

To change the background image, edit the following line in the CSS section of `index.html`:

```css
--bg-image: url('https://images.unsplash.com/photo-1497366754035-f200968a6e72?ixlib=rb-4.0.3&auto=format&fit=crop&w=2000&q=80');
```

Replace the URL with your desired image URL.

### Adjusting the Color Scheme

To customize the color scheme, modify the CSS variables in the `:root` section:

```css
:root {
    --primary-pink: #f8c4c4;
    --light-pink: #ffd1dc;
    --dark-pink: #e09e9e;
    --cream: #fff8f0;
    --text-dark: #555555;
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

## Acknowledgments

- Background image from Unsplash
- Icons and design elements are custom-built for this project

---

Made with ❤️ for students who want to study more efficiently.
