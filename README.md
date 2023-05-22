# AstralRouter

AstralRouter is a powerful routing library inspired by React Router. Designed for modern web applications, AstralRouter provides an efficient and flexible solution for managing navigation in your React application.

## Key Features

- **Dynamic Routing**: AstralRouter allows you to define routes dynamically, making it easy to create applications with content and functionality that adapts to user needs.
- **Nested Route Handling**: With AstralRouter, you can easily build nested and hierarchical routes to organize your application in a logical and modular way.
- **Smooth Transitions**: AstralRouter includes smooth and customizable transitions between routes, providing a seamless and visually appealing navigation experience for users.
- **Advanced State Management**: AstralRouter allows you to access and manipulate the state of the current route, enabling you to perform specific actions based on the user's location in the application.
- **React Hooks Compatibility**: AstralRouter seamlessly integrates with React Hooks, allowing you to leverage the power of Hooks to handle routing in a simple and declarative way.

AstralRouter is designed to be user-friendly, scalable, and customizable, providing a solid foundation for your routing needs in React applications.

## Installation

To install AstralRouter, follow these steps:

1. Run the following command in your terminal:

   ```shell
   npm install astral-router

2. Import AstralRouter into your project:

   ```shell
   import { Astral, AstralRoute, AstralLink } from 'astral-router';

3. Start using AstralRouter in your application:

## Usage Example

Here's a basic example of how you can use AstralRouter in your application:

   ```shell 
   import { Astral, AstralRoute, AstralLink } from 'astral-router';
   
   function App() {
     return (
       <Astral>
         <nav>
           <ul>
             <li>
               <AstralLink to="/">Home</AstralLink>
             </li>
             <li>
               <AstralLink to="/about">About</AstralLink>
             </li>
             <li>
               <AstralLink to="/contact">Contact</AstralLink>
             </li>
           </ul>
         </nav>

         <AstralRoute path="/" exact>
           <Home />
         </AstralRoute>
         <AstralRoute path="/about">
           <About />
         </AstralRoute>
         <AstralRoute path="/contact">
           <Contact />
         </AstralRoute>
       </Astral>
     );
   }
   ```
   
Happy astral routing! ✨

We hope AstralRouter proves to be a useful tool for your routing needs in React applications.
