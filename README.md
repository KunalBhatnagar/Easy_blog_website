# Easy_blog_website

A dynamic blog management system built with modern web technologies. This project leverages API calls to enable seamless CRUD operations (Create, Read, Update, Delete) on a blog website. It supports multiple routes, single-page handling, and robust error management to ensure a smooth user experience.

---

## Features

- **Write Blogs**: Create new blog posts with ease.
- **Update/Edit Blogs**: Modify existing blog entries.
- **Delete Blogs**: Remove blogs you no longer need.
- **API Integration**: Utilizes API calls for fetching and updating blog data.
- **Error Handling**: Comprehensive error management ensures stability and reliability.
- **Multiple Routes**: Efficient routing for managing pages and API responses.

---

## Technologies Used

### Frontend
- **HTML**: Markup for building the structure of the web pages.
- **CSS**: Styling for creating a visually appealing interface.
- **Embedded JavaScript (EJS)**: Template engine for rendering dynamic content.

### Backend
- **Node.js**: Server-side JavaScript runtime environment.
- **Express.js**: Fast, minimal, and flexible Node.js framework.
- **Axios**: Promise-based HTTP client for API calls.

### Middleware
- **body-parser**: Parses incoming request bodies for easy access.
- **JSON**: Manages JSON payloads for API communication.

### Other
- **API Integration**: Powers CRUD functionality with seamless data flow.

---

## Directory Structure
*P.S.: Some of the URLs in the code to locate files may need to change.*

---

## Routes

| HTTP Method | Endpoint     | Description          |
|-------------|--------------|----------------------|
| GET         | `/blogs`     | Retrieve all blogs   |
| POST        | `/blogs`     | Create a new blog    |
| PUT         | `/blogs/:id` | Update a blog by ID  |
| DELETE      | `/blogs/:id` | Delete a blog by ID  |

---

## Future Improvements

- **Authentication**: Add user login and authorization features.
- **Search and Filter**: Enhance the UX with search and filter options.
- **Database Integration**: Connect to a database for persistent storage.
