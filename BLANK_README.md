<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/iuvo-ai/chatbot-rag-templates">
    <img src="public/favicon.ico" alt="Logo" width="80" height="80">
  </a>

<h2 align="center">Frontend Design</h3>
<h3 align="center">iuvo-ai RAG template</h3>

<!-- TABLE OF CONTENTS -->
<details align="left">
  <summary>Quick Nav</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#running-the-application">Running the Application</a></li>
      </ul>
    </li>
    <li><a href="#storybook">Storybook</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Here's a blank template to get started: To avoid retyping too much info. Do a search and replace with your text editor for the following: `github_username`, `repo_name`, `twitter_handle`, `linkedin_username`, `email_client`, `email`, `project_title`, `project_description`

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![React][React.js]][React-url]

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

## Running the application

## Manually
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
1. Navigate to the project's root
2. Start Storybook; (https://localhost:6006/)
   ```sh
   npm run storybook
   ```

<!-- ROADMAP -->
## Roadmap

- [ ] Login page
- [ ] Main application
    - [ ] Global document storage

See [open issues](https://github.com/iuvo-ai/chatbot-rag-templates/issues) for a full list of proposed features (and known issues).


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/iuvo-ai/chatbot-rag-templates/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/company/iuvo-ai-technologies
[product-screenshot]: images/screenshot.png
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/

