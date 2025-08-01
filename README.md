# SalaryPredict AI

SalaryPredict AI is a machine learning-powered web application designed to provide accurate salary predictions based on user profiles and market data. This project aims to empower professionals with data-driven insights to make informed career decisions and negotiate salaries confidently.

## Features

- User-friendly web interface with a modern, clean design.
- Interactive home page with global job market visualizations.
- Personalized salary prediction form with detailed user inputs.
- PDF report generation with comprehensive salary and profile details.
- User information capture for personalized experience via modal input.
- Navigation with "Visualizations" button linking directly to market insights.
- Ethical considerations and transparency in AI predictions.
- Responsive design for seamless use on desktop and mobile devices.

## Technology Stack

- Python with Flask for backend API and web server.
- Machine Learning models using scikit-learn and joblib.
- FPDF for PDF report generation.
- HTML, CSS, and JavaScript for frontend UI.
- Google Fonts and Font Awesome for typography and icons.
- Chart.js for interactive data visualizations.

## Getting Started

1. Clone the repository:
   ```
   git clone <repository-url>
   cd SalaryPredictor-main
   ```
2. Set up a Python virtual environment (recommended):
   ```
   python -m venv venv
   venv\Scripts\activate   # On Windows
   source venv/bin/activate  # On macOS/Linux
   ```
3. Install required Python packages:
   ```
   pip install -r requirements.txt
   ```
4. Run the Flask application:
   ```
   python main.py
   ```
5. Open the application in your browser at `http://localhost:5000`.

## Usage Guide

- **Home Page:** View interactive global job market visualizations including salary trends, job demand, and industry distribution.
- **Visualizations Button:** Use the "Visualizations" button in the navbar to quickly navigate to the market insights section on the home page.
- **Predict Salary:** Navigate to the salary prediction form to input your profile details and get a personalized salary prediction.
- **User Info Modal:** On first use, enter your name and location in the modal for a personalized experience.
- **PDF Report:** After prediction, download a detailed PDF report of your salary prediction and profile.

## Project Structure

- `main.py`: Flask backend application.
- `templates/`: HTML templates for the web pages.
- `static/`: Static assets including images and styles.
- Model files (`salary_model.pkl`, `scaler1.pkl`, `label_encoders.pkl`): Pre-trained machine learning assets.

## Future Enhancements

- Expand dataset to include international markets.
- Integrate chatbot for interactive salary queries.
- Improve UI/UX with more personalized recommendations.

## Contribution

Contributions are welcome! Please fork the repository and submit pull requests for improvements or bug fixes.

## License

This project is for educational purposes only and should not be used for commercial applications.

## Disclaimer

Model predictions are based on the provided dataset and may not reflect all market conditions or individual circumstances.

## Live Demo

Access the live application here: https://salary-predict-ai.onrender.com/
