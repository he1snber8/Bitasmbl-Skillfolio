# Bitasmbl-Skillfolio

A modern, responsive React.js portfolio page styled with Tailwind CSS that dynamically showcases a candidate’s skill set using component-based architecture and React state management.

## Tech Stack
- React
- Tailwind CSS

## Requirements
- Use React functional components and hooks
- Style UI using Tailwind CSS utility classes
- Manage dynamic data with component state

## Installation
1. Clone the repository
   bash
   git clone https://github.com/<your-username>/Bitasmbl-Skillfolio.git
   
2. Navigate to the project directory
   bash
   cd Bitasmbl-Skillfolio
   
3. Install dependencies
   bash
   npm install
   
4. (Optional) Set up environment variables
   - Create a `.env` file in the project root
   - Define any needed variables (e.g., `REACT_APP_API_URL`)

## Usage
- Start the development server:
  bash
  npm start
  
- Open http://localhost:3000 in your browser to view the portfolio.
- To create a production build:
  bash
  npm run build
  

## Implementation Steps
1. Scaffold the React application:
   bash
   npx create-react-app .
   
2. Install and configure Tailwind CSS:
   bash
   npm install -D tailwindcss postcss autoprefixer
   npx tailwindcss init -p
   
   - Update `tailwind.config.js` to include your `src` paths.
   - Add the Tailwind directives to `src/index.css`:
     css
     @tailwind base;
     @tailwind components;
     @tailwind utilities;
     
3. Create a `SkillCard` component:
   - Build a functional component to display individual skill details.
   - Apply Tailwind utility classes for styling and responsive design.
4. Create a `SkillList` component:
   - Use the `useState` hook to define an array of skill objects.
   - Map over the skills array to render multiple `SkillCard` components.
5. Implement React hooks and state management:
   - Use `useState` for dynamic skill data.
   - Optionally use `useEffect` to fetch or update data from external sources.
6. Style the UI:
   - Utilize Tailwind CSS classes for layout, spacing, colors, and typography.
   - Ensure responsiveness with Tailwind’s breakpoint utilities.
7. Test and iterate:
   - Verify the layout across different screen sizes.
   - Refine components and update styling as needed.
8. Build and deploy:
   bash
   npm run build