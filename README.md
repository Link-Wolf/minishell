<div id="top"></div>

<div align="center">
 <a href="https://github.com/Link-Wolf/minishell" title="Go to GitHub repo"><img src="https://img.shields.io/static/v1?label=Link-Wolf&message=minishell&color=blue&logo=github&style=for-the-badge" alt="Link-Wolf - minishell"></a>
 <a href="https://"><img src="https://img.shields.io/badge/42_grade-98_%2F_100-brightgreen?style=for-the-badge" alt="42 grade - 98 / 100"></a>
 <a href="https://"><img src="https://img.shields.io/badge/Year-2022-ffad9b?style=for-the-badge" alt="Year - 2022"></a>
 <a href="https://github.com/Link-Wolf/minishell/stargazers"><img src="https://img.shields.io/github/stars/Link-Wolf/minishell?style=for-the-badge&color=yellow" alt="stars - minishell"></a>
 <a href="https://github.com/Link-Wolf/minishell/network/members"><img src="https://img.shields.io/github/forks/Link-Wolf/minishell?style=for-the-badge&color=lightgray" alt="forks - minishell"></a>
 <a href="https://github.com/Link-Wolf/minishell/issues"><img src="https://img.shields.io/github/issues/Link-Wolf/minishell?style=for-the-badge&color=orange" alt="issues - minishell"></a>
 <a href="https://www.apple.com/macos/" title="Go to Apple homepage"><img src="https://img.shields.io/badge/OS-macOS-blue?logo=apple&logoColor=white&style=for-the-badge&color=9cf" alt="OS - macOS"></a>
</div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a>
    <img src="https://www.42mulhouse.fr/wp-content/uploads/2022/06/logo-42-Mulhouse-white.svg" alt="Logo" width="192" height="80">
  </a>

  <h3 align="center">minishell</h3>

  <p align="center">
   <em>As cute as a real shell</em><br/>
    A C project to create a minimalist shell, our own little bash (ft. <a href="https://github.com/laird-ikar">bguyot</a>)
    <br />
    <br />
    <a href="https://github.com/Link-Wolf/minishell/issues">Report Bug</a>
    ·
    <a href="https://github.com/Link-Wolf/minishell/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

<div align="center">
  <a>
    <img src="https://media.discordapp.net/attachments/453159761639112706/1055501555102654584/image.png" alt="minishell header">
  </a>
</div>
</br>
This project is presented as a way to discover the basics of a shell, and it's a group project i made it with <a href="https://github.com/laird-ikar">bguyot</a>.
It requires us to create a simple shell that can execute commands, manage the environment, handle errors and signals, and more.

Specifically, we have to:
- Display a prompt when waiting for a new command
- Search and launch the right executable (based on the PATH variable or by using relative or absolute path)
- It must implement the builtins like in bash:
  - echo with option ’-n’
  - cd with only a relative or absolute path
  - pwd without any options
  - export without any options
  - unset without any options
  - env without any options and any arguments
  - exit without any options
- `|` must work
- `>` and `<` must work
- `>>` must work
- `Ctrl-C`, `Ctrl-D` and `Ctrl-\` must be handled
- return value must be handled
- `"` and `'` must work

Everything is to be checked against `bash` in case of doubt.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

Because it's a simple C project, there isn't much to say here

### Prerequisites

Having a C compiler like cc, gcc or clang

### Installation

1. Clone the repo

   ```sh
   git clone https://github.com/Link-Wolf/minishell.git
   ```

2. Compile the project

   ```sh
   cd minishell; make
   ```

3. Execute it

   ```sh
   ./minishell
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

Use the minishell as you'd use bash or zsh, but please be kind to him and remember he's (too) fragile !

<div align="center">
 <a>
   <img src="https://media.discordapp.net/attachments/453159761639112706/1055503158283096065/image.png" alt="minishell example">
 </a>
</div>

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [ ] Fix some ~~(a lot of)~~ errors and extremes cases
- [ ] Add bonus features
- [x] Add back to top links

See the [open issues](https://github.com/Link-Wolf/minishell/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Mail : xxxxxxx@student.42mulhouse.fr

Project Link: [https://github.com/Link-Wolf/minishell](https://github.com/Link-Wolf/minishell)

<p align="right">(<a href="#top">back to top</a>)</p>
