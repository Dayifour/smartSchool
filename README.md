# 📚 ENT - Digital Work Environment

Welcome to **ENT**, an interactive e-learning platform designed to enhance the online learning experience. This project allows teachers to manage their courses and students to easily access educational resources.

## 📸 SmartSchool platform preview

### Logo

![SmartSchool logo](public/img/logoS.png)

### Screenshots

![SmartSchool screenshot 1](public/img/sc1.png)
![SmartSchool screenshot 2](public/img/sc2.png)
![SmartSchool screenshot 3](public/img/sc3.png)
![SmartSchool screenshot 6](public/img/sc6.png)
![SmartSchool screenshot 7](public/img/sc7.png)
![SmartSchool screenshot 8](public/img/sc8.png)
![SmartSchool screenshot 9](public/img/sc9.png)
![SmartSchool screenshot 10](public/img/sc10.png)
![SmartSchool screenshot 11](public/img/sc11.png)
![SmartSchool screenshot 12](public/img/sc12.png)
![SmartSchool screenshot 13](public/img/sc13.png)
![SmartSchool screenshot 14](public/img/sc14.png)
![SmartSchool screenshot 15](public/img/sc15.png)
![SmartSchool screenshot 17](public/img/sc17.png)
![SmartSchool screenshot 18](public/img/sc18.png)
![SmartSchool screenshot 20](public/img/sc20.png)
![SmartSchool screenshot 21](public/img/sc21.png)

## 🚀 Key features

- 🔐 **Secure authentication** (registration, login, role management)
- 📚 **Course management** (creation, modification, deletion)
- 🎥 **Display and follow-up of training videos**
- 📝 **Interactive quiz system**
- 📊 **Tracking student progress**
- 💬 **Discussion forum** for the exchange between learners and teachers

## 🛠️ Technologies used

- **Framework**: Next.js
- **Frontend**: React, Tailwind CSS
- Backend: Next.js API Routes, Prisma
- **Database**: MySQL
- **Authentication**: NextAuth.js

## 📥 Installation

### 📌 Prerequisites

- **Node.js 18+**
- **MySQL or MongoDB database configured**
- **Prisma installed**

### 🔧 Installation steps

1. **Clone Project**

```bash
git clone https://github.com/ton-utilisateur/ENT.git
cd ENT
```
2. **Install dependencies**
    '''bash npm install'''
3. **Configure the environment**
   Create a '.env.local' file at the root of the project and add:
   DATABASE_URL="votre_url_de_base_de_donnees"
    NEXTAUTH_SECRET="votre_secret"
4. **Run database migrations**
```bash
 npx prisma migrate dev --name init
```
5. **Launch the application**
```bash
 npm run dev
```
## 📅 Roadmap
 - [ ] Finalization of the authentication system
 - [ ] Addition of advanced course management
 - [ ] Integration of an administrator dashboard
 - [ ] Improvement of the UX/UI
## 🤝 Contribution Contributions are welcome!
 - [ ] 1. Forking the repo
 - [ ] 2. Create a branch ('git checkout -b feature-xyz')
 - [ ] 3. Commit your changes ('git commit -m 'Adding a new feature')
 - [ ] 4. Push Branch ('git push origin feature-xyz')
 - [ ] 5. Open a Pull Request
## 📜 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more information.

---

✨ _This project is actively being developed, stay tuned for updates!_
