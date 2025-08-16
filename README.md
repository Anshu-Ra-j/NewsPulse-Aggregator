#📰 News App (Kotlin, Open Source)

This is an **open-source News Application** built with **Kotlin** for Android devices (**Android 5.0 Lollipop and above**).  
It fetches live news from [NewsAPI.org](https://newsapi.org) and provides a smooth, modern user experience with caching, search, and multiple viewing options.

---

## 🚀 Features

- **Latest News** powered by [NewsAPI.org](https://newsapi.org).  
- **Default API Key** included in the app. If the key limit is reached, users can provide their own API key from [NewsAPI.org](https://newsapi.org).  
- **MVVM Architecture** for clean code and easy maintainability.  
- **Offline Caching** with Room Database to save and display recently viewed news on the homepage.  
- **Retrofit** for seamless API calls.  
- **Glide** for efficient image loading.  
- **Sensor Support**: Shake your device to swap between **List View** and **Grid View** for browsing news.  
- **Search Functionality** to find news related to any topic.  
- **Category & Channel Filters** for a personalized experience.  





## 🛠️ Tech Stack

- **Language:** Kotlin  
- **Architecture:** MVVM (Model-View-ViewModel)  
- **Database:** Room  
- **Networking:** Retrofit  
- **Image Loading:** Glide  
- **Sensors:** Accelerometer (for shake detection)  


## 🔑 API Key Setup

1. Go to [NewsAPI.org](https://newsapi.org) and create a free account.  
2. Generate your personal API key.  
3. Add it in the app when prompted (if the default key exceeds its usage limit).  

---

## 🌱 Branches

- **main** → Active development  
- **v1** → Version 1 release  

---

## 🏗️ How to Run

1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/News-App.git
Open the project in Android Studio.

Build & Run on an emulator or a physical device (Android 5.0+).

