REST API for managing student records using Node.js, Express, MongoDB, and Mongoose.

- Node.js (LTS)
- MongoDB Community Server (running locally) and MongoDB Compass

MONGODB_URI=mongodb://127.0.0.1:27017/lab5_students
PORT=5001

- Development: `npm run dev`
- Production: `npm start`

| Method | Route | Description |
|---|---|---|
| GET | /api/health | Health check |
| GET | /api/students | Get all students |
| GET | /api/students/:id | Get one student (404 if not found) |
| POST | /api/students | Create a student (201) |
| PUT | /api/students/:id | Update a student |
| DELETE | /api/students/:id | Delete a student |

{
  "fullName": "Alex Santos",
  "course": "BSIT",
  "yearLevel": 2,
  "section": "IT-2A"
}