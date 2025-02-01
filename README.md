# 📦 Home Inventory Recipes

Home Inventory Recipes is a smart recipe suggestion app that helps you cook delicious and healthy meals based on the ingredients you already have at home. With features like barcode scanning, dietary filters, and an AI-powered recipe generator, meal planning has never been easier!

## 🚀 Features

- ✅ **Automatic Recipe Suggestions** – Get recipe recommendations as soon as your inventory updates.
- ✅ **Barcode Scanning** – Quickly add ingredients to your inventory.
- ✅ **Smart Shopping List** – Know what ingredients you're missing for a recipe.
- ✅ **Nutritional Breakdown** – View calories, macros, and health insights.
- ✅ **Dietary Filters** – Search for vegan, keto, gluten-free, and other specialized recipes.
- ✅ **AI-Powered Recipe Generation** – Can't find a recipe? Let AI create one for you!
- ✅ **Meal Planning** – Schedule meals for the week and stay organized.

## 🏗️ Tech Stack

- **Frontend:** React Native (Expo)
- **Backend:** FastAPI
- **Database:** MongoDB
- **API Integration:** Spoonacular API for recipes
- **Deployment:** Docker

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/yourusername/home-inventory-recipes.git
cd home-inventory-recipes
```

### 2️⃣ Setup Backend

```sh
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

### 3️⃣ Setup Frontend

```sh
cd frontend
npm install
npm start
```

### 4️⃣ Run with Docker

```sh
docker-compose up --build
```

## 📜 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Feel free to open issues and pull requests to improve the app.
