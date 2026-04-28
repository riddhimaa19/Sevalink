 SevaLink: A simple and efficient platform that connects people in need with available volunteers in real-time.
 Features:
1.Volunteer registration
2.Post help requests
3.Automatic volunteer assignment
4.View all requests with status (Assigned / Pending)
 Tech Stack:
Backend: Node.js + Express.js
Frontend: HTML, CSS, JavaScript
Data Storage: In-memory arrays (temporary)
 Project Structure:

/project-root
│── server.js
│── /public
│    ├── index.html
│    ├── script.js
│    └── style.css
  Installation & Setup:
Clone the repository

git clone https://github.com/your-username/sevalink.git
cd sevalink
Install dependencies

npm install
Run the server

node server.js
Open in browser

http://localhost:3000
  How It Works:
1.Volunteers register with their skills
2.Users post help requests
3.System assigns the first available volunteer
4.Requests can be viewed with their status
 API Endpoints:
i.  POST /register → Register volunteer
ii. POST /request → Create help request
iii. GET /requests → Fetch all requests
 Future Improvements:
1. Database integration
2. Smart matching based on skills and location
3. Real_time updates(WebSockrts)
4. Authentication system
