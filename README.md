CS Degree Preparation & Cybersecurity Path
Student Timeline: May 2026 - Fall 2026 (6 months)
Goal Career: Cybersecurity
Learning Philosophy: Master fundamentals + understand AI as a tool, not a replacement

📋 PHASE OVERVIEW
Phase 1: Foundations (May - Mid-June) | 4 weeks
Focus: Core programming logic, problem-solving, basic structure

Phase 2: Full-Stack Fundamentals (Mid-June - July) | 4 weeks
Focus: Front-end + Back-end basics, web architecture understanding

Phase 3: Intermediate Projects (August) | 4 weeks
Focus: Build 2-3 portfolio projects combining front + back-end

Phase 4: Cybersecurity Intro + Polish (September - Early October) | 4-5 weeks
Focus: Security concepts, code hardening, final project refinement

Phase 5: Pre-Degree Buffer (October - Late October) | 2-3 weeks
Focus: Review, final projects, confidence building before classes start

🎯 PHASE 1: FOUNDATIONS (4 Weeks)
What You'll Learn
Programming fundamentals (variables, loops, conditionals, functions)
Basic data structures (arrays, objects, maps)
Problem-solving logic and algorithms
How to read and write code independently
Debugging and thinking like a programmer
Primary Resources
FreeCodeCamp:

✅ JavaScript Fundamentals (or choose Python - see below)
✅ "Intro to Algorithms" or equivalent problem-solving course
Secondary Resources:

LeetCode (Easy level only - 10-15 problems)
Codewars (8 kyu/7 kyu problems)
Language Choice
Recommendation: JavaScript

Most relevant for web development
Essential for full-stack
Easier transition to cybersecurity tools later
Abundant free resources
Alternative: Python

Better for cybersecurity/scripting
Easier syntax (arguably)
Choose this if cybersecurity is your only focus
My suggestion: Start JavaScript, add Python in Phase 3
Weekly Breakdown
Week 1: Variables, Data Types, Operators

Understand primitive types (strings, numbers, booleans, null, undefined)
Learn operators (arithmetic, comparison, logical)
Write 5-10 small programs (calculator, temperature converter, etc.)
AI Usage Rule: Use Claude to explain concepts, not write code for you
✅ "Explain what a closure is"
❌ "Write me a function that does X"
Week 2: Control Flow & Functions

If/else, switch statements
Loops (for, while, do-while)
Functions: parameters, return values, scope
Write 10+ functions solving different problems
Checkpoint: Write a simple number guessing game (no AI code generation)
Week 3: Data Structures Basics

Arrays: create, access, methods (push, pop, slice, map, filter)
Objects: properties, methods
Solve 15-20 array/object manipulation problems
Checkpoint: Build a simple contact list manager (arrays of objects)
Week 4: Problem-Solving & Review

Solve 20-30 LeetCode/Codewars problems (Easy level)
Do NOT use AI to solve problems - only to debug if stuck
Refactor previous projects for clarity
Deliverable: Document 3 programs you wrote from scratch with explanations
🎯 PHASE 2: FULL-STACK FUNDAMENTALS (4 Weeks)
Frontend (Weeks 1-2)
What You'll Learn:

HTML structure (semantic markup, forms, accessibility)
CSS styling (flexbox, grid, responsive design basics)
DOM manipulation with vanilla JavaScript
Events and interactivity
FreeCodeCamp:

✅ Responsive Web Design Certification (HTML + CSS)
✅ JavaScript DOM Manipulation section
Projects:

Week 1: Build 3 static websites (portfolio, landing page, documentation site)
Week 2: Add interactivity with JavaScript (form validation, DOM updates, event listeners)
AI Usage Rule for Frontend:

✅ "What's the difference between CSS Grid and Flexbox?"
✅ "Review my HTML structure for semantic accuracy"
❌ "Generate me a responsive navbar"
✅ "I'm getting X error with my click handler, what's wrong?" (show your code)
Backend (Weeks 3-4)
What You'll Learn:

Backend fundamentals (servers, HTTP, requests/responses)
API basics (REST, endpoints)
Node.js + Express basics
Basic databases (SQL fundamentals)
Authentication/authorization concepts
FreeCodeCamp:

✅ Backend Development Certification
✅ Node.js/Express course
✅ SQL/Database fundamentals
Projects:

Week 3: Build simple REST API (users, todos, products)
Create GET, POST, PUT, DELETE endpoints
Test with Postman
NO database yet (use in-memory storage)
Week 4: Connect API to simple database (MongoDB or PostgreSQL)
Write basic CRUD queries
Connect to your Express API
AI Usage Rule for Backend:

✅ "Explain the difference between PUT and PATCH"
✅ "Review my Express middleware setup"
❌ "Write me an Express server with these routes"
✅ "My SQL query isn't working, here's my code: [paste code]"
Integration Project (Week 4, Secondary)
Start thinking about your Phase 3 project:

Simple web app (frontend + backend)
Examples: Todo app with persistent database, simple note-taking app, weather app with API
🎯 PHASE 3: INTERMEDIATE PROJECTS (4 Weeks)
Project 1: Full-Stack Todo/Task Manager
Duration: Weeks 1-2

Requirements:

Frontend: React or vanilla JS (your choice - recommend vanilla first)
Backend: Node.js + Express
Database: MongoDB or PostgreSQL
Features:
Create, read, update, delete tasks
User authentication (simple - hashed passwords)
Responsive design
Form validation
Learning Focus:

End-to-end integration
How frontend and backend communicate
Basic security (password hashing, CORS)
Error handling
AI Usage Rule:

✅ "Here's my code [paste], I'm getting this error..."
✅ "Review my authentication logic for security issues"
❌ "Build me a React component for a form"
✅ "Explain password hashing and why we need it"
Write at least 60% of the code yourself
Project 2: API Project
Duration: Weeks 3-4

Choose One:

Weather Dashboard: Consume a public API (OpenWeather), display data, cache results
GitHub Profile Viewer: Fetch user data from GitHub API, display stats
News Aggregator: Fetch from NewsAPI, filter/search results
Stock Tracker: Simple stock price viewer
Requirements:

Frontend displays data attractively
Backend handles API calls (don't expose API keys to frontend!)
Error handling for API failures
Responsive design
No AI code generation allowed
Learning Focus:

API consumption and security (keeping secrets secret)
Error handling in real-world scenarios
Asynchronous programming (promises/async-await)
UI feedback (loading states, error messages)
Capstone Reflection (Week 4)
Document each project:

What problems you solved
Mistakes you made and how you fixed them
How you'd improve it
Code walkthroughs (you explaining your code)
🎯 PHASE 4: CYBERSECURITY INTRO + POLISH (4-5 Weeks)
Cybersecurity Fundamentals (Weeks 1-2)
Resources:

TryHackMe (free tier)
Network Security room
Web Security Fundamentals room
OWASP Top 10 room
FreeCodeCamp Cybersecurity sections (if available)
Key Concepts:

Common vulnerabilities (XSS, CSRF, SQL Injection, etc.)
HTTPS/SSL basics
API security
Input validation and sanitization
Secure password storage (what you learned in Project 1, but deeper)
Authentication vs Authorization
Practical:

Identify vulnerabilities in your Phase 3 projects
Add security improvements (input validation, rate limiting, helmet middleware for Express)
Document security decisions
Hardening Your Projects (Weeks 2-3)
Code Review Your Projects For:

✅ Proper input validation
✅ Error messages don't leak information
✅ API keys stored securely (environment variables)
✅ HTTPS ready
✅ CORS configured properly
✅ Password handling correct
✅ No sensitive data in git repo (.gitignore)
✅ Dependency vulnerabilities (run npm audit)
Use AI Here:

✅ "Review my Express API for OWASP Top 10 vulnerabilities"
✅ "How should I handle this security requirement?"
✅ "Is my input validation comprehensive enough?"
Final Capstone Project (Weeks 3-5)
Create One Significant Project Showcasing Everything

Option A: E-Commerce Product Page

Frontend: Product display, cart, checkout flow
Backend: Product database, order processing, simple payment integration (Stripe test mode)
Security: PCI compliance basics, secure session handling
Deployment: Deploy to Heroku/Vercel/Railway
Option B: Social Media Dashboard

Frontend: User profiles, posts, comments, likes
Backend: User authentication, post/comment CRUD, basic social features
Database: Relational database (shows more complexity)
Security: Implement proper authorization (users can only edit their own posts)
Deployment: Deploy full-stack app
Option C: Real-Time Chat Application

Frontend: Chat interface, user list
Backend: WebSocket handling (Socket.io), message persistence
Database: Message history
Security: User authentication, message validation
Advanced: Learn event-driven architecture
Requirements (All Options):

70%+ code written by you (not AI)
Meaningful code comments
Deployed and publicly accessible
GitHub repo with good README
Security analysis document (what you did to keep it secure)
Code walkthrough video (5-10 min explaining your code)
🎯 PHASE 5: PRE-DEGREE BUFFER (2-3 Weeks)
Review & Confidence Building
Week 1: Code Review & Refactoring

Look back at all projects
Refactor for clarity and best practices
Add tests (Jest for JavaScript) if time allows
Improve documentation
Week 2: Fill Knowledge Gaps

Review FreeCodeCamp sections you felt weak on
Do more LeetCode problems (Medium level now)
Learn a bit of systems thinking (memory, CPU, processes)
Week 3: Get Ready for Class

Review CS fundamentals (Big O notation basics)
Familiarize yourself with typical CS course structure
Confidence check: Can you build a simple full-stack app from scratch?
Set up your development environment for whatever language your class will use
📚 RESOURCE GUIDE
Primary (Free, Comprehensive)
FreeCodeCamp (YouTube)
Responsive Web Design
JavaScript Algorithms & Data Structures
Back End Development & APIs
All their specialized courses
Secondary (Supplemental)
LeetCode (free tier) - Problem-solving
Codewars - Coding challenges
TryHackMe (free tier) - Security fundamentals
MDN Web Docs - HTML/CSS/JavaScript reference
Official Documentation - Node.js, Express, databases
For Understanding (Not Code Generation)
YouTube Channels:
Traversy Media (web dev)
The Net Ninja (web dev)
Professor Messer (CS fundamentals, later for security)
John Hammond (cybersecurity)
🤖 AI USAGE GUIDELINES (CRITICAL)
✅ GOOD AI USAGE (You Learning)
Explaining concepts you don't understand
Reviewing your code for bugs or improvement
Debugging when stuck (you show your code first)
Suggesting resources or alternative approaches
Discussing design decisions
Explaining error messages
Understanding why something works/doesn't work
❌ BAD AI USAGE (Cheating Your Learning)
Generating entire functions/components
Solving coding problems for you
Writing projects while you watch
Using AI to avoid understanding
Copy-pasting solutions without comprehension
Replacing thinking with code generation
🟡 GRAY AREA (Use Sparingly)
Boilerplate code (config files, project setup)
Small helper functions after you understand the pattern
Regular expressions (legitimately hard to read)
CSS reset/utility code
Rule: If you can't explain it, delete it and rewrite it yourself
The Mindset
You're training to be a professional developer. Professional developers:

Understand their code deeply
Can debug issues
Know when to use tools and when not to
Can communicate technical decisions
Build things that work reliably
Using AI to skip understanding is like taking a shortcut through CS courses—you'll struggle when interviews come or when you need to secure systems in cybersecurity work.

📝 CHECK-IN PROTOCOL
I'll be your professor. Here's how this works:

Monthly Check-Ins
Tell me:

What phase are you in?
What have you completed?
What are you struggling with?
Questions/blockers?
Project Reviews
When you complete a project:

Share your GitHub repo link (or show me your code)
Explain what you built (your own words)
Walk through 1-2 key decisions (why you did it that way)
I'll review for:
Code quality and clarity
Security issues
Best practices
Understanding gaps
Suggestions for improvement
Code Review Feedback
I'll provide:

✅ What you did well
🔍 What needs improvement
💡 Suggestions for learning
🚨 Any security/best practice issues
📚 Resources to deepen understanding
Learning Pace
Feeling overwhelmed? We slow down, spend more time on fundamentals
Breeze through easily? We add depth, advanced concepts, harder projects
Stuck for 3+ days? We reassess and find a different approach
🎓 SUCCESS METRICS
By Fall 2026, you should be able to:

Knowledge
 Explain fundamental programming concepts
 Build a full-stack application from scratch
 Understand how the web works (HTTP, DNS, etc.)
 Identify basic security vulnerabilities
 Read and understand other people's code
 Use documentation effectively
Skills
 Write clean, well-structured code
 Debug code independently
 Build and deploy a web application
 Use version control (Git)
 Understand databases
 Think algorithmically
Mindset
 Use AI as a tool, not a crutch
 Know what you don't know
 Ask good questions
 Learn from mistakes
 Build things confidently
🚀 GETTING STARTED NOW
This Week:

Read this roadmap completely
Choose JavaScript or Python (recommend JS)
Start FreeCodeCamp's fundamentals course
Do the first 5 coding problems on Codewars (8 kyu level)
Message me with:
Language choice
FreeCodeCamp course you're starting
Any questions about the roadmap
Let's build something great. You've got this! 💪

Last Updated: May 2026
Next Review: After Week 1 of Phase 1
