# 📸 Instaclone

## 🚀 Features

1. **User Authentication & Sessions**  
   - Secure login and signup with hashed passwords.  
   - Persistent login sessions implemented using `express-session`.

2. **Profile Management**  
   - Users can create and update personal profiles with bio and profile picture.

3. **Post Creation & Sharing**  
   - Upload images with captions.  
   - Posts stored in MongoDB with secure file handling.

4. **Feed System**  
   - Real-time feed that displays posts from all users in chronological order.

5. **Like & Comment Functionality**  
   - Users can like/unlike posts and comment on them.  
   - Instant updates without page reload.

6. **Follow/Unfollow System**  
   - Ability to follow other users and see their posts in your feed.

7. **Session Management**  
   - `express-session` used for secure session tracking.  
   - Sessions stored in MongoDB for scalability.

8. **Responsive Frontend (React)**  
   - Clean, modern UI built with React.  
   - Fully responsive for desktop and mobile devices.

9. **API Endpoints (Express)**  
   - RESTful APIs for authentication, posts, likes, comments, and follows.  
   - JWT-based protection for certain endpoints.

10. **Database & Storage**  
   - MongoDB for storing users, posts, and comments.  
   - Images handled via local storage or cloud services (Cloudinary / AWS S3).

---

## 🛠️ Tech Stack

- **Frontend:** React.js, CSS, Axios  
- **Backend:** Node.js, Express.js (with Express Generator)  
- **Database:** MongoDB (Mongoose ORM)  
- **Session:** express-session + connect-mongo  
- **Other Tools:** Multer (for file uploads), bcrypt (for password hashing)

---  
