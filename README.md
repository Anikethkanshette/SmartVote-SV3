SmartVote-SV3

SmartVote - College Election Management System 🎓🗳️

SmartVote is a modern, secure, and user-friendly college election system that incorporates Face Recognition Authentication and Biometric Registration to ensure transparent and tamper-proof voting.

> 💡 Built for educational institutions to digitally manage elections for student bodies with enhanced security and ease of use.




---

🔐 Features

🧑‍🎓 Role-based access: Voters, Candidates, Admins, and Super Admins.

🆔 Biometric Registration – Voters can register using fingerprint or face capture.

📸 Face authentication using simulated Face API.

🗳️ Secure Digital Voting – Each voter can cast only one vote securely.

📝 Candidate Applications – Voters/Students can apply to become candidates.

✅ Admin Approval System – Admins review candidate applications and accept or reject them.

🧾 Voter registration and profile management.

📊 Dashboard with user stats, election management, and results.

⚡ Responsive, mobile-friendly UI with smooth UX.



---

🖼️ Demo

https://smartvoter.aniketh.info/


---

🔧 Tech Stack

Tech	Purpose

HTML, CSS, JS	Frontend and UI/UX
face-api.js	Face recognition (simulated)
Biometric API	Fingerprint & biometric registration
localStorage	Client-side data persistence
FontAwesome	Icons


> ✅ No backend or database needed — ideal for academic demo or prototype projects.




---

🏃‍♂️ Run Locally

You can open index.html directly in your browser OR use a local server:

# Python HTTP server (Python 3)
python -m http.server 8000

Then open http://localhost:8000 in your browser.


---

📂 File Structure

smartvote/
├── index.html           # Main application UI
├── styles.css           # Styling and responsive design
├── script.js            # Application logic (face auth, biometrics, dashboard)
├── face-api.min.js      # Simulated face recognition API
├── package.json         # Project metadata
└── models/              # (Optional) FaceAPI model folder (if using real API)


---

🚀 Deployment

Deploy easily to:

[x] Netlify

[x] GitHub Pages


No backend setup required. Just upload or link the project files.


---

🔒 Authentication & Election Flow

1. User Registration → Students/Voters register using biometrics and face data.


2. Admin Approval → Admins approve newly registered voters.


3. Candidate Application → Any student/voter can apply to become a candidate.


4. Admin Review → Admins accept or reject candidate applications.


5. Secure Voting → Approved voters cast their votes once.


6. Real-Time Results → Results are displayed instantly on the dashboard.




---

📦 Simulated face-api.js

This version uses a placeholder to simulate facial detection and matching logic. You can replace it with actual Face API models for production.


---

👥 Roles

Role	Permissions

Super Admin	Approve users, manage elections, view stats
Admin	Approve/reject candidates, manage elections, set limits
Candidate	Apply for elections, view application status
Voter	Vote securely via biometrics or credentials



---

📘 License

MIT License © 2025 [ Aniketh Malkarjun Kanshette ]


---

🙌 Acknowledgements

face-api.js

Font Awesome

UI inspiration from modern admin dashboards and design systems.



---

💼 Connect with Me
🌐 Portfolio: aniketh.info
🌐 Website: personal.aniketh.info
💼 LinkedIn: Aniketh Kanshette
📷 Instagram: @ANIKETH.PATIL.KANSHETTE


