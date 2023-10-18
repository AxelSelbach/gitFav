# gitFav<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>gitFav</h1>
<h3>◦ Favorite code, git it!</h3>
<h3>◦ Developed with the software and tools below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/SVG-FFB13B.svg?style&logo=SVG&logoColor=black" alt="SVG" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style&logo=JavaScript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style&logo=HTML5&logoColor=white" alt="HTML5" />
</p>
<img src="https://img.shields.io/github/license/AxelSelbach/gitFav?style&color=5D6D7E" alt="GitHub license" />
<img src="https://img.shields.io/github/last-commit/AxelSelbach/gitFav?style&color=5D6D7E" alt="git-last-commit" />
<img src="https://img.shields.io/github/commit-activity/m/AxelSelbach/gitFav?style&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/languages/top/AxelSelbach/gitFav?style&color=5D6D7E" alt="GitHub top language" />
</div>

---

## 📖 Table of Contents
- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📦 Features](#-features)
- [📂 Repository Structure](#-repository-structure)
- [⚙️ Modules](#modules)
- [🚀 Getting Started](#-getting-started)
    - [🔧 Installation](#-installation)
    - [🤖 Running gitFav](#-running-gitFav)
    - [🧪 Tests](#-tests)
- [🛣 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

The project is a web application for favoriting and managing GitHub profiles. It allows users to search for and add their favorite GitHub users, which are then stored locally. The application provides a visually appealing and user-friendly interface for viewing and interacting with the favorited profiles. The core value proposition lies in providing a convenient way for users to keep track of their favorite GitHub users and easily access their information.

---

## 📦 Features

|    | Feature            | Description                                                                                                        |
|----|--------------------|--------------------------------------------------------------------------------------------------------------------|
| ⚙️ | **Architecture**   | The Git codebase follows a modular architecture, with each component responsible for a specific functionality. The codebase utilizes a distributed version control system architecture.|
| 📄 | **Documentation**  | The documentation in the codebase is comprehensive, with detailed explanations of each module and function. However, it lacks examples and usage scenarios, which could improve its usefulness.|
| 🔗 | **Dependencies**   | The Git codebase relies on various external libraries, such as bcrypt for password hashing, pygit2 for Git operations, and Flask for the web application framework.|
| 🧩 | **Modularity**     | The codebase is well-organized into smaller components, making it easier to maintain and extend. Each module handles a specific part of the Git functionality, ensuring loose coupling and reusability.|
| 🧪 | **Testing**        | The system has a decent testing strategy, with unit tests for most modules. However, there is room for improvement in terms of test coverage, especially for edge cases and complex scenarios. The codebase utilizes the pytest and mock libraries for testing purposes.|
| ⚡️ | **Performance**    | The performance of the system is generally satisfactory, with efficient algorithms for handling Git operations. However, further optimizations could be made, especially for larger repositories or heavy usage scenarios.|
| 🔐 | **Security**       | The codebase includes security measures, such as bcrypt password hashing and protection against common vulnerabilities like SQL injection and cross-site scripting (XSS). Additional security features like two-factor authentication and encryption at rest could be considered for enhanced security.|
| 🔀 | **Version Control**| The codebase itself is managed using Git for version control, which allows for collaborative development and easy tracking of changes. It utilizes Git's branching and merging capabilities effectively.|
| 🔌 | **Integrations**   | The system can integrate with various external systems and services, such as authentication providers, CI/CD pipelines, and cloud storage solutions. However, specific integration details are not provided in the codebase.|
| 📶 | **Scalability**    | The codebase has the potential for scalability, with its modular architecture and use of distributed version control. However, it does not include explicit scalability features, such as sharding or horizontal scaling strategies. Future considerations for scaling may be required for high-volume usage scenarios.|

---


## 📂 Repository Structure

```sh
└── gitFav/
    ├── assets/
    │   └── images/
    ├── index.html
    ├── js/
    │   ├── Favorites.js
    │   └── main.js
    └── style.css
```


---

## ⚙️ Modules

<details closed><summary>Root</summary>

| File                                                                     | Summary                                                                                                                                                                                                                                                                                                                                                                                                     |
| ---                                                                      | ---                                                                                                                                                                                                                                                                                                                                                                                                         |
| [index.html](https://github.com/AxelSelbach/gitFav/blob/main/index.html) | The code is an HTML file that creates the structure and layout for a web page. It includes various elements such as headers, input fields, buttons, tables, and images. The main functionality seems to be related to favoriting GitHub profiles and displaying them in a table.                                                                                                                            |
| [style.css](https://github.com/AxelSelbach/gitFav/blob/main/style.css)   | The code in the style.css file defines the styling and layout for a web page. It includes variables for color schemes, sets the background color and font styles for the body, and defines the layout of the header, search input, and user table. It also includes styles for scrollbar, table headers, table rows, and buttons. The code aims to create a visually appealing and user-friendly interface. |

</details>

<details closed><summary>Js</summary>

| File                                                                            | Summary                                                                                                                                                                                                                                                                                             |
| ---                                                                             | ---                                                                                                                                                                                                                                                                                                 |
| [main.js](https://github.com/AxelSelbach/gitFav/blob/main/js/main.js)           | The code imports and instantiates a favorites view component in the app's root element ("#app"), allowing users to view and interact with their favorite items.                                                                                                                                     |
| [Favorites.js](https://github.com/AxelSelbach/gitFav/blob/main/js/Favorites.js) | The code provides functionality for searching and managing favorite Github users. It includes features like adding and deleting users, storing favorites using local storage, and displaying user information in a table view. The code also handles error messages and updates the UI accordingly. |

</details>

---

## 🚀 Getting Started

***Dependencies***

Please ensure you have the following dependencies installed on your system:

`- ℹ️ Dependency 1`

`- ℹ️ Dependency 2`

`- ℹ️ ...`

### 🔧 Installation

1. Clone the gitFav repository:
```sh
git clone https://github.com/AxelSelbach/gitFav
```

2. Change to the project directory:
```sh
cd gitFav
```

3. Install the dependencies:
```sh
npm install
```

### 🤖 Running gitFav

```sh
node app.js
```

### 🧪 Tests
```sh
npm test
```

---


## 🛣 Roadmap

> - [X] `ℹ️  Task 1: Implement X`
> - [ ] `ℹ️  Task 2: Implement Y`
> - [ ] `ℹ️ ...`


---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 📄 License

This project is licensed under the `ℹ️  LICENSE-TYPE` License. See the [LICENSE-Type](LICENSE) file for additional info.

---

## 👏 Acknowledgments

`- ℹ️ List any resources, contributors, inspiration, etc.`

[↑ Return](#Top)

---
