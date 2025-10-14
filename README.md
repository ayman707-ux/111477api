# 🎬 Movie Parser API# 🎬 Movie Parser API# 🎬 Movie Parser API# Movie Parser API



A RESTful API for parsing movie and TV show links from directory listings with TMDB integration.



## 📋 API Endpoints SummaryA RESTful API for parsing movie and TV show links from directory listings with TMDB integration.



| Method | Endpoint | Description |

|--------|----------|-------------|

| `GET` | `/api/tmdb/search/{query}` | Search movies by title |## 🚀 What Does This Project Do?A powerful RESTful API for parsing movie and TV show links from directory listings with seamless integration to The Movie Database (TMDB). Perfect for building movie streaming applications, media servers, or content discovery tools.An API for parsing movie and show links from directory listings with TMDB integration.

| `GET` | `/api/tmdb/{tmdb_id}` | Get movie by TMDB ID |

| `GET` | `/api/tmdb/movie/{tmdb_id}` | Get movie details by TMDB ID |

| `GET` | `/api/tmdb/tv/{tmdb_id}` | Get TV show by TMDB ID |

| `GET` | `/api/tmdb/tv/{tmdb_id}/season/{season}` | Get TV season |- **Parse movie directories** and extract downloadable links

| `GET` | `/api/tmdb/tv/{tmdb_id}/season/{season}/episode/{episode}` | Get TV episode |

| `GET` | `/api/movies/{movie_name}` | Get movie files by name |- **Search movies** using The Movie Database (TMDB) 

| `POST` | `/api/parse` | Parse custom URL |

| `POST` | `/api/parse-batch` | Parse multiple URLs |- **Get movie details** including posters, descriptions, and ratings## 🚀 What Does This Project Do?## Features

| `GET` | `/health` | API health check |

- **Handle multiple file formats** (mkv, mp4, avi, etc.)

## 🚀 What Does This Project Do?

- **Batch process** multiple URLs at once

- **Parse movie directories** and extract downloadable links

- **Search movies** using The Movie Database (TMDB) 

- **Get movie details** including posters, descriptions, and ratings

- **Handle multiple file formats** (mkv, mp4, avi, etc.)## 🛠️ Quick StartThis API helps you:- Parse HTML directory listings to extract movie file links

- **Batch process** multiple URLs at once



## 🛠️ Quick Start

### 1. Install Dependencies- **Parse movie directories** from file servers and extract downloadable links- RESTful API endpoints

### 1. Install Dependencies

```bash```bash

npm install

```npm install- **Search movies** using The Movie Database (TMDB) - Support for various video file formats (mkv, mp4, avi, etc.)



### 2. Get TMDB API Key (Optional)```

1. Go to https://www.themoviedb.org/settings/api

2. Create free account and get API key- **Get movie details** including posters, descriptions, genres, and ratings- Filter out non-video files and parent directory links

3. Set environment variable:

```bash### 2. Get TMDB API Key (Optional)

# Windows

set TMDB_API_KEY=your_api_key_here1. Go to https://www.themoviedb.org/settings/api- **Handle multiple file formats** (mkv, mp4, avi, etc.)- **TMDB Integration**: Search movies by TMDB ID and automatically construct URLs



# Mac/Linux  2. Create free account and get API key

export TMDB_API_KEY=your_api_key_here

```3. Set environment variable:- **Format file sizes** in human-readable formats (GB, MB, etc.)- **TMDB Search**: Search for movies on The Movie Database



### 3. Start Server```bash

```bash

npm start# Windows- **Batch process** multiple URLs at once- Automatic movie name construction (Title + Year format)

```

set TMDB_API_KEY=your_api_key_here

Visit: http://localhost:3000/health



## 📖 API Endpoints Details

# Mac/Linux  

### Search Movies

```export TMDB_API_KEY=your_api_key_herePerfect for developers who want to build movie apps, media centers, or content discovery platforms!## Installation

GET /api/tmdb/search/zodiac

``````



### Get Movie by TMDB ID

```

GET /api/tmdb/562### 3. Start Server

```

```bash## 🛠️ Prerequisites (What You Need)1. Install dependencies:

### Get Movie by Name

```npm start

GET /api/movies/Zodiac%20(2007)

`````````bash



### Get TV Show

```

GET /api/tmdb/tv/268Visit: http://localhost:3000/healthBefore you start, make sure you have:npm install

```



### Get TV Season

```## 📖 API Endpoints```

