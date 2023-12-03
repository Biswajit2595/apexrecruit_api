# **Apex Recruit Job Portal**

## **Discover Your Career Opportunities**

### **Introduction**

Welcome to Apex Recruit, your premier job portal for discovering exciting career opportunities. This readme will guide you through the essential features of the platform, ensuring you make the most of your job-seeking experience.

### **Platform Access**

Access the Apex Recruit platform through [https://apexrecruit.com](https://apexrecruit-api-flask-app.onrender.com)


### **Key Features**

- Explore Job Postings from Top Companies
- Submit Job Applications Effortlessly
- Keep Track of Your Job Application Status
- Connect with Hiring Managers
- Receive Customized Applicant Recommendations

### **Design Approach and Assumptions**

- Designed for a seamless and user-friendly experience.
- Assumption: Simplified authentication process for the sake of this demo.

### **Installation & Getting Started**

1. Clone the repository: `https://github.com/Biswajit2595/ApexRecruit.git`
2. Set up a virtual environment: `python -m venv venv`
3. Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On macOS/Linux: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`
5. Start your job-seeking journey: `flask run`

### **User Journey**

1. Log in using provided credentials.
2. Explore job postings from leading companies.
3. Submit applications effortlessly.
4. Keep track of your application status.
5. Connect with hiring managers for networking.
6. Receive personalized job recommendations.
7. Stay informed about job market trends.

### **API Endpoints**

#### **Authentication**

- `POST /api/jobsekers/signup` - Register a new jobseeker.
- `POST /api/hiringmanager/signup` - Register a new Hiring Manager.
- `POST /api/jobsekers/login` - Log in an existing job seeker.
- `POST /api/hiringmanager/login` - Log in an existing Miring Manager.

#### **Job Postings**

- `POST /api/jobs/create` - create new Job Posting.
- `GET /api/jobs/created` - to get all the posting created by the hiring manager.
- `GET /api/jobs/get/all` - Retrieve all job postings.
- `GET /api/jobs/get/:id` - Retrieve job posting details.
- `PUT/PaTCH /api/jobs/update/:id` - To Update job posting details.
- `DELETE /api/jobs/delete/:id` - Delete job posting.

#### **Applications**

- `GET /api/applications` - Retrieve all job applications.
- `GET /api/applications/job/:id` - Retrieve a particular job application.
- `GET /api/applications/get/:id` - To Retrieve a particular Job post details.
- `POST /api/applications/apply/:id` - To Apply in a particular Job post.
- `PUT/PATCH /api/applications/update/:id` - To Update a Job post.
- `DELETE /api/applications/update/:id` - To Delete a Job post.
- `POST /api/applications/recommendations/:id` - To Get recommendations of Applicants from a Job Post.



### **Technology Stack**

- Backend: Flask
- Database: PostgreSQL
- Job Recommendation Engine: OpenAI Integration
- Application Tracking System: Streamlined process

---

