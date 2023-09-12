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

## Project Structure
### Top lavel folders
- `app`: for App router 
- `page` : for Page router
- `public`: for storing static assets 
- `src`: optional aplication source folder

### Top lavel files 
- `next.config.js`: Configuration file for Next.js
- `package.json`: Project dependencies and scripts
- `instrumentation.ts`: OpenTelemetry and Instrumentation file
- `middleware.ts`: Next.js request middleware
- `.env`: Environment variables
- `.env.local`: Local environment variables
- `.env.production`: Production environment variables
- `.env.development`: Development environment variables
- `.eslintrc.json`: Configuration file for ESLint
- `.gitignore`: Git files and folders to ignore
- `next-env.d.ts`: TypeScript declaration file for Next.js
- `tsconfig.json`: Configuration file for TypeScript
- `jsconfig.json`: Configuration file for JavaScript
- `postcss.config.js`: Configuration file for Tailwind CSS

### Routing files 
- `layout`: Layout components 
- `page`: Page components 
- `loading`: Loading UI components 
- `not-found`: Not found UI components 
- `error`: Error UI components 
- `global-error`: Global error UI components 
- `route`: API endpoint components 
- `template`: Re-rendered layout components 
- `default`: Parallel route fallback page components 

### Nested Route
- `folder`:Route segment
- `folder/folder`: Nested route segment

### Dynamic Route
- `[folder]`: Dynamic Route segment
- `[...folder]`: catch all routes route segment
- `[[...folder]]`: optional catch all routes route segment

### Page routing convention
- `_app`: Custom App components 
- `_document`: Custom Document components 
- `_error`: Custom Error Page components 
- `404`: 404 Error Page components 
- `500`: 500 Error Page components
- `index`: Home page 

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
