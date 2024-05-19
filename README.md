# My Video Page

Welcome to **My Video Page**, a simple and elegant video streaming webpage. This project is designed to showcase and stream your favorite videos directly from your own website.

## Important Note

- It is hard to implement mkv or any other video format as most of the browser doesnot support mkv file system so you must use mp4 file format only.

## Features

- **Responsive Design**: The page is designed to be responsive and accessible on different devices and screen sizes.
- **Multiple Videos**: Currently supports streaming multiple videos.
- **Easy Navigation**: Clear and simple layout for easy navigation and viewing.

## Technologies Used

- **HTML5**: For the structure of the webpage.
- **CSS3**: For styling and layout.

## Setup and Usage

To get this project up and running on your local machine, follow these steps:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/my-video-page.git
    ```
2. **Navigate to the Project Directory**
    ```bash
    cd my-video-page
    ```
3. **Open the `index.html` file in your Browser**
    - You can do this by simply double-clicking the `index.html` file or by opening it from your browser's file menu.

## Directory Structure

```plaintext
my-video-page/
├── index.html
├── styles.css
└── videos/
    ├── video1.mp4
    └── video2.mp4
```

- `index.html`: The main HTML file for the webpage.
- `styles.css`: The CSS file containing the styles for the webpage.
- `videos/`: A directory containing the video files.

## How to Add More Videos

1. **Add your video files** to the `videos/` directory.
2. **Update the `index.html` file** to include your new video entries. Here’s an example of how to add another video:

    ```html
    <div class="video">
        <h2>Video Title 3</h2>
        <video width="560" height="315" controls>
            <source src="videos/video3.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
    ```
## Upload to internet
- USE THE SAME FOLDER WHICH YOU WANT TO DISPLAY ON YOUR Webpage to Start the server
```bash
python3 -m http.server --bind 127.0.0.1 8080
```
