<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="https://i.imgur.com/9YwJsO2.png" alt="Logo">
<h2 align="center">RAG template</h2>
</div>

<!-- PROJECT SHIELDS -->
<p align="center">
[![React][React.js]][React-url]
[![Docker][Docker]][Docker-url]
[![Storybook][Storybook.js]][Storybook-url]
</p>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Quick Navigation</summary>
  <ol>
    <li><a href="#preview">Preview</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#run-manually">Running the Application</a></li>
      </ul>
    </li>
    <li><a href="#storybook">Storybook</a></li>
  </ol>
</details>



<!-- Preview Image -->

[![Product Name Screen Shot][product-screenshot]](https://example.com)


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started



### Prerequisites

This application requires `poetry` in order to run the python server.

1. Navigate to applications backend
   ```sh
   cd app
   ```
2. Install poetry
   ```sh
   poetry install --no-root
   ```

## Run Manually

### Start python server
1. Navigate to applications backend
   ```sh
   cd app
   ```
2. Start running the backend server
   ```sh
   poetry run uvicorn main:app --host 0.0.0.0 --port 8080 --reload
   ```

### Launch frontend
1. Navigate to applications frontend
   ```sh
   cd frontend
   ```
2. Start frontend; (https://localhost:3000/)
   ```sh
   npm start
   ```

## Using Docker
1. Ensure `Docker Desktop` if running
2. From the root folder, use the following command
   ```sh
   docker-compose up --build
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Storybook
Storybook allows us to interact with the applications existing components and prototype new ones that will allow us to easily change out component styles for demos or client branding

### Launch Storybook.js
1. Navigate to the strorybook folder
   ```sh
   cd storybook
   ```
3. Start Storybook; (https://localhost:6006/)
   ```sh
   npm run storybook
   ```



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[product-screenshot]: images/screenshot.png
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Docker]:https://img.shields.io/badge/Docker-%231286C5?style=for-the-badge
[Docker-url]: https://www.docker.com/
[Storybook.js]: https://img.shields.io/badge/Storybook.js-%23ff4885?style=for-the-badge
[Storybook-url]: https://storybook.js.org/


