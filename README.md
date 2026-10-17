from pathlib import Path

readme = r'''<div align="center">

# 👋 Hi there, I'm Shameer Babu

### Flutter Developer · Mobile App Engineer · Problem Solver 🇮🇳

Building beautiful, scalable, and user-focused mobile applications with Flutter.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shameer-babu-2755a62a1)
[![Instagram](https://img.shields.io/badge/Instagram-Follow-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/shameer___s_r_b)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:srbshameer098@gmail.com)

![Profile views](https://komarev.com/ghpvc/?username=srbshameer098&style=for-the-badge&color=20C997&label=PROFILE+VIEWS)

</div>

---

## 💫 About Me

- 🔭 Currently working on **Onlypass**
- 🌱 Currently learning and exploring **new things in Flutter**
- 📱 Focused on **Flutter, Dart, and BLoC state management**
- ⚙️ Experienced with **REST API integration, Firebase, Node.js, and MongoDB**
- 💬 Ask me about **Flutter and mobile app development**
- 📫 Reach me at **[srbshameer098@gmail.com](mailto:srbshameer098@gmail.com)**
- 📍 Based in **India**

## 🧰 Tech Stack

### Mobile Development
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![BLoC](https://img.shields.io/badge/BLoC-13B9FD?style=for-the-badge&logo=flutter&logoColor=white)

### Backend & Database
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

### Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

## 🚀 Featured Projects

### 🏢 Onlypass
Membership management for gyms, co-working spaces, and study spaces.

- Member and enquiry management
- Attendance and payment management
- Biometric attendance integration

**Tech:** Flutter · Dart · BLoC

### 📒 Kanakk Book
A personal accounting and bookkeeping app for managing everyday transactions.

- Transaction tracking and reports
- Backup and restore functionality
- Premium features

**Tech:** Flutter · Dart · Hive

### 🚘 Vehiclix
A vehicle inspection application built to support inspection workflows.

- Vehicle inspection workflows
- Flutter mobile application
- Node.js/Express backend and MongoDB
- React dashboard

**Tech:** Flutter · BLoC · Node.js · MongoDB · React

> Some project details may be simplified. Only publish company or team project information that you have permission to share.

## 📈 GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=srbshameer098&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="Shameer's GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=srbshameer098&layout=compact&theme=tokyonight&hide_border=true" alt="Most used languages" />

<img width="70%" src="https://streak-stats.demolab.com?user=srbshameer098&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />

</div>

---

<div align="center">

### 💚 Building useful things, one commit at a time.

*Thanks for visiting my profile!*

</div>
'''

path = Path("/mnt/data/README.md")
path.write_text(readme, encoding="utf-8")
print(f"Created {path} ({path.stat().st_size} bytes)")
