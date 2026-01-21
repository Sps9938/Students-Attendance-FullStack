# Students-Attendance-FullStack

A full-stack application combining separate **Frontend** and **Backend** projects using Git submodules for better modularity and maintainability.

## Project Structure

```bash
FullStackApp/
├── Frontend/ # React/Vite frontend (Git submodule)
└── Backend/ # Express/MongoDB backend (Git submodule)

```


- `Frontend` and `Backend` are Git submodules from their respective repositories.
- This monorepo-style layout allows easier deployment, versioning, and full-stack development.

---

## How to Clone This Repository

To clone this repository **with submodules**, run:

```bash
git clone  https://github.com/your-username/FullStackApp.git

```
## Making Changes to Submodules

### 1. Commit and push changes inside the submodule

```bash
cd Frontend   # or Backend
git add .
git commit -m "Your update message"
git push origin main

```

### 2. Update submodule reference in the main repo

```bash
cd ..
git add Frontend   # or Backend
git commit -m "Update Frontend/Backend submodule reference"
git push origin main

```


## Testing

### Backend Testing
The backend is tested using **Pytest**. Automated tests cover API endpoints, business logic, and health checks to ensure reliability and correctness of the backend services.


### Frontend Testing
The frontend is tested using **Selenium** for UI automation and **Jest** for unit and API endpoint testing.

#### Jest API Testing
Jest is used to automate testing of frontend logic and backend API endpoints. Example tests include verifying login, health check, and other API routes using axios. To run Jest tests:

```bash
cd Frontend
npm run test
```
Make sure your backend server is running before running API tests.

---
## Why Submodules?

Independent version control for Frontend and Backend

Reusable across multiple projects

Keeps this repo lightweight and maintainable

## Contributing

To contribute to the **Frontend** or **Backend**, fork and open pull requests directly in those repositories.

For full-stack integration issues or changes, you can work within this **FullStack** repo.


## Author

**Satya Prakash**  
Full-stack Developer | MERN Stack | Open Source Enthusiast

- GitHub: [@Sps9938](https://github.com/Sps9938)
- LinkedIn: [linkedin.com/in/satya-prakash-sahu-sps](https://linkedin.com/in/satya-prakash-sahu-sps)
- Email: satyaprakash.8455995130@gmail.com
