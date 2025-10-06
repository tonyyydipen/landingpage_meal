# 🍽️ KhanaGenie — Your AI-Powered Food Optimizer

🪄 **Snap. Track. Eat Smart.**  
KhanaGenie is your personal AI companion that helps you eat smarter, track your meals, manage expenses, and stay healthy — all in one colorful, intelligent dashboard.

---

## 🌟 Overview
KhanaGenie combines AI-powered food detection, nutrition insights, expense tracking, and habit streaks into one interactive, fun web experience.  
Simply upload your food photo — KhanaGenie detects what you’re eating, logs it, analyzes your health trends, and gives personalized insights like a foodie genie! 🧞‍♀️

---

## 🧠 Core Features

### 📸 AI Food Detection
- Upload or click a photo of your meal 🍱  
- Detects food items using **Clarifai / Google Vision API**  
- Displays detected food, calories, and nutrition facts instantly  
- Add your meal type and expense with one tap  

### 📊 Intelligent Dashboard
- Central hub showing your **daily progress**  
- **Donut chart** for proteins–carbs–fats  
- **GitHub-style streak calendar** with vibrant icons 🔥  
- Animated **health score meter**  
- Achievement badges for milestones 🏅  
- Motivational daily quote: *“You are what you eat — make it count!”*  

### 💰 Smart Expense Tracking
- Add cost per meal or ingredient  
- Categorize spending (groceries, dine-in, delivery)  
- Bar & pie charts for weekly/monthly spending  
- Track budget goals with reminders 💸  

### 🧬 Health Analytics
- Weekly nutrition reports: protein, carbs, fat balance  
- Percentage breakdowns visualized using **Chart.js**  
- AI-generated insights like:  
  > “You consumed 70% healthy meals this week — great balance!”  
- Motivational feedback and habit insights  

### 🍳 Recipe & Fridge Genie
- Add ingredients you have 🍅  
- Suggests recipes using **Spoonacular API** or a local recipe database  
- Shows **“Waste Reduction”** ideas for near-expiry foods ♻️  

### ⚙️ Settings & Profile
- Profile customization (name, avatar, health goals)  
- Notification settings for meal reminders ⏰  
- Theme toggles (light/dark mode)  
- Secure data management  

---

## 🧩 Tech Stack

| Layer               | Technology                                    |
|--------------------|-----------------------------------------------|
| Frontend           | HTML, CSS, JavaScript                         |
| AI APIs            | Clarifai / Google Vision for image detection |
| Nutrition API      | Edamam / Spoonacular                           |
| Charts             | Chart.js                                      |
| Backend (optional) | Flask or Node.js                              |
| Database           | Firebase / MongoDB                             |
| Hosting            | GitHub Pages / Vercel                          |

---

## 📚 Future Scope
- 🤖 Personalized diet advice using AI  
- 🩺 Integration with Google Fit / Fitbit  
- 📦 Barcode scanner for packaged foods  
- 🗓️ Meal planner with calendar integration  
- 🗣️ Voice-based food logging  

---

## 👩‍💻 Contributors

| Name                     | Role / Pages                                         | Key Modules |
|--------------------------|-----------------------------------------------------|-------------|
| **Nandini Yedelli**       | Food Detection / Upload Page <br> Food Log Page     | - Camera/file upload, API integration (Clarifai/Google Vision) <br> - Display detected food + add expense option <br> - List of meals, filter by date/meal type <br> - Edit/delete entries, expense association |
| **Samiksha Chavan**       | Dashboard Page <br> Settings & Profile Page        | - Central hub with daily summary, streaks, health score <br> - User profile management, app settings, dark mode toggle |
| **Christina Esther Nadar**| Health Analytics Page <br> Recipes & Fridge Inventory Page | - Weekly/monthly food health analysis <br> - Nutritional breakdown charts, motivational insights <br> - Ingredient input, API integration (Spoonacular/Edamam) <br> - Recipe suggestion cards |
| **Taniya Renjarla**       | Landing & Authentication Pages <br> Expense Tracking Page | - Home / Landing page (intro, features, signup CTA) <br> - Login & Signup pages (user authentication flow) <br> - Meals Reminders & Streaks <br> - Expense input, categories (groceries/dining/delivery) <br> - Charts for daily/weekly/monthly spending |
