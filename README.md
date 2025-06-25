# 🧠 MongoDB Database Structure – Level 1 Exercise

## 📄 Description – Exercise Statement

This repository contains the solution for the **Level 1 MongoDB modeling exercise** based on the scenario of an optical store, *Cul d'Ampolla*.  
The goal is to design a NoSQL database using MongoDB to represent clients, their purchases, glasses, and related suppliers and employees.  

**Exercise 2** focuses on viewing the data from the perspective of the glasses, showing their technical data, supplier, and buyers.

## 💻 Technologies Used

- **MongoDB** – NoSQL database
- **MongoDB Compass** – Visual database manager
- **Docker** – For local MongoDB container setup
- **VS Code / Text Editor** – For JSON structure editing
- **Git & GitHub** – Version control and hosting

## 📋 Requirements

To run and interact with this project locally, ensure you have:

- [ ] **Docker** installed (v20+ recommended)
- [ ] **MongoDB Compass** (latest version)
- [ ] **Git** (to clone the repo)
- [ ] A text editor (e.g., VS Code, Sublime, Notepad++)

## 🛠️ Installation

To set up the MongoDB environment:

1. **Clone the repository**  
   ```bash
   git clone https://github.com/JavierDolo/S2.03.Level1_Mongo_Dates_Estrucuture.git
   
   ```

2. **Start MongoDB via Docker**  
   ```bash
   docker run -d -p 27017:27017 --name mongodb mongo
   ```

3. **Open MongoDB Compass**  
   Connect to:
   ```
   mongodb://localhost:27017
   ```

4. **Import the `.json` files** into your collections (`Clients`, `Glasses`, `Suppliers`, etc.).

## ▶️ Execution

Once imported into MongoDB Compass:

- Browse the `Glasses` collection to view glasses data.
- Check embedded supplier information and list of buying clients.
- Use `Aggregations` or `Find` queries to explore relationships.

## 🌐 Deployment

This is a local project for learning purposes. However, to deploy it:

1. Use **MongoDB Atlas** to host your cluster online.
2. Import the data via Compass or `mongoimport`.
3. Share the connection string with collaborators or connect your backend app.

## 🤝 Contributions

Contributions are welcome! If you'd like to improve the structure, add documentation or examples:

1. Fork the repository
2. Create a new branch (`feature/your-feature`)
3. Commit your changes
4. Submit a Pull Request with a clear explanation

---
