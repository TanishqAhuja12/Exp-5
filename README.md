  🚀 Basic Client-Side Routing Using React Router

📌 Aim To implement basic client-side routing in a Single Page Application (SPA) using React Router.

🛠️ Software Requirements

Node.js
React
React Router DOM
Web Browser
📖 Theory Routing in a Single Page Application (SPA) allows navigation between different views without reloading the entire page.

React Router enables smooth client-side routing by mapping URLs to React components using:

BrowserRouter
Routes
Route
Client-side routing is a technique used in modern web applications where navigation between pages happens without reloading the entire webpage. Instead of requesting a new HTML page from the server each time, the application dynamically updates the view using JavaScript.

In traditional websites: Every link click sends a request to the server. The server responds with a new HTML page. The browser reloads completely. In a Single Page Application (SPA): Only one HTML file is loaded initially. JavaScript handles navigation. Components are rendered dynamically based on the URL.

React Router is a powerful routing library for React applications that allows developers to define routes declaratively. It works by monitoring the browser’s URL and rendering the corresponding component when the URL changes.

Important Concepts in React Router:

• BrowserRouter – Wraps the application and enables routing using HTML5 history API. • Routes – A container for all route definitions. • Route – Maps a URL path to a specific component. • Exact Matching – Ensures correct path matching.

Advantages of Client-Side Routing:

Faster navigation Reduced server load Better user experience Seamless transitions No full-page refresh

This experiment demonstrates how URLs can be mapped to React components to create a dynamic and interactive web application.

This improves performance and provides a seamless user experience.

<img width="1764" height="1099" alt="Screenshot 2026-02-19 152100" src="https://github.com/user-attachments/assets/ca18bbf0-ccc6-4f64-b195-e325b8504db6" />
<img width="1775" height="1106" alt="Screenshot 2026-02-19 152050" src="https://github.com/user-attachments/assets/a442d135-c61f-4920-9e11-2600974e1d80" />
<img width="1773" height="1102" alt="Screenshot 2026-02-19 152034" src="https://github.com/user-attachments/assets/cf5af90c-4d5a-43c6-bd8b-60f26c403a1d" />
<img width="1762" height="1080" alt="Screenshot 2026-02-19 151823" src="https://github.com/user-attachments/assets/0f6e81f6-e175-4156-9304-9399698ee457" />
<img width="1764" height="1100" alt="Screenshot 2026-02-19 151814" src="https://github.com/user-attachments/assets/b30ddc94-15b9-436d-874e-c61eb05f4516" />

<img width="1757" height="1079" alt="Screenshot 2026-02-19 151819" src="https://github.com/user-attachments/assets/48479013-03c6-449d-a52e-b96fd73137c1" />






Experiment: Multi-Page SPA Using Routing

🌐 Multi-Page SPA Using Routing

📌 Aim To create a multi-page Single Page Application (SPA) using client-side routing.

🛠️ Software Requirements

Node.js
React
React Router DOM
Web Browser
📖 Theory A Single Page Application dynamically updates content without reloading the browser.

React Router enables:

Multiple routes
Component-based navigation
Clean URL structure
Faster page transitions
A Multi-Page Single Page Application may sound contradictory, but it refers to creating multiple views within a single-page architecture using routing.

In this approach: The application behaves like a multi-page website. Internally, it is still a single HTML file. React dynamically renders different components based on the route.

Routing allows us to structure applications logically. Each component represents a page such as: Home About Services Contact


Experiment: Navigation Using Link Component

📌 Aim To implement navigation links in a SPA using React Router Link component.

🛠️ Software Requirements

Node.js
React
React Router DOM
Web Browser
📖 Theory The Link component allows smooth navigation between routes without refreshing the page.

Unlike the traditional tag, Link:

Prevents page reload
Maintains SPA behavior
Improves performance
Navigation is an essential part of any web application. In traditional HTML, navigation is done using the tag. However, in React SPAs, using causes the browser to reload the entire page, which breaks SPA behavior.

React Router provides the Link component to handle navigation efficiently.

How Link Works: It prevents default browser refresh behavior. It updates the URL. It renders the corresponding component instantly. It maintains application state.

