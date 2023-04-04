# AI Image Generation DALL-E MERN Clone

![home-page-screenshot](https://user-images.githubusercontent.com/103476893/229875994-d8cfdac7-26d7-4dbe-9b28-9c9b93197cff.png)

## Description

This project was built using a tutorial by [JavaScript Mastery](https://www.youtube.com/watch?v=EyIvuigqDoA) on youtube.

This project is a web application that uses the OpenAI DALL-E model to generate images based on user input. The app is built using the MERN stack (MongoDB, Express, React, and Node.js) and styled with Tailwind CSS. The images are stored and served using Cloudinary.

⭐ Note: This website may require some time for the server to spin up and the posts to render. In addition, the AI functionality of this app may become unresponsive due to an inactive key. Please do not abuse the AI functionality.

## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [Links](#links)
- [License](#license)

## Installation

1. Clone the repository.
2. Install the dependencies in both the client and server folders by running `npm install`.
3. Create a .env file in the server folder and add the following environment variables:

```
OPENAI_API_KEY
```
4. Create a .env file in the client folder and add the following environment variables:

```
OPENAI_API_KEY
MONGODB_URL
CLOUDINARY_CLOUD_NAME
CLOUDINARY_API_KEY
CLOUDINARY_API_SECRET
```

5. Start the client by running `npm run dev`.
6. Start the server by running `npm start`.

⭐ Note: An active OpenAI api key is required for the AI funtionality to work.

## Features

- Image Generation: Users can generate unique images based on their text input using the OpenAI DALL-E model.
- Image Storage: All generated images are stored securely on Cloudinary, a cloud-based image management and delivery service.
- Loading Indicators: The app displays loading indicators while images and other data are being fetched or processed to provide a smooth user experience.
- Responsive Design: The app is designed to work on both desktop and mobile devices.
- Save and Share: Users can download images from the community.

## Screenshots

![create-post-screenshot](https://user-images.githubusercontent.com/103476893/229876198-a811b2aa-b470-41a3-a41c-6b3850955d04.png)

## Technologies Used

- MERN Stack: A full-stack JavaScript framework. (MongoDB, Express, React, and Node.js)
- TailwindCSS: A utility-first CSS framework for rapid UI development.
- OpenAI's DALL-E API: A model that generates images based on text prompts.
- Cloudinary: A cloud-based image and video management service.

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request.

## Links

- [Link to deployed application](https://ai-image-generation-mern-tutorial-jsm.vercel.app/)

- [Link to GitHub repository](https://github.com/kt946/ai-image-generation-mern-tutorial-jsm)

- [Link to original GitHub repository by JavaScript Mastery](https://github.com/adrianhajdin/project_ai_mern_image_generation)

- [Link to youtube tutorial by JavaScript Mastery](https://www.youtube.com/watch?v=EyIvuigqDoA)

## License

This project is licensed under the MIT License.
