I want to create a sub-agent focused on the topic: ``` Auth Agent, responsible for handling secure user authentication flows. ```
Generate an agent prompt based on the reference agent-creation prompt I provided.

Ensure that the agent explicitly uses the following skills: ``` Auth Skill and Validation Skill. ```
Here is reference prompt:
"""   """



I want to create a Skill focused on the topic: ``` Auth Skill – Signup, signin, password hashing, JWT tokens, Better Auth integration. ```
Generate a skill based on the reference Skill 
here is reference prompt:
"""   """

**Update the `claude.md` file based on my project requirements.
In this file:**
- Use Auth Agent for authentication
- Use Frontend Agent for frontend development (e.g., Next.js)
- Use DB Agent for database design and operations
- Use Backend Agent for FastAPI development

Below are my project requirements: 
```"""   Phase II: Todo Full-Stack Web Application
Basic Level Functionality
Objective: Using Claude Code and Spec-Kit Plus transform the console app into a modern multi-user web application with persistent storage.
💡Development Approach: Use the Agentic Dev Stack workflow: Write spec → Generate plan → Break into tasks → Implement via Claude Code. No manual coding allowed. We will review the process, prompts, and iterations to judge each phase and project.
Requirements
Implement all 5 Basic Level features as a web application
Create RESTful API endpoints
Build responsive frontend interface
Store data in Neon Serverless PostgreSQL database
Authentication – Implement user signup/signin using Better Auth
Technology Stack
Layer
Technology
Frontend
Next.js 16+ (App Router)
Backend
Python FastAPI
ORM
SQLModel
Database
Neon Serverless PostgreSQL
Spec-Driven
Claude Code + Spec-Kit Plus
Authentication
Better Auth

Better Auth can be configured to issue JWT (JSON Web Token) tokens when users log in. These tokens are self-contained credentials that include user information and can be verified by any service that knows the secret key.
How It Works
User logs in on Frontend → Better Auth creates a session and issues a JWT token
Frontend makes API call → Includes the JWT token in the Authorization: Bearer <token> header
Backend receives request → Extracts token from header, verifies signature using shared secret
Backend identifies user → Decodes token to get user ID, email, etc. and matches it with the user ID in the URL
Backend filters data → Returns only tasks belonging to that user

 """```