GET /api/tmdb/tv/268/season/1

```



### Get TV Episode### Search Movies1. **Node.js** installed on your computer

```

GET /api/tmdb/tv/268/season/1/episode/4```

```

GET /api/tmdb/search/zodiac   - Download from: https://nodejs.org/2. (Optional) Configure TMDB API key for enhanced functionality:

### Parse Custom URL

``````

POST /api/parse

{   - Choose the LTS (Long Term Support) version   - Get a free API key from [TMDB](https://www.themoviedb.org/settings/api)

  "url": "https://example.com/movies/SomeMovie/"

}### Get Movie by TMDB ID

```

```   - To check if installed: Open terminal/command prompt and type `node --version`   - Set environment variable: `set TMDB_API_KEY=your_api_key_here`

### Batch Process

```GET /api/tmdb/1949

POST /api/parse-batch

{```   - Or edit `src/tmdbClient.js` and replace `YOUR_TMDB_API_KEY_HERE`

  "urls": ["url1", "url2"]

}

```

### Get Movie by Name2. **A code editor** (optional but recommended)

## 📋 Example Response

```

```json

{GET /api/movies/Zodiac%20(2007)   - VS Code (free): https://code.visualstudio.com/3. Start the server:

  "success": true,

  "movieName": "Zodiac (2007)",```

  "fileCount": 7,

  "files": [   - Or any text editor you prefer```bash

    {

      "name": "movie.mkv",### Parse Custom URL

      "url": "https://example.com/movies/Zodiac/movie.mkv",

      "size": "43511019082",```npm start

      "sizeFormatted": "40.52 GB"

    }POST /api/parse

  ],

  "tmdb": {{3. **Basic terminal/command prompt knowledge**```

    "id": 562,

    "title": "Zodiac",  "url": "https://example.com/movies/SomeMovie/"

    "year": "2007",

    "overview": "Movie description...",}   - Don't worry, we'll guide you through each step!

    "posterPath": "https://image.tmdb.org/t/p/w500/poster.jpg",

    "genres": [{"id": 80, "name": "Crime"}],```

    "runtime": 158

  }For development with auto-reload:

}

```### Batch Process



## 🧪 Test Examples```## 📥 Installation & Setup```bash



### Popular TMDB IDs:POST /api/parse-batch

**Movies:**

- Zodiac (2007): `562`{npm run dev

- John Wick (2014): `245891`

- The Matrix (1999): `603`  "urls": ["url1", "url2"]



**TV Shows:**}### Step 1: Download the Project```

- The 100: `268`

- Marvel's Daredevil: `38472````

- The Walking Dead: `1402`

```bash

### Test Commands:

```bash## 📋 Example Response

# Search

curl http://localhost:3000/api/tmdb/search/matrix# If you have git installed:## API Endpoints



# Get movie```json

curl http://localhost:3000/api/tmdb/603

{git clone [your-repo-url]

# Get TV show

curl http://localhost:3000/api/tmdb/tv/268  "success": true,



# Get TV season  "movieName": "Zodiac (2007)",cd 111477### GET /api/movies/:movieName

curl http://localhost:3000/api/tmdb/tv/268/season/1

  "fileCount": 7,

# Health check

curl http://localhost:3000/health  "files": [Parse a movie directory and return available file links.

```

    {

## 🏗️ Project Structure

      "name": "movie.mkv",# Or download the ZIP file and extract it

```

src/      "url": "https://example.com/movies/Zodiac/movie.mkv",

├── index.js          # Main server

├── httpClient.js     # HTTP requests      "size": "43511019082",```Example:

├── parser.js         # HTML parsing

├── tmdbClient.js     # TMDB integration      "sizeFormatted": "40.52 GB"

└── test.js           # Tests

```    }```



## 🚨 Troubleshooting  ],



**Dependencies issues:**  "tmdb": {### Step 2: Install DependenciesGET /api/movies/Zodiac%20(2007)

```bash

npm install    "id": 1949,

```

    "title": "Zodiac",Open your terminal/command prompt in the project folder and run:```

**Port in use:**

```bash    "year": "2007",

PORT=8080 npm start

```    "overview": "Movie description...",```bash



**TMDB API errors:**    "posterPath": "https://image.tmdb.org/t/p/w500/poster.jpg",

- Check your API key is correct

- Verify TMDB account is activated    "genres": [{"id": 80, "name": "Crime"}],npm install### GET /api/tmdb/:tmdbId



## 🚀 Production    "runtime": 158



**Using PM2:**  }```**NEW**: Get movie files by TMDB ID. Automatically fetches movie details from TMDB, constructs the proper movie name format, and returns file links.

```bash

npm install -g pm2}

