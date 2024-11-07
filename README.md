# QuizMe: AI-Powered Quiz Platform

## Features

* **AI-Powered Question Generation:**  Generate quizzes on *any* topic using OpenAI's GPT API.  Choose the number of questions and whether you want multiple-choice or open-ended format.  For open-ended questions, QuizMe intelligently assesses the similarity of your answer to the correct one.
* **Multiple Quiz Formats:** Choose between multiple-choice (MCQ) and open-ended question formats. Open-ended questions challenge you to fill in missing keywords, providing a more engaging experience.
* **Interactive Gameplay:**  Enjoy a modern and intuitive user interface with smooth transitions and interactive elements. Control options with your keyboard for seamless navigation.
* **Detailed Statistics and History:** Track your progress with comprehensive statistics including average accuracy, time taken, and a review of past quiz attempts. A visually appealing word cloud displays popular quiz topics.
* **Dark and Light Mode:**  Switch between dark and light themes for a comfortable and customizable user experience.
* **Google Authentication:** Securely sign in with your Google account.
* **PlanetScale Database:**  Built on PlanetScale's cloud-based MySQL database for infinite scalability.
* **Modern Tech Stack:**  Built with cutting-edge technologies, including:
    * Next.js 13.4 with App Router and React Server Components
    * Tailwind CSS and Shadcn UI component library for beautiful and accessible styling
    * NextAuth.js for authentication
    * React Query for server-side data syncing
    * Prisma ORM for database interaction
    * TypeScript for type safety and improved developer experience

## Tech Stack

* **Frontend:** Next.js, React, TypeScript, Tailwind CSS, Shadcn UI, Lucid Icons, React D3 Cloud
* **Backend:** Node.js, Next.js API Routes, OpenAI API, Prisma, PlanetScale (MySQL)
* **Authentication:** NextAuth.js, Google OAuth
* **State Management:** React Query
* **Other:**  Zod (schema validation), React Hook Form, Axios, date-fns, string-similarity, keyword-extractor
