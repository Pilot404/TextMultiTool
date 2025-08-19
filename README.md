# QA MultiTool

A comprehensive, browser-based development and testing toolkit designed for QA engineers, developers, and anyone working with data formats. Built with modern web technologies and featuring a sleek dark/light theme interface.

QA MultiTool Screenshots
<img width="2542" height="1259" alt="image" src="https://github.com/user-attachments/assets/7542c42d-d076-41cf-9bb6-210b92195b5d" />
<img width="2531" height="1252" alt="image" src="https://github.com/user-attachments/assets/5c2443c6-0792-43c0-ba6b-46372736ff04" />



## 🚀 Features

### Data Formatting & Validation
- **JSON Beautifier** - Format and validate JSON with syntax highlighting
- **XML Beautifier** - Clean and format XML documents with proper indentation
- **JSON Schema Generator** - Automatically generate JSON Schema from sample data

### Encoding & Decoding
- **Base64 Encoder/Decoder** - Convert text to/from Base64 with UTF-8 support
- **JWT Decoder** - Decode JWT tokens and display header, payload, and signature
- **Smart Content Detection** - Automatically detect and highlight JSON/XML in decoded content

### Text Processing
- **Text Comparison** - Side-by-side diff with visual highlighting of changes
- **Random Text Generator** - Generate random strings with customizable length and character sets
- **UUID Generator** - Generate single or multiple UUID v4 identifiers

### Developer Experience
- **Syntax Highlighting** - Powered by Prism.js for beautiful code display
- **Line Numbers** - Synchronized line numbering for all editors
- **Dark/Light Theme** - Toggle between themes for comfortable viewing
- **Copy & Download** - Easy export of processed results
- **Responsive Design** - Works on desktop and mobile devices

## 🎯 Use Cases

- **API Testing** - Format and validate JSON responses
- **Data Migration** - Convert between formats and validate schemas
- **Security Testing** - Decode JWT tokens and Base64 payloads
- **Documentation** - Generate schemas and format examples
- **Development** - Quick text processing and UUID generation
- **QA Automation** - Prepare test data and validate formats

## 🛠️ Technology Stack

- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Styling**: CSS Custom Properties with theme support
- **Syntax Highlighting**: Prism.js
- **Icons**: Unicode Emojis for universal compatibility
- **No Dependencies**: Self-contained, no build process required

## 🚀 Getting Started

### Quick Start
1. Download the `qa-multitool.html` file
2. Open it in any modern web browser
3. Start using the tools immediately - no installation required!

### Local Development
```bash
# Clone the repository
git clone https://github.com/Pilot404/TextMultiTool.git

# Navigate to project directory
cd tester-helper-app

# Open in browser
open tester-helper-app.html
```

### Browser Compatibility
- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+

## 📖 Usage Examples

### JSON Formatting
```json
// Input (minified)
{"name":"John","age":30,"city":"Prague"}

// Output (formatted)
{
  "name": "John",
  "age": 30,
  "city": "Prague"
}
```

### JWT Decoding
```
// Input
eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIxMjM0NTY3ODkwIiwibmFtZSI6IkpvaG4gRG9lIiwiaWF0IjoxNTE2MjM5MDIyfQ.SflKxwRJSMeKKF2QT4fwpMeJf36POk6yJV_adQssw5c

// Output
=== JWT HEADER ===
{
  "alg": "HS256",
  "typ": "JWT"
}

=== JWT PAYLOAD ===
{
  "sub": "1234567890",
  "name": "John Doe",
  "iat": 1516239022
}
```

### Text Comparison
```
// Text 1
Hello World
Line 2

// Text 2  
Hello Universe
Line 2

// Output
Řádek 1:
- Hello World
+ Hello Universe
```

## 🎨 Features in Detail

### Smart Content Detection
The tool automatically detects content types in Base64 decoded data and applies appropriate syntax highlighting for JSON and XML.

### Theme Support
Switch between dark and light themes with the toggle button. Theme preference is maintained during the session.

### Czech Localization
Interface elements and messages are localized in Czech, making it perfect for Czech development teams.

### Responsive Layout
The tool adapts to different screen sizes while maintaining usability across desktop and mobile devices.

## 🔧 Configuration

### Customizing Text Generator
- **Length**: 1-10,000 characters
- **Character Sets**:
  - Letters only (A-Z, a-z)
  - Numbers only (0-9)
  - Mixed (letters, numbers, symbols)

### UUID Generation
- Generate 1-100 UUIDs at once
- UUID v4 format with proper randomization

## 📝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Development Guidelines
- Follow existing code style
- Add comments in Czech for consistency
- Test across different browsers
- Ensure responsive design
- Update documentation as needed

## 🐛 Bug Reports

Found a bug? Please open an issue with:
- Browser and version
- Steps to reproduce
- Expected behavior
- Actual behavior
- Screenshots (if applicable)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Prism.js](https://prismjs.com/) for syntax highlighting
- [Inter Font](https://rsms.me/inter/) for beautiful typography
- [cdnjs](https://cdnjs.com/) for reliable CDN hosting

## 📊 Project Stats

- **Size**: ~50KB (single HTML file)
- **Load Time**: <1 second
- **Dependencies**: None (self-contained)
- **Browser Support**: 95%+ modern browsers

## 🔮 Roadmap

- [ ] CSV/TSV formatter
- [ ] Hash generators (MD5, SHA-256)
- [ ] Color picker and converter
- [ ] Regular expression tester
- [ ] Timestamp converter

---

**Made with ❤️ for the QA and development community**

If you find this tool useful, please ⭐ star the repository!
