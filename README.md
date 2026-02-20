# Television — Roald Dahl (Visual Poem)

A single-file static webpage that presents Roald Dahl's poem "Television" with a vintage/print-inspired layout and subtle animations.

## ⚠️ Copyright & Legal Notice

**IMPORTANT:** This project contains the full text of "Television" by Roald Dahl from *Charlie and the Chocolate Factory* (1964). 

- **The poem text is © The Roald Dahl Story Company Limited**
- This visualization is created for **educational and non-commercial purposes** under fair use principles
- This project is **NOT authorized** or endorsed by The Roald Dahl Story Company Limited
- If you plan to host, distribute, or use this project publicly or commercially, **you must obtain proper permissions** from the copyright holder

**By using this code, you acknowledge that:**
- You are responsible for ensuring your use complies with applicable copyright laws
- The creator of this visualization (Keagan Gilmore) makes no warranties about the legality of any particular use
- You agree to indemnify and hold harmless the creator from any copyright claims

## 📋 Project Information

- **Repository:** [github.com/KeaganGilmore/roald-dahl-television-poem-vis](https://github.com/KeaganGilmore/roald-dahl-television-poem-vis)
- **Author:** Keagan Gilmore
- **Contact:** keagangilmore@gmail.com
- **License:** MIT (code only - does NOT include the poem text)

## 📂 Contents

- `index.html` — Complete static page (HTML + embedded CSS) that renders the poem and visuals
- `LICENSE` — Repository license for the code (see file for details)
- `DONATIONS.md` — Donation information
- `README.md` — This file

## 🚀 Quick Start (View Locally)

### Option 1: Open directly in browser
Simply double-click `index.html` or run:
```bash
open index.html
```

### Option 2: Local HTTP server
Using Python 3 (macOS/Linux/Windows):
```bash
python3 -m http.server 8000
# Then open http://localhost:8000/ in your browser
```

Using Node.js:
```bash
npx serve
```

## ✨ What You'll See

- Typographic layout using Google Fonts (Playfair Display + Courier Prime)
- Stylized retro television graphic with animated scanlines and static
- Staggered stanza reveal animations
- Themed sections (TV warning, shouting emphasis, reading/book list, finale)
- Aged paper texture overlay
- Responsive design optimized for modern browsers

## 🎨 Development Notes

### Architecture
- All styles are embedded in `index.html` inside a `<style>` block
- CSS variables at the top for easy color customization
- No external dependencies except Google Fonts

### Key Animations
- `flicker` — Subtle TV body flicker effect
- `scanlines` — Moving scanlines over the TV screen
- `staticMove` — Simulated static movement
- `fadeUp` / `popIn` — Stanza reveal animations with staggered delays

### Customization
To change colors, modify CSS variables in the `:root` selector:
```css
:root {
    --cream: #f5f0e8;
    --dark: #1a1208;
    --tv-glow: #4af;
    --warm: #c8602a;
    --gold: #d4a847;
    --book-green: #2d5a27;
}
```

## 🔮 Suggested Next Steps

- **Copyright compliance:** If hosting publicly, obtain permission or replace with public domain/original text
- **Extract CSS:** Move styles to separate `styles.css` file for larger projects
- **Responsive tweaks:** Add mobile-specific optimizations
- **Print styles:** Add `@media print` rules for printable versions
- **Accessibility:** Add ARIA labels and improve screen reader support

## 🤝 Contributing

Small tweaks and visual improvements are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test in multiple browsers
5. Submit a pull request

## 📜 Disclaimer

THIS SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

The use of copyrighted poem text is at your own risk. The author of this code assumes no responsibility for copyright infringement by users of this code.

## 📞 Contact

- **GitHub:** [@KeaganGilmore](https://github.com/KeaganGilmore)
- **Email:** keagangilmore@gmail.com
- **Project URL:** https://github.com/KeaganGilmore/roald-dahl-television-poem-vis

---

*This is a fan-made educational project and is not affiliated with or endorsed by Roald Dahl, The Roald Dahl Story Company Limited, or any of their affiliates.*
