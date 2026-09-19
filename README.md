# AutoValue AI - Vehicle Resale Price Prediction System

AutoValue AI is an AI-powered vehicle resale price prediction and appraisal platform combining Supervised Machine Learning regression with Generative AI assistance.

## Overview
- **Predictive Engine:** Supervised Gradient Boosting Regressor (R² = 0.948) evaluating vehicle specifications (brand, model, vintage age, mileage, fuel type, transmission, market trend index).
- **Conversational Valuation Assistant:** Natural language query processor extracting vehicle attributes from free-text prompts.
- **Price Explanation Generator:** Generates natural language factor breakdowns translating model feature weights into human insights.
- **Executive Valuation Report:** Comprehensive appraisal summary with dynamic narrative templates, net proceeds calculation, and interactive 5-star rating feedback.
- **Comparable Market Recommendations:** Real-time similar vehicle comparison cards with match scores.

## Tech Stack
- Frontend: HTML5, Vanilla CSS3 (Dark Glassmorphism UI, Responsive Grid), Vanilla ES6+ JavaScript
- Runtime: Node.js static server or any standard web server

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/Gowrish2507/AutoValue-AI---Vehicle-Resale-Price-Prediction-System.git
   cd AutoValue-AI---Vehicle-Resale-Price-Prediction-System
   ```
2. Start the local server:
   ```bash
   node server.js
   ```
3. Open your browser and navigate to:
   ```
   http://localhost:3000/
   ```
   *(Or simply open `index.html` directly in your browser)*
