# Blog API - NestJS

## 📌 Project Overview
This is a **RESTful API** built with **NestJS** to manage a blog system. It provides CRUD operations for users, articles, and categories while following REST best practices.

## 🚀 Features
- 📝 **CRUD Operations**: Create, Read, Update, and Delete articles, users, and categories.
- 🔑 **Authentication & Authorization**: Secure endpoints with JWT authentication.
- 📄 **API Documentation**: Auto-generated Swagger documentation.
- 🗄️ **Database Integration**: PostgreSQL support using TypeORM.
- 🛠️ **Validation & Error Handling**: Input validation with class-validator.
- ☁️ **Deployment Ready**: Configured for cloud hosting.
- 🐳 **Docker Support**: Easily run the API with Docker.

## 🏗️ Technologies Used
- **Backend**: [NestJS](https://nestjs.com/)
- **Database**: PostgreSQL with TypeORM
- **Authentication**: JWT & Passport.js
- **Documentation**: Swagger (OpenAPI)
- **Testing**: Jest & Supertest
- **Containerization**: Docker & Docker Compose

## 📦 Installation & Setup
### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/blog-api.git
cd blog-api
```

### 2️⃣ Install dependencies
```bash
npm install
```

### 3️⃣ Configure environment variables
Create a `.env` file at the root of the project:
```env
DATABASE_URL=postgres://user:password@localhost:5432/blog_db
JWT_SECRET=your_secret_key
PORT=3000
```

### 4️⃣ Run the project
#### Development mode:
```bash
npm run start:dev
```
#### Production mode:
```bash
npm run build && npm run start
```

### 5️⃣ Run with Docker
#### Build and start the container:
```bash
docker-compose up --build
```
#### Stop the container:
```bash
docker-compose down
```

### 6️⃣ API Documentation
Once the server is running, access the Swagger documentation at:
👉 [http://localhost:3000/api](http://localhost:3000/api)

## 🛠️ Endpoints
| Method | Endpoint       | Description |
|--------|---------------|-------------|
| GET    | /articles     | Get all articles |
| GET    | /articles/:id | Get a single article |
| POST   | /articles     | Create a new article |
| PUT    | /articles/:id | Update an article |
| DELETE | /articles/:id | Delete an article |

More details are available in the Swagger documentation.

## 📜 License
This project is licensed under the MIT License.

---
👨‍💻 Built with ❤️ by [Auger-Dubois Benoit](https://github.com/BenoitAd)

