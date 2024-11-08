# Custom-404-Page

This project provides a stylish and responsive custom 404 error page using HTML and CSS. The custom 404 page enhances the user experience by offering a friendly message, useful navigation, and a visually appealing design to guide visitors back to the main content of the site.

## Features
- **Responsive Design**: Looks great on both desktop and mobile devices.
- **Curved Borders**: Stylish curved borders for the image and content box.
- **Easy Customization**: Simple to update with your own branding and content.
- **User-Friendly Navigation**: Helps users find their way back to useful pages.

## Demo
Here's how the custom 404 page looks:

![Custom 404 Page](https://github.com/TechyShreyansh/Custom-404-Page-Master/blob/main/Images/404.png)

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/Custom-404-Page.git
    ```
2. **Navigate to the project directory**:
    ```sh
    cd Custom-404-Page
    ```

## Usage

1. **HTML Structure**:
    Add the following HTML to your 404 error page:
    ```html
    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Document</title>
        <link rel="stylesheet" href="style.css" />
      </head>
      <body>
        <div class="custom404">
          <div>
            <img src="images/404.png" alt="" />
          </div>

          <div class="custom404-content">
            <p>Hi, I think you are lost!</p>
            <p>
              Please click
              <a href="https://appiemods.blogspot.com">here</a> to go back to
              the <a href="https://appiemods.blogspot.com">Home Page</a>
            </p>
          </div>
        </div>
      </body>
    </html>
    ```

2. **CSS Styles 1**:
    Create a `style.css` file with the following content:
    ```css
    .custom404 {
      display: flex;
      align-items: center;
      flex-direction: column;
      text-align: center;
      font-family: "Roboto", sans-serif;
    }

    .custom404 img {
      width: 70%;
    }

    .custom404 .custom404-content {
      background: #222;
      padding: 8px 48px;
      color: #eee;
      border-radius: 10px;
    }

    .custom404 .custom404-content a {
      color: #eee;
    }
    ```

    3. **CSS Styles 2**:
    Create a `style.css` file with the following content:
    ```css
    .custom404 {
      display: flex;
      align-items: center;
      flex-direction: column;
      text-align: center;
      font-family: "Roboto", sans-serif;
      padding: 20px; /* Ensure some padding for responsiveness */
    }
    
    .custom404 img {
      width: 70%;
      border-radius: 15px; /* Adds curved borders to the image */
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Adds a subtle shadow for better visual effect */
    }
    
    .custom404 .custom404-content {
      background: #222;
      padding: 8px 48px;
      color: #eee;
      border-radius: 10px;
      max-width: 90%; /* Ensure it doesn't exceed 90% of the container width */
      margin: 20px 0; /* Add some margin for spacing */
    }
    
    .custom404 .custom404-content a {
      color: #eee;
    }
    
    @media (max-width: 768px) {
      .custom404 img {
        width: 100%; /* Full width for smaller screens */
      }
    
      .custom404 .custom404-content {
        padding: 8px 24px; /* Adjust padding for smaller screens */
      }
    }    
    ```

4. **Customization**:
    - Replace `images/404.png` with the actual path to your 404 image.
    - Adjust text and styles as needed to match your branding.

## Contributing
Feel free to contribute to this project by submitting a pull request. Your contributions are always welcome!

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
