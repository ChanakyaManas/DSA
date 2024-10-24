### **Week 1: Local Setup and Basic Project Structure**  
**Cloud Admin Tasks:**
1. **Create Google Cloud Accounts & Setup Project:**
   - Create a **Google Cloud Project** for the students.
   - Enable **Google Cloud APIs** (PostgreSQL, Redis, and Pub/Sub APIs).

2. **Set up Cloud PostgreSQL:**
   - Create a **Cloud SQL PostgreSQL instance** and configure connections.
   - Share **connection strings** with students for backend integration later.

3. **Prepare Cloud Redis (Optional Demo):**
   - Set up a **Redis Cloud instance** to demonstrate cloud caching.
   - Document Redis commands to share with students for local setup.

4. **Create Basic Cloud Infrastructure:**
   - Prepare **Google Cloud buckets** (for future uploads like profile pictures).
   - Ensure **IAM roles** are correctly assigned for database access.

---

### **Week 2: Authentication and User Profiles**  
**Cloud Admin Tasks:**
1. **Cloud PostgreSQL Integration**:
   - Verify that students can **connect** their Spring Boot backend to Cloud SQL.
   - Support any **connection troubleshooting** (e.g., firewall or IP issues).

2. **Google Identity Demo Preparation:**
   - Set up **Google OAuth 2.0** client IDs for student demos (if using Google login).
   - Test **JWT token flows** (using tools like Postman) to ensure smooth authentication.

3. **Storage Setup for Profile Pictures:**
   - Create a **Google Cloud Storage bucket** to store uploaded files.
   - Provide students with a **service account** JSON key for local development.

---

### **Week 3: CRUD Operations and Timeline**  
**Cloud Admin Tasks:**
1. **Setup Kafka & Google Pub/Sub (Messaging Demo):**  
   - Create a **Google Pub/Sub topic** to simulate real-time message notifications.
   - Prepare **Kafka locally** in case students struggle with Pub/Sub integration.

2. **Analytics Setup (Optional BigQuery Demo):**
   - Create **BigQuery tables** to collect Tweet data for analytics.
   - Set up **SQL queries** to show students how data can be queried at scale.

3. **Cloud SQL Performance Monitoring:**
   - Use **Cloud SQL Insights** to track and optimize query performance.
   - Guide students on **how to monitor database connections**.

---

### **Week 4: User Relationships and Search Functionality**  
**Cloud Admin Tasks:**
1. **Setup Elasticsearch (Optional Demo):**
   - Create an **Elasticsearch instance** in the cloud for demonstrating advanced search.
   - Provide simple curl-based search **query examples** for students to test locally.

2. **Implement Relationship Graphs in Cloud:**
   - Prepare a **FlockDB or Neo4j instance** to demonstrate modeling user relationships.
   - Share documentation or APIs for students to explore graph concepts locally.

---

### **Week 5: Caching, Load Balancing, and Monitoring**  
**Cloud Admin Tasks:**
1. **Redis in Production (Pelikan Cache):**  
   - Ensure **Redis production caching setup** is in place for demonstration.
   - Run a **benchmarking demo** showing performance improvement with caching.

2. **Load Balancer Setup (Nginx):**
   - Set up **Google Cloud Load Balancer** to distribute traffic across multiple instances.
   - Configure **DNS routing** and share the public URL with students for testing.

3. **Monitor with Zipkin and Splunk:**
   - Integrate **Zipkin** for tracing service requests.
   - Prepare a **Splunk dashboard** for log monitoring.

---

### **Week 6: Scaling and Optimization**  
**Cloud Admin Tasks:**
1. **Sharded Counters for Scalability:**
   - Implement **sharded counters** in **Google Datastore** for like counts and retweets.
   - Guide students in setting up **sharding logic** locally.

2. **Consistent Hashing Demo:**
   - Use a **load balancing demo** to show how consistent hashing ensures scalability.
   - Prepare a scenario (e.g., simulating load spikes) and discuss how to handle it in the cloud.

---

### **Week 7: Testing, Debugging, and Deployment**  
**Cloud Admin Tasks:**
1. **Set up CI/CD Pipelines with GitHub Actions:**  
   - Create **GitHub Actions workflows** to automate build and deployment pipelines.
   - Connect the pipeline to **Google Kubernetes Engine (GKE)** for automated deployments.

2. **Configure GKE for Backend Services:**  
   - Set up **Kubernetes clusters** and deploy the backend services to GKE.
   - Use **Helm charts** to simplify deployment and scaling.

3. **Docker and Cloud Storage Integration:**
   - Prepare Docker containers for backend/frontend.
   - Ensure uploaded images/files sync correctly with **Google Cloud Storage** buckets.

---

### **Week 8: Final Review and Wrap-up**  
**Cloud Admin Tasks:**
1. **Full System Walkthrough in the Cloud:**  
   - Showcase the **end-to-end architecture** (PostgreSQL, Redis, Pub/Sub, GKE, etc.).
   - Discuss **trade-offs** in using various services (like Redis vs. Pelikan cache, Kafka vs. Pub/Sub).

2. **Optimize Cloud Resources for Scalability:**  
   - Optimize the **cloud infrastructure** to simulate real-world scaling scenarios.
   - Demonstrate **autoscaling** in GKE and **monitoring dashboards** for services.

3. **Final Deployment and Presentation:**  
   - Ensure the **final application** is fully deployed and accessible via public URLs.
   - Walk students through the **deployment process** and reflect on **DSA concepts** used in the project.

---

### **Ongoing Tasks Throughout the Project**  
- **IAM Roles and Security:**  
  - Manage **IAM policies and roles** to control access to cloud resources.
  - Ensure **secure credentials management** and avoid hardcoding secrets.

- **Cloud Monitoring and Alerts:**  
  - Set up **Google Cloud Monitoring** for key metrics like CPU usage, memory, and errors.
  - Enable **alert notifications** to catch any issues early during deployment.

---

### Summary  
As the **cloud admin**, you’ll handle the setup, monitoring, and deployment of the cloud infrastructure, ensuring that students can focus on coding without worrying about cloud complexities. This division of responsibilities allows for smooth integration of DSA concepts and practical cloud knowledge, while you demo and manage **cloud tools** to show how their local work can scale in the cloud.