pm2 start src/index.js --name "movie-api"

``````



**Environment Variables:**

```bash

PORT=3000## 🧪 Test ExamplesThis will download all the required packages automatically.Example:

TMDB_API_KEY=your_api_key_here

```



---Popular TMDB IDs:```



**Made by Ayman with love ❤️ - 100% Open Source**- Zodiac (2007): `1949`

- John Wick (2014): `245891`### Step 3: Get Your Free TMDB API Key (Optional but Recommended)GET /api/tmdb/1949

- The Matrix (1999): `603`

```

```bash

# SearchThe TMDB integration gives you movie posters, descriptions, and ratings. It's completely free!(This will fetch "Zodiac (2007)" using TMDB ID 1949)

curl http://localhost:3000/api/tmdb/search/matrix



# Get movie

curl http://localhost:3000/api/tmdb/6031. **Go to TMDB website**: https://www.themoviedb.org/### GET /api/tmdb/search/:query



# Health check2. **Create a free account** (takes 2 minutes)**NEW**: Search for movies on TMDB by title.

curl http://localhost:3000/health

```3. **Go to API settings**: https://www.themoviedb.org/settings/api



## 🏗️ Project Structure4. **Request an API key** (it's instant and free)Example:



```5. **Copy your API key**```

src/

├── index.js          # Main serverGET /api/tmdb/search/zodiac

├── httpClient.js     # HTTP requests

├── parser.js         # HTML parsing### Step 4: Configure Your API Key```

├── tmdbClient.js     # TMDB integration

└── test.js           # Tests

```

You have two options:### POST /api/parse

## 🚨 Troubleshooting

Parse a custom URL and return file links.

**Dependencies issues:**

```bash**Option A: Environment Variable (Recommended)**

npm install

``````bashRequest body:



**Port in use:**# Windows (Command Prompt)```json

```bash

PORT=8080 npm startset TMDB_API_KEY=your_api_key_here{

```

  "url": "https://a.111477.xyz/movies/Zodiac%20(2007)/"

**TMDB API errors:**

- Check your API key is correct# Windows (PowerShell)}

- Verify TMDB account is activated

$env:TMDB_API_KEY="your_api_key_here"```

## 🚀 Production



**Using PM2:**

```bash# Mac/Linux### POST /api/parse-batch

npm install -g pm2

pm2 start src/index.js --name "movie-api"export TMDB_API_KEY=your_api_key_hereParse multiple URLs at once.

```

```

**Environment Variables:**

```bashRequest body:

PORT=3000

TMDB_API_KEY=your_api_key_here**Option B: Edit the Code Directly**```json

```

1. Open `src/tmdbClient.js`{

---

2. Find this line: `const TMDB_API_KEY = process.env.TMDB_API_KEY || 'xxxxxxx';`  "urls": ["url1", "url2"]

**Made by Ayman with love ❤️ - 100% Open Source**
3. Replace `'xxxxxxx'` with your actual API key}

```

### Step 5: Start the Server

```bash## Response Format

# For production:

npm start### Standard Movie Response

```json

# For development (auto-restarts when you make changes):{

npm run dev  "success": true,

