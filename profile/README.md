<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/board-together">
    <img src="https://github.com/board-together/BE-Board-Together/raw/main/public/board-together.png" alt="Logo">
  </a>

  <h1 align="center">Board (games) Together!</h3>

  <h3 align="center">
    Board Game Swap Application
    <br />
  </h3>
</div>

<!-- TABLE OF CONTENTS -->
<h4>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#deployment-information">Deployment Information</a></li>
        <li><a href="#built-with">Built With</a></li>
        <li><a href="#database-schema">Database Schema</a></li>
        <li><a href="#learning-goals">Learning Goals</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
          <li><a href="#repositories">Repositories</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</li>
  </ol>
</h4>

<!-- ABOUT THE PROJECT -->
## About The Project

Board Together is a board game platform that allows users to create their own profiles and list their favorite board games. It utilizes GraphQL and PostgreSQL to create a seamless user experience and features API calls to the popular Board Game Atlas API to provide up-to-date information about various board games. With this platform, board game enthusiasts can keep track of their collection, discover new games to play, and connect with others who share their interests. The platform is easy to use and accessible to anyone who loves board games or wants to learn more about them.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Deployment Information -->
### Deployment Information

Board Together is a full-stack application combining a React frontend deployed to Surge, and Ruby on Rails backend deployed to Heroku. The frontend handles client-side tasks and displays data from the backend, which handles server-side logic and database operations. Deployment involves building the React frontend, integrating it with the Rails backend, and pushing the code to Heroku. The application can be accessed at the Surge URL.

* <a href="https://board-together.surge.sh/" alt="Surge Deployment">Frontend Surge Deployment</a>
* <a href="https://board-together.herokuapp.com/" alt="Heroku Deployment">Backend Heroku Deployment</a><br>

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Built With -->
### Built With

<img alt="Board Together-FE-Tech Stack" src="https://user-images.githubusercontent.com/60988144/219110787-3968c539-cb23-4021-81d5-41e4f039ad6d.png" height="90%" width="90%">
<img alt="tech-stack-BE" src="https://user-images.githubusercontent.com/60988144/219104874-9f3d2583-3006-4f5b-a4ff-241a75c60f6d.png" height="90%" width="90%">

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Database Schema -->
### Database Schema

![Schema 2-6-23](https://user-images.githubusercontent.com/60988144/219105395-0710eb9a-df06-481c-b25d-bc5bbe16942f.png)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Learning Goals -->
### Learning Goals

* Implement GraphQL into a React and Rails application.
* Work in a full-stack development team.
* Utilize continuous integration with CircleCI.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

Board Together utilizes a service oriented architecture with separate backend and frontend services. Installation instructions for the backend repository below. Frontend installation instructions can be found in the repository section. The Postman mock server below can be used to test the available endpoints. Expected request and response formats are listed for CRUD functionality.

<!-- Repositories -->
### Repositories

* <b>Frontend installation instructions:</b> https://github.com/board-together/FE-Board-Together <br />
* <b>Backend installlation instructions:</b> https://github.com/board-together/BE-Board-Together <br />

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

MVP

* CRUD functionality for User and UserGames.
* Search for a board game utilizing [Board Game Atlas API](https://www.boardgameatlas.com/api/docs/search).
* Add board games to User collection.
* Track board games you have borrowed and board games you have lent out.

Stretch Goals

* Add friends feature, allowing a User to add friends and see that friend's games instead of all User's games.
* Implement User authentication using a OAuth provider.
* Create board game parties, where friends can arrange get togethers to play a certain game.
* Ability to add comments or reviews to games you have, or have borrowed.
* Email notifications for requests to borrow games.

See the [open issues](https://github.com/board-together/FE-Board-Together/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact
### FRONTEND
<table>
  <tr>
    <td><img src="https://avatars.githubusercontent.com/u/110054994?s=150&v=4"></td>
    <td><img src="https://avatars.githubusercontent.com/u/74210902?s=150&v=4"></td>
    <td><img src="https://avatars.githubusercontent.com/u/105405396?s=150&v=4"></td>
  </tr>
  <tr>
    <td>Brett Kuhn</td>
    <td>Spencer Haka</td>
    <td>Thomas Peterson</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/bkuhn2">GitHub</a><br>
      <a href="https://www.linkedin.com/in/brett-kuhn/">LinkedIn</a>
    </td>
    <td>
      <a href="https://github.com/Speekins">GitHub</a><br>
      <a href="https://www.linkedin.com/in/spencer-haka/">LinkedIn</a>
    </td>
    <td>
      <a href="https://github.com/thomedpete">GitHub</a><br>
      <a href="https://www.linkedin.com/in/thomas-peterson-web-dev/">LinkedIn</a>
    </td>
  </tr>
</table>

### BACKEND
<table>
  <tr>
    <td><img src="https://avatars.githubusercontent.com/u/102780642?s=150&v=4"></td>
    <td><img src="https://avatars.githubusercontent.com/u/101418582?s=150&v=4"></td>
    <td><img src="https://avatars.githubusercontent.com/u/60988144?s=150&v=4"></td>
    <td><img src="https://avatars.githubusercontent.com/u/35391349?s=150&v=4"></td>
  </tr>
  <tr>
    <td>Annie Pulzone</td>
    <td>Bryan Keener</td>
    <td>Darby Smith</td>
    <td>Michael Marchand</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/ajpulzone">GitHub</a><br>
      <a href="https://www.linkedin.com/in/annie-pulzone/">LinkedIn</a>
    </td>
    <td>
      <a href="https://github.com/bkeener7">GitHub</a><br>
      <a href="https://www.linkedin.com/in/bkeener/">LinkedIn</a>
    </td>
    <td>
      <a href="https://github.com/DarbySmith">GitHub</a><br>
      <a href="https://www.linkedin.com/in/darby-m-smith/">LinkedIn</a>
    </td>
    <td>
      <a href="https://github.com/marchandMD">GitHub</a><br>
      <a href="https://www.linkedin.com/in/mmarchand1/">LinkedIn</a>
    </td>
  </tr>
</table>

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Turing School of Software Design: [https://turing.edu/](https://turing.edu/)
<p>Project Manager: Leta Keane</p>
<p>Project Mentor: Khoa Nguyen</p>

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

