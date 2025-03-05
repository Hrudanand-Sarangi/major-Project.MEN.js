# **Full-Stack Web Application**

## 🚀 **Project Overview**
This is a **full-stack web application** that allows users to **create, manage, and review listings**. It features **secure user authentication, cloud image storage, and a dynamic UI**, making it a powerful and scalable solution for various listing-based applications.

---

## 🌟 **Key Features**
- 🔐 **User Authentication** – Secure login & registration using **Passport.js & Express-Session**.
- 📍 **Listings Management** – Users can **create, edit, and delete listings** with detailed descriptions.
- 🖼️ **Image Upload & Storage** – Integrated **Cloudinary** for seamless media management.
- ⭐ **Reviews & Ratings** – Users can leave **reviews with ratings**, ensuring community engagement.
- 🛡️ **Validation & Security** – Implemented **Joi validation & custom Express error handling**.
- 🌍 **Responsive UI** – Designed with **EJS templating** for smooth user experience.
- 🗄️ **MongoDB Database** – Efficient data storage using **Mongoose ORM**.

---

## 🛠️ **Tech Stack**
### **Frontend:**
- EJS (Embedded JavaScript Templating)
- Bootstrap / CSS

### **Backend:**
- Node.js & Express.js
- Passport.js (Authentication)
- Joi (Validation)

### **Database & Cloud Services:**
- MongoDB (Mongoose ORM)
- Cloudinary (Image Storage)

---

## 📂 **Project Structure**
```
|-- models/
|   |-- listing.js  # Schema for Listings
|   |-- review.js   # Schema for Reviews
|
|-- routes/
|   |-- listings.js  # Routes for Listings CRUD operations
|   |-- reviews.js   # Routes for Reviews CRUD operations
|
|-- public/
|   |-- styles/   # CSS Files
|
|-- views/
|   |-- listings/  # EJS Templates for Listings
|   |-- reviews/   # EJS Templates for Reviews
|
|-- middleware.js  # Custom Middleware (Authentication, Error Handling)
|-- cloudConfig.js  # Cloudinary API Configuration
|-- index.js  # Main Server File
|-- schema.js  # Validation Schemas using Joi
|-- package.json  # Dependencies & Scripts
```

---

## 🚀 **Installation & Setup**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/Hrudanand-Sarangi/MejorProject.git
cd MejorProject
```

### **2️⃣ Install Dependencies**
```bash
npm install
```

### **3️⃣ Configure Environment Variables**
Create a `.env` file and add the following:
```env
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
SESSION_SECRET=your_secret
```

### **4️⃣ Run the Server**
```bash
npm start
```
The server will run at **http://localhost:8080/**.

---

## 📜 **Future Improvements**
- ✅ Add **real-time chat functionality** for better user interaction.
- ✅ Implement **OAuth (Google/Facebook login)** for easier authentication.
- ✅ Improve **UI with React.js** for a more dynamic experience.

---

## 🤝 **Contributing**
Pull requests are welcome! Feel free to **fork the repository and submit your improvements.**

---

## 📩 Contact
📧 **Email:** hn.sarangi96@gmail.com  
🔗 **GitHub:** [Your GitHub Link]  
🔗 **LinkedIn:** [Your LinkedIn Link]  

---

⭐ **If you like this project, give it a star!** ⭐

