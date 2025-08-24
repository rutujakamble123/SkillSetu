# SkillSetu
SkillSetu – A responsive web platform connecting local talent with businesses. Features talent showcase, service listings, secure auth, testimonials, and Firebase-integrated contact form. Built with HTML, CSS, JS, Bootstrap &amp; Firebase to empower professionals and bridge skill seekers with providers.

# SkillSetu – A Local Talent Platform  

🚀 **SkillSetu** is a responsive web platform that connects local talent with businesses and individuals in need of their skills. Built with modern web technologies, SkillSetu empowers professionals to showcase their expertise, helps users find trusted service providers, and bridges the gap between skill seekers and providers.  

---

## ✨ Features  
- 📱 **Responsive Design** – User-friendly and mobile-first interface.  
- 👨‍🎨 **Talent Showcase** – Professionals can display their skills and services.  
- 🔐 **Secure Authentication** – Login & signup system.  
- ⭐ **Testimonials & Reviews** – Build trust with genuine feedback.  
- 📩 **Contact Form with Firebase** – Easy communication and lead capture.  

---

## 🔧 Tech Stack  
- **Frontend**: HTML, CSS, JavaScript, Bootstrap  
- **Backend/Database**: Firebase (Realtime Database / Firestore)  
- **Hosting**: GitHub Pages (or Firebase Hosting)  

---

## 📂 Project Structure  
SkillSetu/
│── index.html # Homepage
│── about.html # About Us page
│── events.html # Events page (if added)
│── contact.html # Contact page with Firebase form
│── assets/ # Folder for images, icons, and other assets
│── css/ # Stylesheets
│── js/ # JavaScript files
│── README.md # Project documentation


---

## ⚡ Firebase Setup (Optional)  
1. Go to [Firebase Console](https://console.firebase.google.com/).  
2. Create a new project → Add a Web App.  
3. Copy your Firebase config (API key, project ID, etc.).  
4. Add the Firebase SDK in your `index.html`:  

```html
<script src="https://www.gstatic.com/firebasejs/9.0.0/firebase-app.js"></script>
<script src="https://www.gstatic.com/firebasejs/9.0.0/firebase-database.js"></script>

<script>
  const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
    databaseURL: "https://YOUR_PROJECT_ID.firebaseio.com",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_PROJECT_ID.appspot.com",
    messagingSenderId: "YOUR_SENDER_ID",
    appId: "YOUR_APP_ID"
  };

  firebase.initializeApp(firebaseConfig);
</script>

🚀 How to Run Locally
Clone the repository:
git clone https://github.com/your-username/SkillSetu.git

Open the project folder:
cd SkillSetu

Open index.html in your browser.

📌 Future Enhancements

Add user dashboards for talent & businesses.
AI-based skill recommendations.
Integrated payment gateway.

📄 License
This project is currently not licensed. All rights reserved by the author.

👩‍💻 Author

Rutuja Kamble
🌐 Web Developer | Ex-System Engineer @ Infosys | Exploring New Opportunities

📌 GitHub: https://github.com/rutujakamble123

📌 LinkedIn: https://www.linkedin.com/in/rutuja-kamble-7a3452190