```  "movieName": "Zodiac (2007)",

  "baseUrl": "https://a.111477.xyz/movies/Zodiac%20(2007)/",

You should see:  "fileCount": 7,

```  "files": [

Server running on port 3000    {

Visit: http://localhost:3000/health      "name": "Zodiac.2007.Directors.Cut.Bluray.1080p.TrueHD.5.1.AVC.REMUX-FraMeSToR.mkv",

```      "url": "https://a.111477.xyz/movies/Zodiac%20(2007)/Zodiac.2007.Directors.Cut.Bluray.1080p.TrueHD.5.1.AVC.REMUX-FraMeSToR.mkv",

      "size": "43511019082",

### Step 6: Test It's Working      "sizeFormatted": "40.52 GB"

Open your browser and go to: http://localhost:3000/health    }

  ]

You should see something like:}

```json```

{

  "status": "ok",### TMDB Enhanced Response

  "timestamp": "2025-10-14T...",When using TMDB endpoints, additional metadata is included:

  "uptime": 1.234,```json

  "tmdbApiConfigured": true{

}  "success": true,

```  "movieName": "Zodiac (2007)",

  "baseUrl": "https://a.111477.xyz/movies/Zodiac%20(2007)/",

🎉 **Congratulations! Your API is now running!**  "fileCount": 7,

  "files": [...],

## 📖 How to Use the API  "tmdb": {

    "id": 1949,

### Available Endpoints    "title": "Zodiac",

    "originalTitle": "Zodiac",

#### 1. 🔍 Search for Movies    "releaseDate": "2007-03-02",

```    "year": "2007",

GET /api/tmdb/search/[movie-name]    "overview": "The zodiac murders cause the lives of Paul Avery...",

```    "posterPath": "https://image.tmdb.org/t/p/w500/yNlJUOFPwaMuKhvhOHOFVy6KBYC.jpg",

    "backdropPath": "https://image.tmdb.org/t/p/w1280/zQ8QXaEhJXFUDILcpTMAg5yqO9F.jpg",

**Example:**    "genres": [{"id": 80, "name": "Crime"}, {"id": 18, "name": "Drama"}],

```    "runtime": 158,

http://localhost:3000/api/tmdb/search/zodiac    "imdbId": "tt0443706"

```  }

}

This returns a list of movies matching your search with their TMDB IDs.```



#### 2. 🎬 Get Movie Details by TMDB ID## Example TMDB IDs

```

GET /api/tmdb/[tmdb-id]- **Zodiac (2007)**: TMDB ID `1949`

```- **Zookeeper (2011)**: TMDB ID `8078`  

- **The Death of Superman (2018)**: TMDB ID `541982`

**Example:**

```## Usage Examples

http://localhost:3000/api/tmdb/1949

```### Fetch by TMDB ID (Recommended)

```bash

This gets the movie "Zodiac (2007)" with all details and available file links.curl http://localhost:3000/api/tmdb/1949

```

#### 3. 📁 Get Movie Files by Name

```### Search TMDB and then fetch

GET /api/movies/[movie-name]```bash

```# 1. Search for movie

curl http://localhost:3000/api/tmdb/search/zodiac

**Example:**

```# 2. Use TMDB ID from results

http://localhost:3000/api/movies/Zodiac%20(2007)curl http://localhost:3000/api/tmdb/1949

``````

#### 4. 🔗 Parse Custom URLs
```
POST /api/parse
Content-Type: application/json

{
  "url": "https://example.com/movies/SomeMovie/"
}
```

#### 5. ⚡ Batch Process Multiple URLs
```
POST /api/parse-batch
Content-Type: application/json

{
  "urls": [
    "https://example.com/movies/Movie1/",
    "https://example.com/movies/Movie2/"
  ]
}
```

#### 6. ❤️ Health Check
```
GET /health
```

### Example Response

When you request a movie, you get back detailed information:

```json
{
  "success": true,
  "movieName": "Zodiac (2007)",
  "baseUrl": "https://a.111477.xyz/movies/Zodiac%20(2007)/",
  "fileCount": 7,
  "files": [
    {
      "name": "Zodiac.2007.Directors.Cut.Bluray.1080p.TrueHD.5.1.AVC.REMUX-FraMeSToR.mkv",
      "url": "https://a.111477.xyz/movies/Zodiac%20(2007)/Zodiac.2007.Directors.Cut.Bluray.1080p.TrueHD.5.1.AVC.REMUX-FraMeSToR.mkv",
      "size": "43511019082",
      "sizeFormatted": "40.52 GB"
    }
  ],
  "tmdb": {
    "id": 1949,
    "title": "Zodiac",
    "originalTitle": "Zodiac",
    "releaseDate": "2007-03-02",
    "year": "2007",
    "overview": "The zodiac murders cause the lives of Paul Avery, David Toschi and Robert Graysmith to intersect...",
    "posterPath": "https://image.tmdb.org/t/p/w500/yNlJUOFPwaMuKhvhOHOFVy6KBYC.jpg",
    "backdropPath": "https://image.tmdb.org/t/p/w1280/zQ8QXaEhJXFUDILcpTMAg5yqO9F.jpg",
    "genres": [
      {"id": 80, "name": "Crime"},
      {"id": 18, "name": "Drama"}
    ],
    "runtime": 158,
    "imdbId": "tt0443706"
  }
}
```

## 🧪 Testing Examples

### Popular Movie TMDB IDs for Testing:
- **Zodiac (2007)**: ID `1949`
- **John Wick (2014)**: ID `245891`
- **The Matrix (1999)**: ID `603`
- **Zookeeper (2011)**: ID `8078`
- **The Death of Superman (2018)**: ID `541982`

### Test Commands:

**Search for a movie:**
```bash
curl http://localhost:3000/api/tmdb/search/matrix
```

**Get movie by TMDB ID:**
```bash
curl http://localhost:3000/api/tmdb/603
```

**Check API health:**
```bash
curl http://localhost:3000/health
```

## 🏗️ Project Structure

```
├── src/
│   ├── index.js          # Main server file (Express.js setup)
│   ├── httpClient.js     # HTTP requests and URL building
│   ├── parser.js         # HTML parsing for movie directories
│   ├── tmdbClient.js     # TMDB API integration
│   ├── test.js           # Basic tests
│   └── testTmdb.js       # TMDB-specific tests
├── package.json          # Project dependencies and scripts
├── test-client.html      # Simple web interface for testing
└── README.md             # This file!
```

## 🔧 How It Works

### 1. **Movie Directory Parsing**
- The API fetches HTML from movie directory URLs
- Uses Cheerio (jQuery-like server-side parsing) to extract file links
- Filters out non-video files and directories
- Calculates and formats file sizes

### 2. **TMDB Integration** 
- Connects to The Movie Database API
- Fetches movie metadata (posters, descriptions, genres)
- Constructs proper movie directory names
- Provides rich movie information

### 3. **HTTP Client**
- Handles all web requests with proper error handling
- Supports timeout and retry logic
- Manages URL encoding and normalization

### 4. **Express.js Server**
- RESTful API endpoints
- CORS support for web applications
- JSON request/response handling
- Request logging and error handling

## 🚨 Troubleshooting

### Common Issues:

**"Cannot find module" errors:**
```bash
# Solution: Install dependencies
npm install
```

**"TMDB API key invalid" errors:**
- Check your API key is correct
- Make sure it's properly set in environment variable or code
- Verify your TMDB account is activated

**"Port 3000 already in use" errors:**
```bash
# Solution: Use a different port
PORT=8080 npm start
```

**"Network timeout" errors:**
- Check your internet connection
- The movie server might be temporarily down
- Try again in a few minutes

### Getting Help:
1. Check the console output for detailed error messages
2. Test the `/health` endpoint to verify basic functionality
3. Try the TMDB endpoints first (they're more reliable)
4. Make sure your API key is working with a simple search

## 🚀 Advanced Usage

### Running in Production

**Using PM2 (Process Manager):**
```bash
# Install PM2 globally
npm install -g pm2

# Start with PM2
pm2 start src/index.js --name "movie-api"

# Check status
pm2 status

# View logs
pm2 logs movie-api
```

**Using Docker:**
```dockerfile
# Create a Dockerfile
FROM node:18-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["npm", "start"]
```

### Environment Variables
```bash
# Server configuration
PORT=3000

# TMDB configuration
TMDB_API_KEY=your_api_key_here

# Movie server configuration (if different)
MOVIE_BASE_URL=https://a.111477.xyz
```

## 🎯 Use Cases

This API is perfect for:
- **Movie streaming applications**
- **Media server interfaces**
- **Content discovery platforms**
- **Personal movie libraries**
- **Educational projects**
- **Portfolio demonstrations**

## 📱 Building a Frontend

You can use this API with any frontend framework:

**React Example:**
```javascript
async function searchMovie(query) {
  const response = await fetch(`http://localhost:3000/api/tmdb/search/${query}`);
  const data = await response.json();
  return data;
}
```

**Vue.js Example:**
```javascript
methods: {
  async getMovieDetails(tmdbId) {
    const response = await this.$http.get(`/api/tmdb/${tmdbId}`);
    this.movie = response.data;
  }
}
```

**Plain JavaScript Example:**
```javascript
fetch('http://localhost:3000/api/tmdb/1949')
  .then(response => response.json())
  .then(data => {
    console.log('Movie:', data);
    // Display movie information
  });
```

## 🔐 Security Considerations

- **API Key Protection**: Never expose your TMDB API key in client-side code
- **Rate Limiting**: Consider implementing rate limiting for production use
- **CORS**: Configure CORS settings for your specific frontend domains
- **Input Validation**: The API includes basic input validation
- **Error Handling**: Comprehensive error handling prevents crashes

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

---

**Made by Ayman with love ❤️ - 100% Open Source**

*Happy coding! 🚀*