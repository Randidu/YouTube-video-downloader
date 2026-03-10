# InfinityGrab - Universal Video Downloader

InfinityGrab is a powerful and versatile web application that allows users to download videos and audio from various social media platforms, including YouTube, Facebook, Instagram, TikTok, Twitter (X), and Vimeo. Built with a robust Python backend (FastAPI) and a modern, responsive frontend.

## 🚀 Features

*   **Multi-Platform Support**: Download content from YouTube, Facebook, Instagram, TikTok, X (Twitter), Vimeo, and more.
*   **High Quality**: Support for HD downloads (up to 4K where available).
*   **Audio Extraction**: Option to convert and download videos as high-quality MP3 audio files.
*   **Smart Quality Selection**: Choose your preferred resolution (1080p, 720p, 480p, etc.).
*   **Fast processing**: Utilizes powerful libraries like `yt-dlp` and `pytubefix` for reliable and fast downloads.
*   **Modern UI**: A clean, responsive interface built with Bootstrap 5 and custom CSS.

## 🛠️ Technology Stack

*   **Backend**: Python 3, FastAPI, Uvicorn
*   **Core Engines**: `yt-dlp`, `pytubefix`, `FFmpeg`
*   **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
*   **Deployment**: Ready for deployment on platforms like Render or Heroku (includes `Procfile` and `render.yaml`).

## 📋 Prerequisites

Before running the application, ensure you have the following installed:

