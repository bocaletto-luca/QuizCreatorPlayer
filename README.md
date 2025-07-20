# Quiz Creator & Player

A modern, responsive single-page web app for building, managing, and taking quizzes entirely in the browser. Create, edit, and delete questions and options, mark correct answers, import/export your quizzes as JSON, save locally, and print quizzes for offline use—no external dependencies or build steps required.

---

## 🔗 Live Demo

[View the live demo on GitHub Pages](https://bocaletto-luca.github.io/QuizCreatorPlayer/index.html)

---

## 🚀 Features

- **Fully Featured Quiz Editor**  
  - Add, edit, and delete questions  
  - Create multiple choice options per question  
  - Mark one option as the correct answer  
  - Reorder, remove, or modify any element at any time

- **Real-Time Preview & Print**  
  - Print-ready layout hides UI controls automatically  
  - Instantly preview your quiz in printable form

- **Play Mode**  
  - Seamlessly switch from editor to player  
  - Navigate questions with Next/Previous buttons or keyboard  
  - Submit answers and see your score at the end

- **Local Persistence**  
  - Save your current quiz to LocalStorage with one click  
  - Data persists across sessions without any server

- **Import / Export JSON**  
  - Export your quiz data as a JSON file for sharing or backup  
  - Import any properly formatted quiz JSON to continue editing or playing

- **Responsive & Accessible**  
  - Mobile-first layout using CSS Grid & Flexbox  
  - Semantic HTML, ARIA labels, and keyboard support  

- **Zero Dependencies**  
  - Pure HTML5, CSS3 (Custom Properties), and vanilla JavaScript (ES6+)  
  - No frameworks, libraries, or build tools required

---

## 🛠️ Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge).

### Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/bocaletto-luca/QuizCreatorPlayer.git
   ```
2. **Open in browser**  
   - Navigate into the project folder  
   - Open `index.html` in your favorite browser  

That’s it—no build or install steps required.

---

## 🎯 Usage

1. **Editor Tab**  
   - Click **Editor** in the header to build your quiz  
   - Enter a quiz title, then add questions with the **+ Add Question** button  
   - For each question:  
     - Type the question text  
     - Add options, type each option, and select the correct answer  
     - Remove questions or options with the “×” buttons  

2. **Save & Print**  
   - Click **Save Locally** to store your progress in LocalStorage  
   - Click **Export JSON** to download your quiz data  
   - Click **Import JSON** to load a previously exported quiz  
   - Click **Print Quiz** to open a print-friendly view  

3. **Play Tab**  
   - Click **Play** in the header to switch to quiz mode  
   - Navigate questions with **Next** and **Previous**  
   - Select your answers and click **Submit** on the last question  
   - View your score immediately  

---

## 🧰 Built With

- **HTML5** & **CSS3** (Grid, Flexbox, Custom Properties)  
- **Vanilla JavaScript** (ES6+)  
- **LocalStorage** for data persistence  

---

## 🤝 Contributing

Contributions and feedback are welcome!

1. Fork the repo  
2. Create a feature branch:  
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes:  
   ```bash
   git commit -m "Add awesome feature"
   ```
4. Push to your fork:  
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a Pull Request on GitHub  

---

## 📄 License

This project is licensed under the [GNU GPLv3 License](https://www.gnu.org/licenses/gpl-3.0.en.html).

---

## 👤 Author

**Bocaletto Luca**  
- GitHub: [@bocaletto-luca](https://github.com/bocaletto-luca)  
- Live Demo: https://bocaletto-luca.github.io/QuizCreatorPlayer/index.html

Feel free to star ⭐ the repository if you find it useful!
