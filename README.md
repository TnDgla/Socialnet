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
![image](https://github.com/user-attachments/assets/130b55bc-5ad1-4cc4-8aad-5e66a2fbe884)



### **Database Design**
![image](https://github.com/user-attachments/assets/4a7d6fa6-178e-4dfa-b70b-280d35f2b91e)

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
     - **Reading**: [MongoDB Relationships](https://mongoosejs.com/docs/index.html)  
     - **Video**: [Managing Relationships in MongoDB](https://www.youtube.com/watch?v=WDrU305J1yw)

- **Deliverables**:
  - A profile page and follow/unfollow feature.

---

#### **Week 3: Posts and Comments**
- **Tasks**:
  1. Build post creation and display functionality.
     - **Reading**: [Material-UI Cards](https://mui.com/components/cards/)  
     - **Video**: [Material-UI for Beginners](https://www.youtube.com/watch?v=Xoz31I1FuiY&t=59s)
  2. Implement comments and likes for posts.
     - **Reading**: [Axios Documentation](https://axios-http.com/docs/intro)  
     - **Video**: [Working with Axios in React](https://www.youtube.com/watch?v=Gl-vOU7ZU9A&t=6s)

- **Deliverables**:
  - Interactive posts with comments and likes.

---

#### **Week 4: Real-Time Features**
- **Tasks**:
  1. Setup Socket.io for notifications and chat.
     - **Reading**: [Socket.io Documentation](https://socket.io/docs/v4/tutorial/introduction)  
     - **Video**: [Real-Time Applications with Socket.io](https://www.youtube.com/watch?v=UUddpbgPEJM&t=567s)
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
     - **Video**: [Deploying Full-Stack Apps](https://www.youtube.com/watch?v=cVEOhgPziO8&t=61s)

- **Deliverables**:
  - Fully deployed application accessible via public URL.

---

#### **Screenshots for Reference**
![Screenshot (177)](https://github.com/user-attachments/assets/9dca4e58-64c2-4944-a985-69ae724958c4)
![Screenshot (178)](https://github.com/user-attachments/assets/622c4a97-2972-4f2b-97d1-8469053fe50b)
![Screenshot (179)](https://github.com/user-attachments/assets/26516e40-1d58-4cce-b59f-8052b1f181d8)
![Screenshot (180)](https://github.com/user-attachments/assets/e227c433-09c6-4412-9e5f-fec9bec19a59)
![Screenshot (181)](https://github.com/user-attachments/assets/ad5e2424-c15f-4359-97cc-388f7dd3aac1)
![Screenshot (182)](https://github.com/user-attachments/assets/8de029d1-b12d-4aaa-845e-93197dbb58c6)
![Screenshot (183)](https://github.com/user-attachments/assets/de5f98f9-0b36-4a28-b156-1415d2b0cf94)
![Screenshot (184)](https://github.com/user-attachments/assets/cfba79f4-5a4e-49e5-bf8c-6b76b097a8a8)
![Screenshot (185)](https://github.com/user-attachments/assets/7bacedff-cd2b-469a-8af6-5f1f07c8ff58)
![Screenshot (186)](https://github.com/user-attachments/assets/f6830d47-4b7b-46ff-afb9-43a543a56486)
![Screenshot (175)](https://github.com/user-attachments/assets/ac2c8d2f-914c-4708-94ac-c0fceb54c35b)
![Screenshot (176)](https://github.com/user-attachments/assets/a885aa11-d513-44be-a568-3774cb23e8ee)



---

## **References:**
1. [MERN Stack Tutorial](https://www.youtube.com/playlist?list=PLillGF-RfqbbiTGgA77tGO426V3hRF9iE)
2. [React Documentation](https://reactjs.org/docs/getting-started.html)
3. [Material-UI Documentation](https://mui.com/getting-started/installation/)
4. [MongoDB Documentation](https://www.mongodb.com/docs/manual/)
5. https://github.com/ZainRk/MERN-SocialMedia-ZAINKEEPSCODE.git
6. https://www.youtube.com/watch?v=VQCeu2mq8wE&list=PLLLt8Z0S3SGJ0KX7lyYF5LUZN741gMCAP&index=4
