# Next.js Tutorial

Welcome to the Next.js tutorial! In this tutorial, we'll cover...

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Creating a Next.js App](#creating-a-nextjs-app)
- [Routing](#routing)
- [Styling](#styling)
- [Deployment](#deployment)
- [Conclusion](#conclusion)

## Introduction
NextJs is react framework for building fullstack application. Basically we use React to build user interface and next for additional features. 

### NextJs features 
- **Rendering:** server-side rendering which enhances page load times and SEO by rendering pages on the server before sending them to the client.

- **Static Site Generation :** Next.js supports SSG, allowing you to pre-render pages at build time.
  
- **Routing:** File-system based routing supports layout, nested routing, error handling, loading states. 

- **API Routes:** create serverless API routes within your Next.js application, simplifying backend development.

- **CSS Support:** Next.js offers various options for styling, including CSS Modules, Styled Components, tailwind and CSS-in-JS.


## Getting Started
### Installation 
Run following command to set up everything: 
` npx create-next-app@latest ` 

or if you are already on the project folder 
` npx create-next-app@latest .` 
After you run that command you'll see following prompts: 
```
√ What is your project named? ... first-app
√ Would you like to use TypeScript? ... No / Yes
√ Would you like to use ESLint? ... No / Yes
√ Would you like to use Tailwind CSS? ... No / Yes
√ Would you like to use `src/` directory? ... No / Yes
√ Would you like to use App Router? (recommended) ... No / Yes
√ Would you like to customize the default import alias? ... No / Yes

```
You can choose the option according your preference, in this tutorial I used typescript. I chose App router for this tutorial as this has additional feature, 
however you can choose No (page router). 

### Creating directories
Unlike React.js, Next.js use file-based routing. It means that we no longer have to define each router, import router, or wrap the main component with router. Instead all routes are determined by how you strucuture your folders.
You should have App folders, and layout.tsx and page.tsx files inside after installation. 

### Run the development server
- Run `npm run dev` to start the server
- Visit `http://localhost:3000` to view
- Edit app/page.tsx file and save to see the update 

## Creating a Next.js App
...

## Routing
...

## Styling
...

## Deployment
...

## Conclusion
...
