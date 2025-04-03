Lugoo is a context-aware, generative AI tool designed to simplify the complexities of immigration and asylum-related legal data. Originally conceived as a school project to address bureaucratic opacity, Lugoo leverages a conversational interface to provide tailored, case-specific legal guidance, helping users to navigate immigration processes with clarity.

Features
Conversational Chat Interface:
Engage in dynamic, interactive conversations with Lugoo to generate personalized asylum processes based on user inputs (e.g., nationality, age, gender, persecution type, and destination).

Asylum Process Generation:
Utilizes a Generative AI model (configured with an OpenAI client) to produce detailed, step-by-step instructions covering aspects such as application procedures, legal residence, health insurance access, and appeal processes.

User Authentication & Profile Management:
Users can register, log in, and edit their profiles (including username updates, password changes, and account deletion) via a secure authentication system that leverages Flask-Bcrypt for password hashing.

Chat History & Export Functionality:
Maintain a history of chat sessions, and export complete conversation transcripts as PDF files using PDFKit, ensuring users have a permanent record of the generated processes.

Modern UI Design:
A glassmorphism-inspired user interface with video backgrounds and sleek styling delivers an engaging and contemporary user experience across all pages (landing, about, chat, profile editing, etc.).

Technologies Used
Backend Framework: Flask

Database & ORM: SQLite with SQLAlchemy

User Authentication: Flask-Bcrypt

AI Integration: OpenAI API (configured with the gpt-4o-mini model)

PDF Export: PDFKit (requires wkhtmltopdf installation)

Markdown Conversion: Python-Markdown

Frontend: HTML templates with custom CSS (Glassmorphism style and video backgrounds)
