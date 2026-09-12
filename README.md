# 🎓 Smart Teacher Finder

**Bridging the gap between students and the perfect educators through intelligent, location-based matching.** 🚀

Developed for the **Smart India Hackathon (SIH)**, the Smart Teacher Finder is a comprehensive, full-stack web portal designed to revolutionize how parents and students discover local tutoring talent. Finding the right tutor often involves navigating fragmented networks, unpredictable pricing, and scheduling conflicts. This platform solves that by serving as a centralized, transparent hub where educational needs meet expert availability in real-time.

Built with a robust Django backend, the application utilizes an intelligent matching engine that evaluates subject expertise, hourly rates, and geographic proximity to deliver highly personalized recommendations. By integrating HTMX, the platform achieves a blazing-fast, dynamic user experience with instant filtering and search results—delivering the smooth feel of a Single Page Application (SPA) without the overhead of heavy JavaScript frameworks.

### ✨ Key Features

* **🔍 Intelligent Matching Engine:** Advanced, multi-parameter search capabilities (powered by `django-filter`) allow users to seamlessly sift through tutor profiles based on specific academic subjects, budget constraints, and availability.
* **📍 Location-Based Discovery:** Integrated with Geopy, the platform calculates real-world distances to prioritize and recommend educators situated in the student's immediate vicinity.
* **⚡ Blazing Fast, Reactive UI:** Extensive use of **HTMX** ensures that UI updates, live searches, and form submissions happen asynchronously without jarring full-page reloads, resulting in a premium user experience.
* **👨‍🏫 Dedicated User Dashboards:**
* *Student Portal:* Easily manage tutoring requests, view upcoming sessions, and leave feedback.
* *Teacher Portal:* A comprehensive suite for tutors to update their real-time availability, manage incoming session requests, track fees, and monitor their ratings.


* **🛡️ Secure & Scalable Backend:** Leverages Django's powerful built-in ORM for secure database management, custom user authentication, and a fully-featured administrative panel for platform moderation.

### 🛠️ Tech Stack & Architecture

* **Backend:** Python 🐍, Django 🚂
* **Frontend:** HTML5 📄, CSS3 / Bootstrap 🎨, HTMX 🔥
* **Database & Search:** Django ORM 🗄️, `django-filter` 🔎
* **Geolocation:** Geopy 🌍 (for spatial calculations and proximity mapping)

### 🏆 Project Motivation

This project was conceptualized and engineered for the **Smart India Hackathon (SIH)** to address real-world accessibility issues in the education sector. It aims to democratize quality education by making it incredibly simple for localized communities to connect, learn, and grow together.
