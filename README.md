# Digital-Card 
I developed this project as my first React application project to practice my skills and deepen my understanding of the React library. The project is a simple, elegant card-style layout built using React. This project showcases personal or professional information of the user through a clean user-friendly interface. As my first React project, it showcases foundational knowledge of the React library, including component-based architecture, styling, and responsive design principles.

<br>
<br>

🚀 **Project Overview**

This is a Next.js 16 React application built with TypeScript and Tailwind CSS that creates an interactive flashcard learning system. The app allows users to cycle through flashcards, flip them to reveal answers, and toggle between light/dark themes.


<br>

✨ **Features**

Built with **React JSX**

Custom **CSS styling**

Icons integrated via Google Fonts (Material Symbols)

Component-based architecture

Responsive and modern UI

<br>

🛠️ **Tech Stack**

+ Frontend Framework: **React.js**

+ Styling: **CSS (vanilla)**

+ Icons: **Google Fonts (Material Symbols)**

+ Language: **JavaScript (React JSX)**

<br>

📁 **Project Structure & architecture**

1. Framework & Build System
* Next.js 16: React framework with App Router
* TypeScript: Type safety throughout the application
* Tailwind CSS v4: Utility-first CSS framework with dark mode support
* ESLint: Code linting and formatting

<br>

3. Core Dependencies
* React 19: UI library with hooks
* Framer Motion: Animation library for smooth transitions
* next-themes: Theme management for light/dark mode

```
flashcard/
├── app/                    # Next.js App Router
│   ├── layout.tsx         # Root layout with providers
│   ├── page.tsx           # Home page
│   └── globals.css        # Global styles + theme variables
├── components/            # React components
│   ├── providers.tsx      # Theme provider wrapper
│   ├── ui/               # UI components
│   │   └── Navbar.tsx    # Header with menu
│   └── flashcard/        # Flashcard-specific components
│       ├── Flashcard.tsx
│       └── FlashcardContainer.tsx
├── data/                 # Static data
│   └── flashcards.ts
├── hooks/               # Custom React hooks
│   └── useFlashcards.ts
├── types/               # TypeScript definitions
│   └── flashcard.ts
└── package.json         # Dependencies & scripts
```

<br>
<br>

🧑‍💻 **How to Run Locally**

Clone the repository:

bash
Copy
Edit
git clone https://github.com/riaanHarwood/Digital-Card.git
cd Digital-Card
Install dependencies:

bash
Copy
Edit
npm install
Start the development server:

bash
Copy
Edit
npm start

<br>

**Please Note:**
This is my first project using React, created to understand component composition and JSX syntax. I'm continuously improving and iterating on the design and code quality as I learn more about React best practices.

The profile image on the card is AI generated for testing and simplicity purposes. 

**License**
This project is open-source and available under the MIT License.

