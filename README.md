# EEE6208 Interactive Review Guide


**[View in Chinese](README_zh.md)**


## Project Description

This is an interactive review guide for EEE6208 Digital Circuits, supporting both English and Chinese languages.

---

## Main Features

### 🌐 Multilingual Support
- **English Primary**: Default display in English
- **Chinese Toggle**: Click the "中文" button in the top-right corner to switch to Chinese
- **Real-time Switching**: All content (including interactive analysis results) updates language in real-time

### 📚 Learning Modules

1. **MOSFET Basics**
    - Interactive NMOS operating region analyzer
    - Real-time calculation and display of transistor operating status

2. **CMOS Logic Design**
    - Complex logic gate generator
    - Visualization of PUN/PDN network structures

3. **Delay Analysis**
    - Logical effort delay visualization
    - Interactive parameter adjustment

4. **Advanced Logic**
    - PTL voltage drop simulator
    - Weak keeper operation demonstration

5. **Circuit Testing**
    - Stuck-at fault simulator
    - Test vector analysis

6. **Expert Questions**
    - Critical path optimization
    - Asymmetric transistor sizing design

---

## How to Use

1. **Start the Project**
    ```bash
    # Use Python to start a local server
    python3 -m http.server 8000

    # Or use Node.js
    npx http-server
    ```

2. **Access the Application**
    - Open your browser and navigate to `http://localhost:8000`
    - The English version will be displayed by default

3. **Switch Language**
    - Click the language toggle button in the top-right corner of the page
    - All content will immediately update to the selected language

4. **Interactive Learning**
    - Click the navigation bar to switch between different topics
    - Use various interactive tools for learning
    - Observe the real-time impact of parameter changes on results

---

## Technical Features

- **Responsive Design**: Adapts to various screen sizes
- **Real-time Interaction**: All analysis results update in real-time
- **Visual Charts**: Uses Chart.js for interactive chart plotting
- **Modern UI**: Built with Tailwind CSS for an appealing interface
- **Dependency-free**: Pure frontend implementation, no backend service required

---

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

---

## Project Structure

├── index.html          # Main application file

├── README.md           # Project description

└── .git/               # Git version control


---

## Development Notes

- Uses HTML5, CSS3, JavaScript ES6+
- Adopts a modular design for easy maintenance and expansion
- Supports adding more language versions
- Expandable with more interactive learning modules

---

## License

This project is for educational purposes only.
