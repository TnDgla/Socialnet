### **Project Overview: Social Media Web App**

**SocialNet:** This project involves building a social media platform using the MERN stack (MongoDB, Express.js, React, and Node.js). The app includes functionalities such as user authentication, creating and interacting with posts, managing profiles, and real-time notifications. This project provides a comprehensive understanding of full-stack development while enabling participants to create a responsive and interactive social media application.

---

### **Mission and Objectives**

**Goal:**  
By the end of this project, participants will create a fully functional social media application with real-time features and secure authentication.

**Objectives:**  
1. Develop a MERN stack application for social interaction.
2. Implement secure authentication using JWT.
3. Create user-friendly interfaces for posts, profiles, and notifications.
4. Integrate real-time features like chat and notifications using Socket.io.
5. Deploy the application to hosting platforms for public access.

---

### **Technology Stack**

#### **Frontend**
1. **React.js**  
   - **Why?**: Simplifies UI development with reusable components.  
   - **Use Cases**: Rendering user interfaces, managing dynamic content (e.g., posts, profile pages).

2. **Material-UI**  
   - **Why?**: Provides pre-designed components for faster development.  
   - **Use Cases**: Styling components like cards, buttons, and modals.

3. **Redux Toolkit**  
   - **Why?**: Manages global state efficiently.  
   - **Use Cases**: Handling application-wide state (e.g., user data, notifications).

4. **Axios**  
   - **Why?**: Simplifies HTTP requests to the backend.  
   - **Use Cases**: Fetching and posting data (e.g., user login, post creation).

---

#### **Backend**
1. **Node.js**  
   - **Why?**: Provides a scalable runtime environment for the backend.  
   - **Use Cases**: Executing server-side logic and API handling.

2. **Express.js**  
   - **Why?**: Lightweight framework for building RESTful APIs.  
   - **Use Cases**: Defining API routes for posts, users, and notifications.

3. **JWT (JSON Web Tokens)**  
   - **Why?**: Ensures secure user authentication.  
   - **Use Cases**: Verifying user sessions.

4. **Multer**  
   - **Why?**: Handles file uploads (e.g., profile pictures, post images).  
   - **Use Cases**: Enabling media uploads.

---

#### **Database**
1. **MongoDB**  
   - **Why?**: Flexible schema for storing user data, posts, and relationships.  
   - **Use Cases**: Managing data for users, posts, and notifications.

---

#### **Real-Time Communication**
1. **Socket.io**  
   - **Why?**: Enables real-time features like chat and notifications.  
   - **Use Cases**: Handling live updates for likes, comments, and messages.

---

#### **Deployment**
1. **Frontend: Vercel or Netlify**  
   - **Why?**: Fast and optimized deployment for React apps.  
   - **Use Cases**: Hosting the frontend with a global CDN.

2. **Backend: Heroku or AWS**  
   - **Why?**: Simplifies backend deployment with environment variable management.  
   - **Use Cases**: Hosting APIs and real-time services.

---

### **Workflow Overview**
This section illustrates the interaction between the frontend (React, Redux Toolkit), backend (Node.js, Express.js), database (MongoDB), and real-time services (Socket.io).

---

### **System Architecture**
This section showcases the high-level architecture of the **SocialNet** app, illustrating the communication between users, the application, and its services.

---

### **Project Structure for Feature Implementation**
This project is structured to ensure a systematic and incremental development process. Each week builds upon the previous deliverables, enabling a smooth transition from basic functionalities to advanced features.

**NOTE:** Participants are encouraged to personalize the application by adding unique features and improving usability.

---

### **Week-by-Week Learning Plan**

#### **Week 1: Project Setup and Basic Authentication**
- **Tasks**:
  1. Install Node.js, npm, and VSCode.
     - **Reading**: [Node.js Installation](https://nodejs.org/en/download/)  
     - **Video**: [Setting Up Node.js and npm](https://www.youtube.com/watch?v=TlB_eWDSMt4)
  2. Initialize backend and frontend projects.
     - **Reading**: [Express.js Basics](https://expressjs.com/en/starter/basic-routing.html)  
     - **Video**: [Setting Up Express](https://www.youtube.com/watch?v=L72fhGm1tfE)
  3. Setup JWT-based authentication.
     - **Reading**: [JWT Authentication Guide](https://jwt.io/introduction/)  
     - **Video**: [Secure Authentication with JWT](https://www.youtube.com/watch?v=7Q17ubqLfaM)

- **Deliverables**:
  - A functional login/signup system with JWT.

---

#### **Week 2: User Profiles and Connections**
- **Tasks**:
  1. Implement user profiles (name, bio, profile picture).
     - **Reading**: [Multer Documentation](https://www.npmjs.com/package/multer)  
     - **Video**: [Uploading Files with Multer](https://www.youtube.com/watch?v=WqJ0P8JnftI)
  2. Add follow/unfollow functionality.
     - **Reading**: [MongoDB Relationships](https://mongoosejs.com/docs/populate.html)  
     - **Video**: [Managing Relationships in MongoDB](https://www.youtube.com/watch?v=WDrU305J1yw)

- **Deliverables**:
  - A profile page and follow/unfollow feature.

---

#### **Week 3: Posts and Comments**
- **Tasks**:
  1. Build post creation and display functionality.
     - **Reading**: [Material-UI Cards](https://mui.com/components/cards/)  
     - **Video**: [Material-UI for Beginners](https://www.youtube.com/watch?v=3HAARVKWVrk)
  2. Implement comments and likes for posts.
     - **Reading**: [Axios Documentation](https://axios-http.com/docs/intro)  
     - **Video**: [Working with Axios in React](https://www.youtube.com/watch?v=zr5nDW4H5hY)

- **Deliverables**:
  - Interactive posts with comments and likes.

---

#### **Week 4: Real-Time Features**
- **Tasks**:
  1. Setup Socket.io for notifications and chat.
     - **Reading**: [Socket.io Documentation](https://socket.io/docs/v4/)  
     - **Video**: [Real-Time Applications with Socket.io](https://www.youtube.com/watch?v=1BfCnjr_Vjg)
  2. Implement notification updates for interactions (e.g., likes, comments).

- **Deliverables**:
  - Real-time notifications and chat features.

---

#### **Week 5: Deployment and Testing**
- **Tasks**:
  1. Test backend APIs using Postman.
     - **Reading**: [Postman Documentation](https://learning.postman.com/docs/getting-started/introduction/)  
     - **Video**: [API Testing with Postman](https://www.youtube.com/watch?v=VywxIQ2ZXw4)
  2. Deploy the frontend and backend to Vercel and Heroku.
     - **Reading**: [Deploying on Heroku](https://devcenter.heroku.com/articles/deploying-nodejs)  
     - **Video**: [Deploying Full-Stack Apps](https://www.youtube.com/watch?v=DY_OjZ9BzOo)

- **Deliverables**:
  - Fully deployed application accessible via public URL.

---

#### **Screenshots for Reference**
- **Login Page**  
  ![Login Page](https://via.placeholder.com/300)
- **User Profile**  
  ![User Profile](https://via.placeholder.com/300)
- **Post Feed**  
  ![Post Feed](https://via.placeholder.com/300)

---

## **References:**
1. [MERN Stack Tutorial](https://www.youtube.com/playlist?list=PLillGF-RfqbbiTGgA77tGO426V3hRF9iE)
2. [React Documentation](https://reactjs.org/docs/getting-started.html)
3. [Material-UI Documentation](https://mui.com/getting-started/installation/)
4. [MongoDB Documentation](https://www.mongodb.com/docs/manual/)
