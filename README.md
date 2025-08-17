# 🎬 DreamWork Studio - Photography Studio Management System

DreamWork Studio is a **full-featured photography studio management system** built with the **MERN stack**.  
It streamlines studio operations, including **booking management, package selection, payments, portfolio management, and finance tracking**, providing a seamless experience for both admins and customers.  
This project was developed as a **group project** for academic purposes, demonstrating collaborative software development and full-stack application design.

<br>

## 👥 Contributors / Team Members

- **[Ravindu Thiranjaya](URL)** – Finance Management 
- **[Sadumina Bagya](URL)** – User Management  
- **[Ohasee Lanka](URL)** – Booking Management 
- **[Amasha Sinhalagoda](URL)** – Portfolio Management
- **[Ijas Ahamed](URL)** - Package Management
<br>

## 🗂 Project Management & Development Process

This project was developed following **Agile development practices** with a focus on **Kanban methodology**:

- **Sprint Planning:** Tasks and features were planned in 1–2 week sprints.  
- **Kanban Board:** Used [Trello](https://trello.com/) to manage tasks and track progress visually.  
  - Columns included: Backlog, To Do, In Progress, Review, Done  
  - Each user story or task was broken down into subtasks for clarity.  
- **Collaboration:** Team members coordinated on tasks and code reviews using Trello and GitHub.  
- **Iterative Development:** Features were implemented incrementally, allowing testing and feedback at every step. 
<br>

## 🚀 Key Features

### User Management
- Sign up, login, and profile management  
- Role-based access control: **Admin** & **Customer**  
- Secure authentication using JWT & Bcrypt.js

### Booking & Package Management
- Browse photography packages  
- Book appointments and manage schedules  
- Real-time booking status updates for customers and admins  

### Finance Management
- Full & partial payment handling (credit card or cash)  
- Automatically generated invoices  
- Payment history for customers and admins  
- Finance reports for admins  

### Portfolio Management
- Upload and manage photos/videos using Cloudinary  
- Interactive gallery for customers to view past sessions  
- Admin controls to manage portfolio content  

### Additional Features
- Fully responsive design for mobile & desktop  
- Intuitive UI/UX with Tailwind CSS  
- Error handling and form validations with React Hook Form  
<br>

## 🛠 Tech Stack & Libraries

### Frontend
- [React.js](https://reactjs.org/) – Fast, component-based UI  
- [Redux Toolkit](https://redux-toolkit.js.org/) & [Redux Persist](https://github.com/rt2zz/redux-persist) – State management and persistence  
- [Tailwind CSS](https://tailwindcss.com/) & [Flowbite](https://flowbite.com/) – Styling & prebuilt UI components  
- [Framer Motion](https://www.framer.com/motion/) – Animations  
- [Axios](https://axios-http.com/) – API requests  
- [React Router DOM](https://reactrouter.com/) – Client-side routing  
- [React Hook Form](https://react-hook-form.com/) – Form handling  
- [Recharts](https://recharts.org/) – Charts for finance and statistics  
- [Firebase](https://firebase.google.com/) – Optional backend integrations  
- [React Toastify](https://fkhadra.github.io/react-toastify/) & [React Spinners](https://www.davidhu.io/react-spinners/) – Notifications and loading indicators  

### Backend
- [Node.js](https://nodejs.org/) & [Express.js](https://expressjs.com/) – Server-side logic  
- [MongoDB](https://www.mongodb.com/) & [Mongoose](https://mongoosejs.com/) – Database and ODM  
- [JWT](https://jwt.io/) & [Bcrypt.js](https://www.npmjs.com/package/bcryptjs) – Authentication and password security  
- [Cloudinary](https://cloudinary.com/) & [Multer](https://www.npmjs.com/package/multer) – Media upload and storage  
- [PDFKit](https://pdfkit.org/) – Generate invoices and finance reports  
- [CORS](https://www.npmjs.com/package/cors), [Body-Parser](https://www.npmjs.com/package/body-parser), [Cookie-Parser](https://www.npmjs.com/package/cookie-parser), [Dotenv](https://www.npmjs.com/package/dotenv) – Backend utilities
- **[Nodemon](https://www.npmjs.com/package/nodemon) (dev)** – Auto-restart server during development

