# Movie: Mini Streaming App

MovieX is a **mini streaming app** where you can explore trailers for the latest movies and TV shows. Browse genres, search for top hits, and preview trending content with ease. Perfect for quick browsing, anytime, anywhere! 🚀

---

## Features
- 🎮 **Explore Latest Trailers**: Watch trailers for trending movies and TV shows.
- 🔍 **Search by ID or Query**: Find specific movies or shows using their ID or by searching with keywords.
- 🎦 **Browse by Genre**: Easily discover content by exploring different genres.
- 🔐 **User Authentication**: Login and signup functionality for a personalized experience.
- ⚡ **Fast and Responsive**: Enjoy a seamless browsing experience.

---

## Demo
🔗 Try Movie live: [**MovieX Demo**](https://shimmering-kitsune-443682.netlify.app/)

---

## Getting Started

To run Movie locally, follow these steps:

### 1. Clone the Repository
```bash
git clone <repository_url>
```

### 2. Navigate into the Directory
```bash
cd movieX
```

### 3. Install Dependencies
```bash
npm install
```

### 4. Add Environment Variables
Create a `.env` file in the root directory and add the following keys:
```
API_TOKEN=your_api_token
API_KEY=your_api_key
```

### 5. Start the Development Server
```bash
npm start
```

---

## Directory Structure
Here’s the directory structure for the project:

```
movieX/
├── public/
│   ├── src/
│   │   ├── index.jsx
│   │   ├── movie.jsx
│   │   └── apiService.jsx
│   ├── styles/
│   │   ├── index.css
│   │   └── movie.css
├── src/
│   ├── index.jsx
│   ├── login.jsx
│   ├── movie.jsx
│   └── signup.jsx
├── .gitignore
├── README.md
├── package.json
└── .env (Environment variables)
```

---

## API Endpoints

### Primary Base URL
```plaintext
https://shimmering-kitsune-443682.netlify.app/
```

### Search Content by ID
- **For TV Shows**:
  ```
  GET /tv/${ID}/videos?language=en-US
  ```
- **For Movies**:
  ```
  GET /movie/${ID}/videos?language=en-US
  ```

#### Parameters
| **Parameter** | **Type** | **Description**             |
|---------------|----------|-----------------------------|
| `id`          | `string` | **Required.** ID of the item to fetch. |

---

### Search Content by Query
- **Endpoint**:
  ```
  GET /search?q=${QUERY}
  ```

#### Parameters
| **Parameter** | **Type** | **Description**                   |
|---------------|----------|-----------------------------------|
| `q`           | `string` | **Required.** Query to fetch item.|

---

## Technologies Used
- **Frontend**: React, CSS
- **API**: TMDb or any movie database API
- **Deployment**: Netlify

---

## Contributing
We welcome contributions! 🎉

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add your message"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

---

## License
This project is licensed under the MIT License.

---

### Happy Coding! ✨

