# AI Fitness Buddy 🧘‍♀️

An AI-powered fitness companion that helps you track calories and plan diets using advanced image analysis and personalized recommendations.

![AI Fitness Buddy](https://img.shields.io/badge/React-19.2.0-blue) ![Vite](https://img.shields.io/badge/Vite-7.2.4-purple) ![Gemini AI](https://img.shields.io/badge/Gemini-2.5--flash-orange)

## ✨ What It Does

AI Fitness Buddy is your personal AI trainer and nutritionist in one app. Using Google's Gemini AI, it provides two main features:

- **Calorie Counter**: Upload a photo of your food and get instant calorie estimates with nutritional breakdown
- **Diet Planner**: Generate customized gym diet plans based on your goals, preferences, and budget

## 🚀 Key Features

- **Smart Image Analysis**: Advanced AI vision to identify food and estimate calories
- **Personalized Diet Plans**: Tailored meal plans for weight loss, maintenance, or muscle gain
- **Multiple Diet Types**: Support for vegetarian, non-vegetarian, vegan, and other preferences
- **Budget-Aware**: Diet suggestions that consider your budget constraints
- **User-Friendly Interface**: Clean, intuitive design with smooth animations
- **Real-Time Results**: Instant analysis and plan generation

## 🛠️ Installation

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Google Gemini API key (free from [Google AI Studio](https://aistudio.google.com/app/apikey))

### Setup Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/anshul280929/AI-Fitness-Buddy.git
   cd ai-fitness-buddy
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**

   Navigate to `http://localhost:5173`

## 📖 Usage

### Getting Started

1. Launch the app and enter your Google Gemini API key when prompted
2. Choose between "Calorie Counter" or "Gym Diet Plans"

### Calorie Counter

1. Click on the "Calorie Counter" tab
2. Upload a clear photo of your food
3. Click "Analyze Food" to get instant results
4. View estimated calories, nutritional breakdown, and fun descriptions

### Diet Planner

1. Switch to the "Gym Diet Plans" tab
2. Fill in your details:
   - Gender
   - Current weight (kg)
   - Fitness goal (Weight Loss, Maintenance, Muscle Gain)
   - Diet preference (Vegetarian, Non-Vegetarian, etc.)
   - Budget level
   - Plan duration (days)
3. Click "Generate Diet Plan"
4. Review your personalized meal plan with daily breakdowns

## 🔧 Development

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

### Project Structure

```
src/
├── components/
│   ├── ImageAnalyzer.jsx    # Calorie counter component
│   └── DietPlanner.jsx      # Diet planning component
├── services/
│   └── GeminiService.js     # AI integration service
├── App.jsx                  # Main application component
└── main.jsx                 # Application entry point
```

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details on:

- Reporting bugs
- Suggesting features
- Submitting pull requests
- Code style guidelines

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

- **Issues**: Report bugs or request features on [GitHub Issues](https://github.com/anshul280929/AI-Fitness-Buddy/issues)
- **Discussions**: Join community discussions on [GitHub Discussions](https://github.com/anshul280929/AI-Fitness-Buddy/discussions)

## 👥 Maintainers

- **Anshul** - [GitHub](https://github.com/anshul280929)

---

Made with ❤️ by Anshul Bhaskar
