# 🎓 ExamAce — Exam & Career Information Portal

ExamAce is a web application designed to bring educational and career-related information together in one place. It organizes information about examinations, job opportunities, and examination results to help users explore relevant opportunities based on their interests and qualifications.

## ✨ Project Overview

Finding relevant examination notifications, job opportunities, and result announcements across different sources can be time-consuming. ExamAce aims to make this information easier to browse through a centralized web platform.

## 🚀 Key Areas

- **Examination Information** — Browse exam-related information and details.
- **Job Listings** — Explore government and private job opportunities, including eligibility, location, vacancies, and application dates.
- **Results Information** — Access result announcements and related links.
- **Category Tags** — Organize information by categories such as engineering, medical, government, banking, and IT.
- **User Accounts** — The project includes user-related functionality and qualification/preference fields.
- **Database-Driven Content** — Store and organize examination, job, result, and category information.

*Note: The feature list should be adjusted to match the screens and workflows that are currently functional in the application.*

## 🛠️ Tech Stack

- **Backend:** PHP, Laravel
- **Frontend:** Blade templates, JavaScript, CSS
- **Database:** MySQL
- **Dependency Management:** Composer, npm
- **Build Tool:** Vite

## 📁 Project Structure

```text
ExamAce/
├── app/                # Application logic
├── bootstrap/          # Framework bootstrapping
├── config/             # Application configuration
├── database/           # Migrations and database-related files
├── public/             # Public assets and entry point
├── resources/
│   └── views/           # Blade templates and views
├── routes/              # Application routes
├── storage/             # Logs and generated files
├── tests/               # Automated tests
├── .env.example         # Example environment configuration
├── composer.json        # PHP dependencies
├── package.json         # Frontend dependencies
└── examace.sql          # Database SQL file
```

## ⚙️ Getting Started

### Prerequisites

Install the following before running the project:

- PHP version compatible with the project's Laravel dependencies
- Composer
- Node.js and npm
- MySQL
- Git

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/priyya16/ExamAce.git
   cd ExamAce
   ```

2. Install PHP dependencies:

   ```bash
   composer install
   ```

3. Create your environment configuration:

   ```bash
   cp .env.example .env
   ```

   On Windows Command Prompt, use:

   ```cmd
   copy .env.example .env
   ```

4. Generate the application key:

   ```bash
   php artisan key:generate
   ```

5. Configure your database credentials in `.env` and create the corresponding MySQL database.

6. Set up the database using the project's migrations or SQL import, as appropriate for the current schema. Do not import the SQL dump and run the same migrations blindly, as this may create duplicate tables.

7. Install frontend dependencies and build assets:

   ```bash
   npm install
   npm run build
   ```

8. Start the Laravel development server:

   ```bash
   php artisan serve
   ```

9. Open the local URL displayed by Artisan in your browser.

## 🔐 Configuration & Security

- Keep `.env` private and never commit real passwords, application keys, or database credentials.
- Use `.env.example` to document the required environment variables without real secrets.
- Review the SQL dump before sharing it publicly, especially if it contains personal data, credentials, or other sensitive information.

## 🧪 Testing

Run the project's automated tests with:

```bash
php artisan test
```

Test availability and successful execution depend on the project's current configuration.

## 🔮 Future Improvements

- Add search and filtering across exams and job listings.
- Improve the user experience on mobile devices.
- Add clearer categorization and personalized information discovery.
- Provide screenshots and a live demo when available.
- Expand automated testing and deployment documentation.

## 👩‍💻 Author

**Priya Pedhadiya**

- GitHub: [@priyya16](https://github.com/priyya16)
- Repository: [ExamAce](https://github.com/priyya16/ExamAce)

---

Built as an academic web development project.
