# D3SKTOP 🎨

Hey there! Welcome to D3SKTOP, a cute desktop-style interface template.

## ✨ What's Inside

- A nostalgic desktop environment with all the good stuff - taskbar, start menu, and windows you can drag around
- Windows that actually work! Minimize, maximize, close - just like the real thing
- Scales nicely on different screens (though it loves desktop the most, as you'd expect)
- Status cards to show what you're up to
- Easy-to-setup navigation icons
- A cute sticky notes section for your updates

## 🚀 Let's Get Started

1. Grab these files
2. Drop in these dependencies (they're all free!):
   - Font Awesome 6.5.1 (for those nice icons)
   - Pangolin from Google Fonts (for that perfect look)

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
<link href="https://fonts.googleapis.com/css2?family=Pangolin&display=swap" rel="stylesheet">
```

3. Put your content in the modal windows (`index.html`)
4. Make it yours by tweaking the colors in `styles.css`

## 🎨 Make It Your Own

### Colors

Want different colors? Super easy! Just find these variables at the top of `styles.css` and change them to whatever makes you happy:

```css
:root {
    --color-primary: #e89098;     /* Current: Salmon pink */
    --color-secondary: #c77984;   /* Current: Darker salmon */
    --color-background: #93b1b4;  /* Current: Sage green-blue */
    /* ...and more! */
}
```

### Adding Your Own Windows

1. Need a new window? Here's how to add one to `index.html`:
```html
<div class="modal" id="your-modal-id">
    <div class="modal-header">
        <h3 class="modal-title">Your Title</h3>
        <div class="modal-controls">
            <button class="minimize-button"><i class="fas fa-minus"></i></button>
            <button class="fullscreen-button"><i class="fas fa-expand"></i></button>
            <button class="close-button">×</button>
        </div>
    </div>
    <div class="modal-content">
        <!-- Whatever you want goes here! -->
    </div>
</div>
```

2. Don't forget its icon:
```html
<div class="nav-icon" data-modal="your-modal-id">
    <div class="icon-box">
        <i class="fas fa-your-icon"></i>
    </div>
    Your Window Name
</div>
```

## 🖥️ Browser Support

Should work on modern desktop browsers, but tested mainly in:
- Chrome Desktop
- Firefox Desktop

Your mileage may vary in other browsers!

## 🔧 Core Files

- `index.html` - Where everything comes together
- `styles.css` - All the pretty stuff lives here
- `script.js` - Makes all the windows and buttons work

## 📜 License

This template is released under CC0 1.0 Universal (CC0 1.0). This means:
- You can use it for personal or commercial projects
- No attribution required
- You can modify, distribute, and use it however you want
- You can even sell works that use this template

For more details about CC0 1.0 Universal, visit: https://creativecommons.org/publicdomain/zero/1.0/

## ⚠️ Important Notes

- This is strictly a desktop-only template - no mobile support at all (hey, it's meant to be a desktop after all!)
- The code isn't the prettiest - it's a fun project that works, but could use some cleanup if you're planning to build on it
- For best results, use this as a starting point and refactor/improve as needed for your specific use case
- The template requires a decent screen size to look right - no guarantees on smaller displays

## 📮 Questions?

Thanks for checking out D3SKTOP! Did you run into any problems? Just wanted to say hi? I'd love to hear from you! Drop me a line at pollygondev@gmail.com or comment on the itch page!

## 🖼️ Background Art Credit

The lovely background image (`free.png`) was created by Sorin (@nobuchikaginoza on Twitter). They've kindly made it free for anyone to use without needing credit - how cool is that?

Want to customize the background? We've got you covered! The template includes:
- The original `.clip` file for Clip Studio Paint users
- A `.psd` file for Photoshop users
- The final `.png` image

Feel free to edit and customize the background to match your style using whichever format works best for you!

---

Made with ❤️ for all you creative folks out there!