1.  **Python 3.8+**: [Download Python](https://www.python.org/downloads/)
2.  **FFmpeg**: Required for media processing (merging video/audio, format conversion).
    *   **Windows**: [Download FFmpeg](https://ffmpeg.org/download.html), extract it, and add the `bin` folder to your system PATH.
    *   **Linux**: `sudo apt install ffmpeg`
    *   **macOS**: `brew install ffmpeg`

## ⚙️ Installation & Setup

1.  **Clone the repository** (or download the source code):
    ```bash
    git clone <repository-url>
    cd YouTube-video-downloader
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    
    # Windows
    venv\Scripts\activate
    
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Running the Application

1.  **Start the server**:
    ```bash
    python main.py
    ```
    *   The application will automatically attempt to open your default browser to `http://localhost:8000`.
    *   Alternatively, you can run: `uvicorn main:app --reload` for development.

2.  **Use the Downloader**:
    *   Paste a video URL (e.g., from YouTube) into the input field.
    *   Click **Fetch Video**.
    *   Select your desired **Quality** and **Format** (Video or Audio).
    *   Click **Download Video**.

## 📝 Configuration

*   **Desktop Mode**: By default, downloads are saved to your system's `Downloads` folder.
*   **Server Mode**: If deployed (detected via `RENDER` or `dyro` env vars), downloads are processed in a temporary directory and served explicitly to the client, then cleaned up.

## ⚠️ Disclaimer

This project is for **educational purposes only**. Please respect the copyright laws and terms of service of the respective platforms you download content from. The developers of this tool are not responsible for any misuse.

# InfinityGrab - Universal Video Downloader

InfinityGrab is a powerful and versatile web application that allows users to download videos and audio from various social media platforms, including YouTube, Facebook, Instagram, TikTok, Twitter (X), and Vimeo. Built with a robust Python backend (FastAPI) and a modern, responsive frontend.

## 🚀 Features

*   **Multi-Platform Support**: Download content from YouTube, Facebook, Instagram, TikTok, X (Twitter), Vimeo, and more.
*   **High Quality**: Support for HD downloads (up to 4K where available).
*   **Audio Extraction**: Option to convert and download videos as high-quality MP3 audio files.
*   **Smart Quality Selection**: Choose your preferred resolution (1080p, 720p, 480p, etc.).
*   **Fast processing**: Utilizes powerful libraries like `yt-dlp` and `pytubefix` for reliable and fast downloads.
*   **Modern UI**: A clean, responsive interface built with Bootstrap 5 and custom CSS.

## 🛠️ Technology Stack

*   **Backend**: Python 3, FastAPI, Uvicorn
*   **Core Engines**: `yt-dlp`, `pytubefix`, `FFmpeg`
*   **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
*   **Deployment**: Ready for deployment on platforms like Render or Heroku (includes `Procfile` and `render.yaml`).

## 📋 Prerequisites

Before running the application, ensure you have the following installed:

1.  **Python 3.8+**: [Download Python](https://www.python.org/downloads/)
2.  **FFmpeg**: Required for media processing (merging video/audio, format conversion).
    *   **Windows**: [Download FFmpeg](https://ffmpeg.org/download.html), extract it, and add the `bin` folder to your system PATH.
    *   **Linux**: `sudo apt install ffmpeg`
    *   **macOS**: `brew install ffmpeg`

## ⚙️ Installation & Setup

1.  **Clone the repository** (or download the source code):
    ```bash
    git clone <repository-url>
    cd YouTube-video-downloader
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    
    # Windows
    venv\Scripts\activate
    
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Running the Application

1.  **Start the server**:
    ```bash
    python main.py
    ```
    *   The application will automatically attempt to open your default browser to `http://localhost:8000`.
    *   Alternatively, you can run: `uvicorn main:app --reload` for development.

2.  **Use the Downloader**:
    *   Paste a video URL (e.g., from YouTube) into the input field.
    *   Click **Fetch Video**.
    *   Select your desired **Quality** and **Format** (Video or Audio).
    *   Click **Download Video**.

## 📝 Configuration

*   **Desktop Mode**: By default, downloads are saved to your system's `Downloads` folder.
*   **Server Mode**: If deployed (detected via `RENDER` or `dyro` env vars), downloads are processed in a temporary directory and served explicitly to the client, then cleaned up.

## ⚠️ Disclaimer

This project is for **educational purposes only**. Please respect the copyright laws and terms of service of the respective platforms you download content from. The developers of this tool are not responsible for any misuse.

# InfinityGrab - Universal Video Downloader

InfinityGrab is a powerful and versatile web application that allows users to download videos and audio from various social media platforms, including YouTube, Facebook, Instagram, TikTok, Twitter (X), and Vimeo. Built with a robust Python backend (FastAPI) and a modern, responsive frontend.

## 🚀 Features

*   **Multi-Platform Support**: Download content from YouTube, Facebook, Instagram, TikTok, X (Twitter), Vimeo, and more.
*   **High Quality**: Support for HD downloads (up to 4K where available).
*   **Audio Extraction**: Option to convert and download videos as high-quality MP3 audio files.
*   **Smart Quality Selection**: Choose your preferred resolution (1080p, 720p, 480p, etc.).
*   **Fast processing**: Utilizes powerful libraries like `yt-dlp` and `pytubefix` for reliable and fast downloads.
*   **Modern UI**: A clean, responsive interface built with Bootstrap 5 and custom CSS.

## 🛠️ Technology Stack

*   **Backend**: Python 3, FastAPI, Uvicorn
*   **Core Engines**: `yt-dlp`, `pytubefix`, `FFmpeg`
*   **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
*   **Deployment**: Ready for deployment on platforms like Render or Heroku (includes `Procfile` and `render.yaml`).

## 📋 Prerequisites

Before running the application, ensure you have the following installed:

1.  **Python 3.8+**: [Download Python](https://www.python.org/downloads/)
2.  **FFmpeg**: Required for media processing (merging video/audio, format conversion).
    *   **Windows**: [Download FFmpeg](https://ffmpeg.org/download.html), extract it, and add the `bin` folder to your system PATH.
    *   **Linux**: `sudo apt install ffmpeg`
    *   **macOS**: `brew install ffmpeg`

## ⚙️ Installation & Setup

1.  **Clone the repository** (or download the source code):
    ```bash
    git clone <repository-url>
    cd YouTube-video-downloader
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    
    # Windows
    venv\Scripts\activate
    
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Running the Application

1.  **Start the server**:
    ```bash
    python main.py
    ```
    *   The application will automatically attempt to open your default browser to `http://localhost:8000`.
    *   Alternatively, you can run: `uvicorn main:app --reload` for development.

2.  **Use the Downloader**:
    *   Paste a video URL (e.g., from YouTube) into the input field.
    *   Click **Fetch Video**.
    *   Select your desired **Quality** and **Format** (Video or Audio).
    *   Click **Download Video**.

## 📝 Configuration

*   **Desktop Mode**: By default, downloads are saved to your system's `Downloads` folder.
*   **Server Mode**: If deployed (detected via `RENDER` or `dyro` env vars), downloads are processed in a temporary directory and served explicitly to the client, then cleaned up.

## ⚠️ Disclaimer

This project is for **educational purposes only**. Please respect the copyright laws and terms of service of the respective platforms you download content from. The developers of this tool are not responsible for any misuse.

# InfinityGrab - Universal Video Downloader

InfinityGrab is a powerful and versatile web application that allows users to download videos and audio from various social media platforms, including YouTube, Facebook, Instagram, TikTok, Twitter (X), and Vimeo. Built with a robust Python backend (FastAPI) and a modern, responsive frontend.

## 🚀 Features

*   **Multi-Platform Support**: Download content from YouTube, Facebook, Instagram, TikTok, X (Twitter), Vimeo, and more.
*   **High Quality**: Support for HD downloads (up to 4K where available).
*   **Audio Extraction**: Option to convert and download videos as high-quality MP3 audio files.
*   **Smart Quality Selection**: Choose your preferred resolution (1080p, 720p, 480p, etc.).
*   **Fast processing**: Utilizes powerful libraries like `yt-dlp` and `pytubefix` for reliable and fast downloads.
*   **Modern UI**: A clean, responsive interface built with Bootstrap 5 and custom CSS.

## 🛠️ Technology Stack

*   **Backend**: Python 3, FastAPI, Uvicorn
*   **Core Engines**: `yt-dlp`, `pytubefix`, `FFmpeg`
*   **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
*   **Deployment**: Ready for deployment on platforms like Render or Heroku (includes `Procfile` and `render.yaml`).

## 📋 Prerequisites

Before running the application, ensure you have the following installed:

1.  **Python 3.8+**: [Download Python](https://www.python.org/downloads/)
2.  **FFmpeg**: Required for media processing (merging video/audio, format conversion).
    *   **Windows**: [Download FFmpeg](https://ffmpeg.org/download.html), extract it, and add the `bin` folder to your system PATH.
    *   **Linux**: `sudo apt install ffmpeg`
    *   **macOS**: `brew install ffmpeg`

## ⚙️ Installation & Setup

1.  **Clone the repository** (or download the source code):
    ```bash
    git clone <repository-url>
    cd YouTube-video-downloader
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    
    # Windows
    venv\Scripts\activate
    
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Running the Application

1.  **Start the server**:
    ```bash
    python main.py
    ```
    *   The application will automatically attempt to open your default browser to `http://localhost:8000`.
    *   Alternatively, you can run: `uvicorn main:app --reload` for development.

2.  **Use the Downloader**:
    *   Paste a video URL (e.g., from YouTube) into the input field.
    *   Click **Fetch Video**.
    *   Select your desired **Quality** and **Format** (Video or Audio).
    *   Click **Download Video**.

## 📝 Configuration

*   **Desktop Mode**: By default, downloads are saved to your system's `Downloads` folder.
*   **Server Mode**: If deployed (detected via `RENDER` or `dyro` env vars), downloads are processed in a temporary directory and served explicitly to the client, then cleaned up.

## ⚠️ Disclaimer

This project is for **educational purposes only**. Please respect the copyright laws and terms of service of the respective platforms you download content from. The developers of this tool are not responsible for any misuse.

# InfinityGrab - Universal Video Downloader

InfinityGrab is a powerful and versatile web application that allows users to download videos and audio from various social media platforms, including YouTube, Facebook, Instagram, TikTok, Twitter (X), and Vimeo. Built with a robust Python backend (FastAPI) and a modern, responsive frontend.

## 🚀 Features

*   **Multi-Platform Support**: Download content from YouTube, Facebook, Instagram, TikTok, X (Twitter), Vimeo, and more.
*   **High Quality**: Support for HD downloads (up to 4K where available).
*   **Audio Extraction**: Option to convert and download videos as high-quality MP3 audio files.
*   **Smart Quality Selection**: Choose your preferred resolution (1080p, 720p, 480p, etc.).
*   **Fast processing**: Utilizes powerful libraries like `yt-dlp` and `pytubefix` for reliable and fast downloads.
*   **Modern UI**: A clean, responsive interface built with Bootstrap 5 and custom CSS.

## 🛠️ Technology Stack

*   **Backend**: Python 3, FastAPI, Uvicorn
*   **Core Engines**: `yt-dlp`, `pytubefix`, `FFmpeg`
*   **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
*   **Deployment**: Ready for deployment on platforms like Render or Heroku (includes `Procfile` and `render.yaml`).

## 📋 Prerequisites

Before running the application, ensure you have the following installed:

1.  **Python 3.8+**: [Download Python](https://www.python.org/downloads/)
2.  **FFmpeg**: Required for media processing (merging video/audio, format conversion).
    *   **Windows**: [Download FFmpeg](https://ffmpeg.org/download.html), extract it, and add the `bin` folder to your system PATH.
    *   **Linux**: `sudo apt install ffmpeg`
    *   **macOS**: `brew install ffmpeg`

## ⚙️ Installation & Setup

1.  **Clone the repository** (or download the source code):
    ```bash
    git clone <repository-url>
    cd YouTube-video-downloader
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    
    # Windows
    venv\Scripts\activate
    
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Running the Application

1.  **Start the server**:
    ```bash
    python main.py
    ```
    *   The application will automatically attempt to open your default browser to `http://localhost:8000`.
    *   Alternatively, you can run: `uvicorn main:app --reload` for development.

2.  **Use the Downloader**:
    *   Paste a video URL (e.g., from YouTube) into the input field.
    *   Click **Fetch Video**.
    *   Select your desired **Quality** and **Format** (Video or Audio).
    *   Click **Download Video**.

## 📝 Configuration

*   **Desktop Mode**: By default, downloads are saved to your system's `Downloads` folder.
*   **Server Mode**: If deployed (detected via `RENDER` or `dyro` env vars), downloads are processed in a temporary directory and served explicitly to the client, then cleaned up.

## ⚠️ Disclaimer

This project is for **educational purposes only**. Please respect the copyright laws and terms of service of the respective platforms you download content from. The developers of this tool are not responsible for any misuse.

# InfinityGrab - Universal Video Downloader

InfinityGrab is a powerful and versatile web application that allows users to download videos and audio from various social media platforms, including YouTube, Facebook, Instagram, TikTok, Twitter (X), and Vimeo. Built with a robust Python backend (FastAPI) and a modern, responsive frontend.

## 🚀 Features

*   **Multi-Platform Support**: Download content from YouTube, Facebook, Instagram, TikTok, X (Twitter), Vimeo, and more.
*   **High Quality**: Support for HD downloads (up to 4K where available).
*   **Audio Extraction**: Option to convert and download videos as high-quality MP3 audio files.
*   **Smart Quality Selection**: Choose your preferred resolution (1080p, 720p, 480p, etc.).
*   **Fast processing**: Utilizes powerful libraries like `yt-dlp` and `pytubefix` for reliable and fast downloads.
*   **Modern UI**: A clean, responsive interface built with Bootstrap 5 and custom CSS.

## 🛠️ Technology Stack

*   **Backend**: Python 3, FastAPI, Uvicorn
*   **Core Engines**: `yt-dlp`, `pytubefix`, `FFmpeg`
*   **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
*   **Deployment**: Ready for deployment on platforms like Render or Heroku (includes `Procfile` and `render.yaml`).

## 📋 Prerequisites

Before running the application, ensure you have the following installed:

1.  **Python 3.8+**: [Download Python](https://www.python.org/downloads/)
2.  **FFmpeg**: Required for media processing (merging video/audio, format conversion).
    *   **Windows**: [Download FFmpeg](https://ffmpeg.org/download.html), extract it, and add the `bin` folder to your system PATH.
    *   **Linux**: `sudo apt install ffmpeg`
    *   **macOS**: `brew install ffmpeg`

## ⚙️ Installation & Setup

1.  **Clone the repository** (or download the source code):
    ```bash
    git clone <repository-url>
    cd YouTube-video-downloader
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    
    # Windows
    venv\Scripts\activate
    
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Running the Application

1.  **Start the server**:
    ```bash
    python main.py
    ```
    *   The application will automatically attempt to open your default browser to `http://localhost:8000`.
    *   Alternatively, you can run: `uvicorn main:app --reload` for development.

2.  **Use the Downloader**:
    *   Paste a video URL (e.g., from YouTube) into the input field.
    *   Click **Fetch Video**.
    *   Select your desired **Quality** and **Format** (Video or Audio).
    *   Click **Download Video**.

## 📝 Configuration

*   **Desktop Mode**: By default, downloads are saved to your system's `Downloads` folder.
*   **Server Mode**: If deployed (detected via `RENDER` or `dyro` env vars), downloads are processed in a temporary directory and served explicitly to the client, then cleaned up.

## ⚠️ Disclaimer

This project is for **educational purposes only**. Please respect the copyright laws and terms of service of the respective platforms you download content from. The developers of this tool are not responsible for any misuse.

# InfinityGrab - Universal Video Downloader

InfinityGrab is a powerful and versatile web application that allows users to download videos and audio from various social media platforms, including YouTube, Facebook, Instagram, TikTok, Twitter (X), and Vimeo. Built with a robust Python backend (FastAPI) and a modern, responsive frontend.

## 🚀 Features

*   **Multi-Platform Support**: Download content from YouTube, Facebook, Instagram, TikTok, X (Twitter), Vimeo, and more.
*   **High Quality**: Support for HD downloads (up to 4K where available).
*   **Audio Extraction**: Option to convert and download videos as high-quality MP3 audio files.
*   **Smart Quality Selection**: Choose your preferred resolution (1080p, 720p, 480p, etc.).
*   **Fast processing**: Utilizes powerful libraries like `yt-dlp` and `pytubefix` for reliable and fast downloads.
*   **Modern UI**: A clean, responsive interface built with Bootstrap 5 and custom CSS.

## 🛠️ Technology Stack

*   **Backend**: Python 3, FastAPI, Uvicorn
*   **Core Engines**: `yt-dlp`, `pytubefix`, `FFmpeg`
*   **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
*   **Deployment**: Ready for deployment on platforms like Render or Heroku (includes `Procfile` and `render.yaml`).

## 📋 Prerequisites

Before running the application, ensure you have the following installed:

1.  **Python 3.8+**: [Download Python](https://www.python.org/downloads/)
2.  **FFmpeg**: Required for media processing (merging video/audio, format conversion).
    *   **Windows**: [Download FFmpeg](https://ffmpeg.org/download.html), extract it, and add the `bin` folder to your system PATH.
    *   **Linux**: `sudo apt install ffmpeg`
    *   **macOS**: `brew install ffmpeg`

## ⚙️ Installation & Setup

1.  **Clone the repository** (or download the source code):
    ```bash
    git clone <repository-url>
    cd YouTube-video-downloader
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    
    # Windows
    venv\Scripts\activate
    
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Running the Application

1.  **Start the server**:
    ```bash
    python main.py
    ```
    *   The application will automatically attempt to open your default browser to `http://localhost:8000`.
    *   Alternatively, you can run: `uvicorn main:app --reload` for development.

2.  **Use the Downloader**:
    *   Paste a video URL (e.g., from YouTube) into the input field.
    *   Click **Fetch Video**.
    *   Select your desired **Quality** and **Format** (Video or Audio).
    *   Click **Download Video**.

## 📝 Configuration

*   **Desktop Mode**: By default, downloads are saved to your system's `Downloads` folder.
*   **Server Mode**: If deployed (detected via `RENDER` or `dyro` env vars), downloads are processed in a temporary directory and served explicitly to the client, then cleaned up.

## ⚠️ Disclaimer

This project is for **educational purposes only**. Please respect the copyright laws and terms of service of the respective platforms you download content from. The developers of this tool are not responsible for any misuse.

# InfinityGrab - Universal Video Downloader

InfinityGrab is a powerful and versatile web application that allows users to download videos and audio from various social media platforms, including YouTube, Facebook, Instagram, TikTok, Twitter (X), and Vimeo. Built with a robust Python backend (FastAPI) and a modern, responsive frontend.

## 🚀 Features

*   **Multi-Platform Support**: Download content from YouTube, Facebook, Instagram, TikTok, X (Twitter), Vimeo, and more.
*   **High Quality**: Support for HD downloads (up to 4K where available).
*   **Audio Extraction**: Option to convert and download videos as high-quality MP3 audio files.
*   **Smart Quality Selection**: Choose your preferred resolution (1080p, 720p, 480p, etc.).
*   **Fast processing**: Utilizes powerful libraries like `yt-dlp` and `pytubefix` for reliable and fast downloads.
*   **Modern UI**: A clean, responsive interface built with Bootstrap 5 and custom CSS.

## 🛠️ Technology Stack

*   **Backend**: Python 3, FastAPI, Uvicorn
*   **Core Engines**: `yt-dlp`, `pytubefix`, `FFmpeg`
*   **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
*   **Deployment**: Ready for deployment on platforms like Render or Heroku (includes `Procfile` and `render.yaml`).

## 📋 Prerequisites

Before running the application, ensure you have the following installed:

1.  **Python 3.8+**: [Download Python](https://www.python.org/downloads/)
2.  **FFmpeg**: Required for media processing (merging video/audio, format conversion).
    *   **Windows**: [Download FFmpeg](https://ffmpeg.org/download.html), extract it, and add the `bin` folder to your system PATH.
    *   **Linux**: `sudo apt install ffmpeg`
    *   **macOS**: `brew install ffmpeg`

## ⚙️ Installation & Setup

1.  **Clone the repository** (or download the source code):
    ```bash
    git clone <repository-url>
    cd YouTube-video-downloader
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    
    # Windows
    venv\Scripts\activate
    
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Running the Application

1.  **Start the server**:
    ```bash
    python main.py
    ```
    *   The application will automatically attempt to open your default browser to `http://localhost:8000`.
    *   Alternatively, you can run: `uvicorn main:app --reload` for development.

2.  **Use the Downloader**:
    *   Paste a video URL (e.g., from YouTube) into the input field.
    *   Click **Fetch Video**.
    *   Select your desired **Quality** and **Format** (Video or Audio).
    *   Click **Download Video**.

## 📝 Configuration

*   **Desktop Mode**: By default, downloads are saved to your system's `Downloads` folder.
*   **Server Mode**: If deployed (detected via `RENDER` or `dyro` env vars), downloads are processed in a temporary directory and served explicitly to the client, then cleaned up.

## ⚠️ Disclaimer

This project is for **educational purposes only**. Please respect the copyright laws and terms of service of the respective platforms you download content from. The developers of this tool are not responsible for any misuse.

# InfinityGrab - Universal Video Downloader

InfinityGrab is a powerful and versatile web application that allows users to download videos and audio from various social media platforms, including YouTube, Facebook, Instagram, TikTok, Twitter (X), and Vimeo. Built with a robust Python backend (FastAPI) and a modern, responsive frontend.

## 🚀 Features

*   **Multi-Platform Support**: Download content from YouTube, Facebook, Instagram, TikTok, X (Twitter), Vimeo, and more.
*   **High Quality**: Support for HD downloads (up to 4K where available).
*   **Audio Extraction**: Option to convert and download videos as high-quality MP3 audio files.
*   **Smart Quality Selection**: Choose your preferred resolution (1080p, 720p, 480p, etc.).
*   **Fast processing**: Utilizes powerful libraries like `yt-dlp` and `pytubefix` for reliable and fast downloads.
*   **Modern UI**: A clean, responsive interface built with Bootstrap 5 and custom CSS.

## 🛠️ Technology Stack

*   **Backend**: Python 3, FastAPI, Uvicorn
*   **Core Engines**: `yt-dlp`, `pytubefix`, `FFmpeg`
*   **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
*   **Deployment**: Ready for deployment on platforms like Render or Heroku (includes `Procfile` and `render.yaml`).

## 📋 Prerequisites

Before running the application, ensure you have the following installed:

1.  **Python 3.8+**: [Download Python](https://www.python.org/downloads/)
2.  **FFmpeg**: Required for media processing (merging video/audio, format conversion).
    *   **Windows**: [Download FFmpeg](https://ffmpeg.org/download.html), extract it, and add the `bin` folder to your system PATH.
    *   **Linux**: `sudo apt install ffmpeg`
    *   **macOS**: `brew install ffmpeg`

## ⚙️ Installation & Setup

1.  **Clone the repository** (or download the source code):
    ```bash
    git clone <repository-url>
    cd YouTube-video-downloader
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    
    # Windows
    venv\Scripts\activate
    
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Running the Application

1.  **Start the server**:
    ```bash
    python main.py
    ```
    *   The application will automatically attempt to open your default browser to `http://localhost:8000`.
    *   Alternatively, you can run: `uvicorn main:app --reload` for development.

2.  **Use the Downloader**:
    *   Paste a video URL (e.g., from YouTube) into the input field.
    *   Click **Fetch Video**.
    *   Select your desired **Quality** and **Format** (Video or Audio).
    *   Click **Download Video**.

## 📝 Configuration

*   **Desktop Mode**: By default, downloads are saved to your system's `Downloads` folder.
*   **Server Mode**: If deployed (detected via `RENDER` or `dyro` env vars), downloads are processed in a temporary directory and served explicitly to the client, then cleaned up.

## ⚠️ Disclaimer

This project is for **educational purposes only**. Please respect the copyright laws and terms of service of the respective platforms you download content from. The developers of this tool are not responsible for any misuse.

# InfinityGrab - Universal Video Downloader

InfinityGrab is a powerful and versatile web application that allows users to download videos and audio from various social media platforms, including YouTube, Facebook, Instagram, TikTok, Twitter (X), and Vimeo. Built with a robust Python backend (FastAPI) and a modern, responsive frontend.

## 🚀 Features

*   **Multi-Platform Support**: Download content from YouTube, Facebook, Instagram, TikTok, X (Twitter), Vimeo, and more.
*   **High Quality**: Support for HD downloads (up to 4K where available).
*   **Audio Extraction**: Option to convert and download videos as high-quality MP3 audio files.
*   **Smart Quality Selection**: Choose your preferred resolution (1080p, 720p, 480p, etc.).
*   **Fast processing**: Utilizes powerful libraries like `yt-dlp` and `pytubefix` for reliable and fast downloads.
*   **Modern UI**: A clean, responsive interface built with Bootstrap 5 and custom CSS.

## 🛠️ Technology Stack

*   **Backend**: Python 3, FastAPI, Uvicorn
*   **Core Engines**: `yt-dlp`, `pytubefix`, `FFmpeg`
*   **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
*   **Deployment**: Ready for deployment on platforms like Render or Heroku (includes `Procfile` and `render.yaml`).

## 📋 Prerequisites

Before running the application, ensure you have the following installed:

1.  **Python 3.8+**: [Download Python](https://www.python.org/downloads/)
2.  **FFmpeg**: Required for media processing (merging video/audio, format conversion).
    *   **Windows**: [Download FFmpeg](https://ffmpeg.org/download.html), extract it, and add the `bin` folder to your system PATH.
    *   **Linux**: `sudo apt install ffmpeg`
    *   **macOS**: `brew install ffmpeg`

## ⚙️ Installation & Setup

1.  **Clone the repository** (or download the source code):
    ```bash
    git clone <repository-url>
    cd YouTube-video-downloader
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    
    # Windows
    venv\Scripts\activate
    
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Running the Application

1.  **Start the server**:
    ```bash
    python main.py
    ```
    *   The application will automatically attempt to open your default browser to `http://localhost:8000`.
    *   Alternatively, you can run: `uvicorn main:app --reload` for development.

2.  **Use the Downloader**:
    *   Paste a video URL (e.g., from YouTube) into the input field.
    *   Click **Fetch Video**.
    *   Select your desired **Quality** and **Format** (Video or Audio).
    *   Click **Download Video**.

## 📝 Configuration

*   **Desktop Mode**: By default, downloads are saved to your system's `Downloads` folder.
*   **Server Mode**: If deployed (detected via `RENDER` or `dyro` env vars), downloads are processed in a temporary directory and served explicitly to the client, then cleaned up.

## ⚠️ Disclaimer

This project is for **educational purposes only**. Please respect the copyright laws and terms of service of the respective platforms you download content from. The developers of this tool are not responsible for any misuse.

# InfinityGrab - Universal Video Downloader

InfinityGrab is a powerful and versatile web application that allows users to download videos and audio from various social media platforms, including YouTube, Facebook, Instagram, TikTok, Twitter (X), and Vimeo. Built with a robust Python backend (FastAPI) and a modern, responsive frontend.

## 🚀 Features

*   **Multi-Platform Support**: Download content from YouTube, Facebook, Instagram, TikTok, X (Twitter), Vimeo, and more.
*   **High Quality**: Support for HD downloads (up to 4K where available).
*   **Audio Extraction**: Option to convert and download videos as high-quality MP3 audio files.
*   **Smart Quality Selection**: Choose your preferred resolution (1080p, 720p, 480p, etc.).
*   **Fast processing**: Utilizes powerful libraries like `yt-dlp` and `pytubefix` for reliable and fast downloads.
*   **Modern UI**: A clean, responsive interface built with Bootstrap 5 and custom CSS.

## 🛠️ Technology Stack

*   **Backend**: Python 3, FastAPI, Uvicorn
*   **Core Engines**: `yt-dlp`, `pytubefix`, `FFmpeg`
*   **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
*   **Deployment**: Ready for deployment on platforms like Render or Heroku (includes `Procfile` and `render.yaml`).

## 📋 Prerequisites

Before running the application, ensure you have the following installed:

1.  **Python 3.8+**: [Download Python](https://www.python.org/downloads/)
2.  **FFmpeg**: Required for media processing (merging video/audio, format conversion).
    *   **Windows**: [Download FFmpeg](https://ffmpeg.org/download.html), extract it, and add the `bin` folder to your system PATH.
    *   **Linux**: `sudo apt install ffmpeg`
    *   **macOS**: `brew install ffmpeg`

## ⚙️ Installation & Setup

1.  **Clone the repository** (or download the source code):
    ```bash
    git clone <repository-url>
    cd YouTube-video-downloader
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    
    # Windows
    venv\Scripts\activate
    
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Running the Application

1.  **Start the server**:
    ```bash
    python main.py
    ```
    *   The application will automatically attempt to open your default browser to `http://localhost:8000`.
    *   Alternatively, you can run: `uvicorn main:app --reload` for development.

2.  **Use the Downloader**:
    *   Paste a video URL (e.g., from YouTube) into the input field.
    *   Click **Fetch Video**.
    *   Select your desired **Quality** and **Format** (Video or Audio).
    *   Click **Download Video**.

## 📝 Configuration

*   **Desktop Mode**: By default, downloads are saved to your system's `Downloads` folder.
*   **Server Mode**: If deployed (detected via `RENDER` or `dyro` env vars), downloads are processed in a temporary directory and served explicitly to the client, then cleaned up.

## ⚠️ Disclaimer

This project is for **educational purposes only**. Please respect the copyright laws and terms of service of the respective platforms you download content from. The developers of this tool are not responsible for any misuse.

# InfinityGrab - Universal Video Downloader

InfinityGrab is a powerful and versatile web application that allows users to download videos and audio from various social media platforms, including YouTube, Facebook, Instagram, TikTok, Twitter (X), and Vimeo. Built with a robust Python backend (FastAPI) and a modern, responsive frontend.

## 🚀 Features

*   **Multi-Platform Support**: Download content from YouTube, Facebook, Instagram, TikTok, X (Twitter), Vimeo, and more.
*   **High Quality**: Support for HD downloads (up to 4K where available).
*   **Audio Extraction**: Option to convert and download videos as high-quality MP3 audio files.
*   **Smart Quality Selection**: Choose your preferred resolution (1080p, 720p, 480p, etc.).
*   **Fast processing**: Utilizes powerful libraries like `yt-dlp` and `pytubefix` for reliable and fast downloads.
*   **Modern UI**: A clean, responsive interface built with Bootstrap 5 and custom CSS.

## 🛠️ Technology Stack

*   **Backend**: Python 3, FastAPI, Uvicorn
*   **Core Engines**: `yt-dlp`, `pytubefix`, `FFmpeg`
*   **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
*   **Deployment**: Ready for deployment on platforms like Render or Heroku (includes `Procfile` and `render.yaml`).

## 📋 Prerequisites

Before running the application, ensure you have the following installed:

1.  **Python 3.8+**: [Download Python](https://www.python.org/downloads/)
2.  **FFmpeg**: Required for media processing (merging video/audio, format conversion).
    *   **Windows**: [Download FFmpeg](https://ffmpeg.org/download.html), extract it, and add the `bin` folder to your system PATH.
    *   **Linux**: `sudo apt install ffmpeg`
    *   **macOS**: `brew install ffmpeg`

## ⚙️ Installation & Setup

1.  **Clone the repository** (or download the source code):
    ```bash
    git clone <repository-url>
    cd YouTube-video-downloader
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    
    # Windows
    venv\Scripts\activate
    
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Running the Application

1.  **Start the server**:
    ```bash
    python main.py
    ```
    *   The application will automatically attempt to open your default browser to `http://localhost:8000`.
    *   Alternatively, you can run: `uvicorn main:app --reload` for development.

2.  **Use the Downloader**:
    *   Paste a video URL (e.g., from YouTube) into the input field.
    *   Click **Fetch Video**.
    *   Select your desired **Quality** and **Format** (Video or Audio).
    *   Click **Download Video**.

## 📝 Configuration

*   **Desktop Mode**: By default, downloads are saved to your system's `Downloads` folder.
*   **Server Mode**: If deployed (detected via `RENDER` or `dyro` env vars), downloads are processed in a temporary directory and served explicitly to the client, then cleaned up.

## ⚠️ Disclaimer

This project is for **educational purposes only**. Please respect the copyright laws and terms of service of the respective platforms you download content from. The developers of this tool are not responsible for any misuse.

# InfinityGrab - Universal Video Downloader

InfinityGrab is a powerful and versatile web application that allows users to download videos and audio from various social media platforms, including YouTube, Facebook, Instagram, TikTok, Twitter (X), and Vimeo. Built with a robust Python backend (FastAPI) and a modern, responsive frontend.

## 🚀 Features

*   **Multi-Platform Support**: Download content from YouTube, Facebook, Instagram, TikTok, X (Twitter), Vimeo, and more.
*   **High Quality**: Support for HD downloads (up to 4K where available).
*   **Audio Extraction**: Option to convert and download videos as high-quality MP3 audio files.
*   **Smart Quality Selection**: Choose your preferred resolution (1080p, 720p, 480p, etc.).
*   **Fast processing**: Utilizes powerful libraries like `yt-dlp` and `pytubefix` for reliable and fast downloads.
*   **Modern UI**: A clean, responsive interface built with Bootstrap 5 and custom CSS.

## 🛠️ Technology Stack

*   **Backend**: Python 3, FastAPI, Uvicorn
*   **Core Engines**: `yt-dlp`, `pytubefix`, `FFmpeg`
*   **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
*   **Deployment**: Ready for deployment on platforms like Render or Heroku (includes `Procfile` and `render.yaml`).

## 📋 Prerequisites

Before running the application, ensure you have the following installed:

1.  **Python 3.8+**: [Download Python](https://www.python.org/downloads/)
2.  **FFmpeg**: Required for media processing (merging video/audio, format conversion).
    *   **Windows**: [Download FFmpeg](https://ffmpeg.org/download.html), extract it, and add the `bin` folder to your system PATH.
    *   **Linux**: `sudo apt install ffmpeg`
    *   **macOS**: `brew install ffmpeg`

## ⚙️ Installation & Setup

1.  **Clone the repository** (or download the source code):
    ```bash
    git clone <repository-url>
    cd YouTube-video-downloader
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    
    # Windows
    venv\Scripts\activate
    
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Running the Application

1.  **Start the server**:
    ```bash
    python main.py
    ```
    *   The application will automatically attempt to open your default browser to `http://localhost:8000`.
    *   Alternatively, you can run: `uvicorn main:app --reload` for development.

2.  **Use the Downloader**:
    *   Paste a video URL (e.g., from YouTube) into the input field.
    *   Click **Fetch Video**.
    *   Select your desired **Quality** and **Format** (Video or Audio).
    *   Click **Download Video**.

## 📝 Configuration

*   **Desktop Mode**: By default, downloads are saved to your system's `Downloads` folder.
*   **Server Mode**: If deployed (detected via `RENDER` or `dyro` env vars), downloads are processed in a temporary directory and served explicitly to the client, then cleaned up.

## ⚠️ Disclaimer

This project is for **educational purposes only**. Please respect the copyright laws and terms of service of the respective platforms you download content from. The developers of this tool are not responsible for any misuse.

# InfinityGrab - Universal Video Downloader

InfinityGrab is a powerful and versatile web application that allows users to download videos and audio from various social media platforms, including YouTube, Facebook, Instagram, TikTok, Twitter (X), and Vimeo. Built with a robust Python backend (FastAPI) and a modern, responsive frontend.

## 🚀 Features

*   **Multi-Platform Support**: Download content from YouTube, Facebook, Instagram, TikTok, X (Twitter), Vimeo, and more.
*   **High Quality**: Support for HD downloads (up to 4K where available).
*   **Audio Extraction**: Option to convert and download videos as high-quality MP3 audio files.
*   **Smart Quality Selection**: Choose your preferred resolution (1080p, 720p, 480p, etc.).
*   **Fast processing**: Utilizes powerful libraries like `yt-dlp` and `pytubefix` for reliable and fast downloads.
*   **Modern UI**: A clean, responsive interface built with Bootstrap 5 and custom CSS.

## 🛠️ Technology Stack

*   **Backend**: Python 3, FastAPI, Uvicorn
*   **Core Engines**: `yt-dlp`, `pytubefix`, `FFmpeg`
*   **Frontend**: HTML5, CSS3, JavaScript, Bootstrap 5
*   **Deployment**: Ready for deployment on platforms like Render or Heroku (includes `Procfile` and `render.yaml`).

## 📋 Prerequisites

Before running the application, ensure you have the following installed:

1.  **Python 3.8+**: [Download Python](https://www.python.org/downloads/)
2.  **FFmpeg**: Required for media processing (merging video/audio, format conversion).
    *   **Windows**: [Download FFmpeg](https://ffmpeg.org/download.html), extract it, and add the `bin` folder to your system PATH.
    *   **Linux**: `sudo apt install ffmpeg`
    *   **macOS**: `brew install ffmpeg`

## ⚙️ Installation & Setup

1.  **Clone the repository** (or download the source code):
    ```bash
    git clone <repository-url>
    cd YouTube-video-downloader
    ```

2.  **Create a virtual environment** (recommended):
    ```bash
    python -m venv venv
    
    # Windows
    venv\Scripts\activate
    
    # macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Running the Application

1.  **Start the server**:
    ```bash
    python main.py
    ```
    *   The application will automatically attempt to open your default browser to `http://localhost:8000`.
    *   Alternatively, you can run: `uvicorn main:app --reload` for development.

2.  **Use the Downloader**:
    *   Paste a video URL (e.g., from YouTube) into the input field.
    *   Click **Fetch Video**.
    *   Select your desired **Quality** and **Format** (Video or Audio).
    *   Click **Download Video**.

## 📝 Configuration

*   **Desktop Mode**: By default, downloads are saved to your system's `Downloads` folder.
*   **Server Mode**: If deployed (detected via `RENDER` or `dyro` env vars), downloads are processed in a temporary directory and served explicitly to the client, then cleaned up.

## ⚠️ Disclaimer

This project is for **educational purposes only**. Please respect the copyright laws and terms of service of the respective platforms you download content from. The developers of this tool are not responsible for any misuse.



