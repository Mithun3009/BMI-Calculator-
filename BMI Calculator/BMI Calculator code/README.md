# BMI Calculator (Python + Pyodide)

A simple, browser-based BMI Calculator that uses Python (via Pyodide) for core logic and HTML/CSS/JavaScript for the user interface. No server-side code required.

## Features
- Enter height (meters) and weight (kilograms) to calculate BMI.
- Categorizes BMI as Underweight, Normal, Overweight, or Obese (WHO standards).
- Modular Python code: input validation, calculation, classification, and formatting.
- Clean, responsive UI with Tailwind CSS.
- Color-coded results by BMI category.
- Handles invalid/empty/negative inputs with clear error messages.
- "Clear" button to reset the form.
- Runs entirely in the browser using Pyodide.

## Usage
1. Open `index.html` in any modern web browser.
2. Enter your height (in meters) and weight (in kilograms).
3. Click **Calculate** to see your BMI and category.
4. Click **Clear** to reset the form.

## Example
- **Input:** Weight: 70kg, Height: 1.75m
- **Output:** BMI: 22.86 (Normal)

## Project Structure
- `index.html`: Contains all HTML, CSS (via Tailwind CDN), JavaScript, and Python modules (as `<script type="text/pyodide">`).
- `.github/copilot-instructions.md`: Copilot custom instructions for this workspace.

## Technical Notes
- All Python code is modular and embedded in the HTML file for Pyodide.
- No server or backend required.
- Compatible with all modern browsers.

---

**Developed as a demonstration of Python-in-the-browser and modular web app design.**
