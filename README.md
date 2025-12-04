# 📚 Books Library MERN Stack Application

A full-stack book library application built with the MERN stack (MongoDB, Express, React, Node.js) for managing, searching, and organizing books.

## 🚀 Features
 
- 📖 Book management system 
- 🔍 Search functionality
- 📝 Add, edit, and delete books 
- 📱 Responsive design
- 🔐 User authentication  
- 📊 Book categorization 
 
## 🛠️ Tech Stack

- **Frontend:**
  - React.js
  - Tailwind CSS
  - Vite
  - ESLint

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB
  - Mongoose

## 📁 Project Structure

```
📦 books-library-mern
├── 📂 bookstore-frontend
│   ├── �� src
│   │   ├── 📂 pages
│   │   │   ├── 📄 Home.jsx
│   │   │   ├── 📄 ShowBook.jsx
│   │   │   ├── 📄 DeleteBook.jsx
│   │   │   ├── 📄 EditBook.jsx
│   │   │   └── 📄 CreateBooks.jsx
│   │   │
│   │   ├── 📂 components
│   │   │   ├── 📂 home
│   │   │   │   ├── 📄 BooksTable.jsx
│   │   │   │   ├── 📄 BookSingleCard.jsx
│   │   │   │   ├── 📄 BookModal.jsx
│   │   │   │   └── 📄 BooksCard.jsx
│   │   │   ├── 📄 Spinner.jsx
│   │   │   └── 📄 BackButton.jsx
│   │   │
│   │   ├── 📂 assets
│   │   ├── 📄 App.jsx
│   │   ├── 📄 main.jsx
│   │   └── 📄 index.css
│   │
│   ├── 📂 public
│   ├── 📄 package.json
│   ├── 📄 package-lock.json
│   ├── 📄 vite.config.js
│   ├── 📄 tailwind.config.js
│   ├── 📄 postcss.config.cjs
│   ├── 📄 eslint.config.js
│   ├── 📄 index.html
│   └── 📄 .gitignore
│
└── 📂 bookstore-backend
    ├── 📂 routes
    │   └── 📄 bookRoutes.js
    ├── 📂 models
    │   └── 📄 Book.js
    ├── 📄 index.js
    ├── 📄 config.js
    ├── 📄 package.json
    └── 📄 package-lock.json
```

## 📱 Frontend Structure Details

### Pages 📂
- **Home.jsx** - Main landing page with book listings
- **ShowBook.jsx** - Detailed view of a single book
- **DeleteBook.jsx** - Book deletion confirmation and handling
- **EditBook.jsx** - Book editing interface
- **CreateBooks.jsx** - New book creation form

### Components 📂
#### Home Components
- **BooksTable.jsx** - Tabular view of books
- **BookSingleCard.jsx** - Individual book card component
- **BookModal.jsx** - Modal for book details
- **BooksCard.jsx** - Card layout for book display

#### Common Components
- **Spinner.jsx** - Loading spinner component
- **BackButton.jsx** - Navigation back button

### Core Files 📄
- **App.jsx** - Main application component
- **main.jsx** - Application entry point
- **index.css** - Global styles

### Configuration Files 📄
- **vite.config.js** - Vite bundler configuration
- **tailwind.config.js** - Tailwind CSS configuration
- **postcss.config.cjs** - PostCSS configuration
- **eslint.config.js** - ESLint configuration
- **package.json** - Project dependencies and scripts

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/HARIHARANS24/books-library-mern.git
```

2. Install frontend dependencies
```bash
cd bookstore-frontend
npm install
```

3. Install backend dependencies
```bash
cd ../bookstore-backend
npm install
```

4. Create a `.env` file in the backend directory and add your MongoDB connection string:
```
MONGODB_URI=your_mongodb_connection_string
```

5. Start the backend server
```bash
npm start
```

6. Start the frontend development server
```bash
cd ../bookstore-frontend
npm run dev
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- **HARIHARANS24** - *Initial work* - [GitHub Profile](https://github.com/HARIHARANS24)

## 🙏 Acknowledgments

- Thanks to all contributors who have helped shape this project
- Special thanks to the MERN stack community for their excellent documentation and support 
