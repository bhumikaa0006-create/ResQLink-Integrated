# 🚨 ResQLink — Smart Disaster Rescue & Emergency Response

**ResQLink** is a disaster-response and emergency assistance platform designed to help people access essential rescue resources, communicate emergency information, and locate nearby shelters during disasters.

Built with a focus on accessibility, real-time information, and mobile usability, ResQLink aims to make emergency assistance more organized and accessible when it matters most.

## 🌍 Problem Statement

During natural disasters and other emergencies, people may struggle to find nearby shelters, communicate their location, and access reliable rescue information. Network disruptions can make these challenges even harder.

ResQLink aims to bring essential emergency-response features together in one accessible platform.

## ✨ Key Features

* 🆘 **SOS Assistance** — Access emergency assistance through the SOS interface.
* 🗺️ **Interactive Map** — View relevant locations and rescue resources.
* 🏠 **Shelter Discovery** — Access information about available shelters.
* 📢 **Emergency Feed** — View and share disaster-related updates.
* 🧭 **Digital Compass** — Get directional guidance when navigating.
* 🤝 **NGO & Rescue Support** — Access NGO-related and rescue coordination features.
* 📱 **Android Application** — Built using Capacitor to bring the web application to Android.
* **Mesh Networking** - Helps to connect people with p2p network 
* 🔄 **Data Synchronization** — Backend API support for synchronizing application data.

> Note: Feature availability and behavior depend on the current implementation and configured services.

## 🛠️ Tech Stack

| Technology           | Purpose                             |
| -------------------- | ----------------------------------- |
| React                | User interface                      |
| TypeScript           | Type-safe development               |
| Vite                 | Development server and build tool   |
| Capacitor            | Android application integration     |
| Supabase             | Backend and data services           |
| Node.js              | Server-side runtime                 |
| Express / API server | Backend endpoints, where configured |
| Git & GitHub         | Version control and collaboration   |

## 🏗️ Project Architecture

```text
ResQLink/
├── src/                 # React application
├── public/              # Static assets
├── server/              # Server-side code
├── android/             # Native Android project
├── package.json         # Dependencies and scripts
├── vite.config.ts       # Vite configuration
├── capacitor.config.ts  # Capacitor configuration
└── README.md            # Project documentation
```

*The directory structure may vary depending on the current version of the project.*

## 🚀 Getting Started

### Prerequisites

Install the following before running the project:

* Node.js and npm
* Git
* Android Studio (for Android development)
* A Supabase project and required environment variables, if applicable

### 1. Clone the Repository

```bash
git clone https://github.com/bhumikaa0006-create/ResQLinkk.git
```

### 2. Navigate to the Project

```bash
cd ResQLinkk
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env` file in the project root and add the variables required by your application.

```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

Use the exact variable names expected by your existing code. Never commit private API keys, passwords, or service-role keys to GitHub.

### 5. Start the Development Server

```bash
npm run dev
```

Open the local URL displayed in your terminal.

### 6. Build the Application

```bash
npm run build
```

### 7. Run on Android

After configuring Capacitor and the Android project:

```bash
npx cap sync android
npx cap open android
```

Use Android Studio to build and run the application on an emulator or a connected Android device.

## 🔐 Security & Reliability

* Keep credentials and private keys out of source control.
* Validate incoming API requests.
* Handle network failures and unavailable services gracefully.
* Clearly distinguish verified emergency information from unverified user-submitted reports.
* Test emergency-related features before relying on them in real-world situations.

## 🗺️ Roadmap

* [ ] Improve offline access to essential emergency information.
* [ ] Enhance disaster-report classification using NLP.
* [ ] Improve shelter and rescue-resource verification.
* [ ] Strengthen synchronization during unreliable connectivity.
* [ ] Explore nearby-device communication for situations with limited internet access.
* [ ] Improve accessibility and the Android user experience.

## 🤝 Contributing

Contributions, suggestions, and bug reports are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Test your implementation.
5. Open a pull request describing your changes.


## ⚠️ Disclaimer

ResQLink is a technology project intended to support emergency awareness and coordination. It does not replace official emergency services, verified rescue instructions, or professional emergency responders.

---

**Built with the goal of making emergency assistance more accessible when every second matters.** ❤️‍🩹
