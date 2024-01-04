# SARS School Management Web App

Welcome to the SARS School Management Web App, an Express.js and MongoDB-based school management system. This application provides a platform for managing users, faculties, assignments, and includes an admin panel with specific rights.

## Project Structure

The project structure consists of the following directories and files:

- **middleware**: Contains middleware functions, such as `auth.js`.
- **models**: Includes MongoDB models for various entities.
  - `DepartmentModel.js`
  - `facultyModel.js`
  - `reviewCommentModel.js`
  - `synopsisModel.js`
  - `ProgramModel.js`
  - `notificationModel.js`
  - `reviewTaskModel.js`
  - `token.js`
  - `adminModel.js`
  - `presentationModel.js`
  - `studentModel.js`
- **routes**: Contains Express.js route handlers.
  - `Admin.js`
  - `Faculty.js`
  - `Student.js`
  - `Synopsis.js`
- **uploads**: Directory for storing uploaded files.
  - **AdminImages**: Stores images related to admin activities.
  - **Synopsis**: Stores uploaded synopsis files.

## Middleware

The `middleware` directory contains `auth.js`, which includes middleware functions used in the application.

## Models

The `models` directory includes MongoDB models for different entities like departments, faculties, review comments, synopses, programs, notifications, review tasks, tokens, admin details, presentations, and student details.

## Routes

The `routes` directory contains Express.js route handlers for different roles, including admin, faculty, student, and synopsis.

## Uploads

The `uploads` directory is used to store various uploaded files, such as images and synopses.

## Getting Started

To run the SARS School Management Web App locally:

1. Clone the repository:

   ```bash
   git clone <repository_url>
   ```

2. Navigate to the project directory:

   ```bash
   cd SARS-School-Management-Web-App/sars-app-main
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Set up MongoDB and update the database configuration in `server.js`.

5. Run the app:

   ```bash
   npm start
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Features

- **User Management**: CRUD operations for managing users.
- **Faculty Management**: CRUD operations for managing faculties.
- **Assignment Management**: CRUD operations for managing assignments.
- **Admin Panel**: Includes an admin panel with specific rights.
- **File Uploads**: Allows users to upload images and synopses.

## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m 'Add your feature'`.
4. Push to the branch: `git push origin feature/your-feature`.
5. Submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.