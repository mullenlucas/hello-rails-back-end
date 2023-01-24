<a name="readme-top"></a>

<div align="center">
  <br/>
  <h3><b>Hello Rails - BackEnd Service</b></h3>
</div>

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  - [🚀 Live Demo](#live-demo)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#triangular_flag_on_post-deployment)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ](#faq)
- [📝 License](#license)

# 📖 Hello Rails - Backend <a name="about-project"></a>

> This project is intended to set-up and initialize a RoR project as a backend service along other serviecs such as React for the frontend

**Hello Rails - Backend** is the initializing base blueprint project for building apps using RoR as the backend service

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

> This App backend template was built with Ruby on Rails, using Gitflow and customized Linters

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://www.ruby-lang.org/en/">Ruby</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  <ul>
    <li><a href="https://rubyonrails.org/">Rails</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

<details>
<summary>Frontend</summary>
  <ul>
    <li><a href="https://github.com/mullenlucas/hello-react-front-end">React Frontend Repository</a></li>
  </ul>
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

- **RoR** for building integrated apps
- **PostgreSQL** as the database manager

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 💻 Getting Started <a name="getting-started"></a>

### Prerequisites

#### Check your Ruby version or install it

```shell
ruby --version && irb
```

The ouput should start with something like `ruby 3.1.2`

If not, install the right ruby version using [rbenv](https://github.com/rbenv/rbenv) (it could take a while):

```shell
rbenv install 3.1.2
```

To get a local copy up and running, follow these steps.

### Clone the repository

```shell
git clone https://github.com/mullenlucas/hello-rails-react.git
cd hello-rails-react
```

### Install

- Ensure you have PostgreSQL installed before running the application `psql --version`
- Run `bundle install`
- Create a `.env` file in the project's root folder to assign variable values for the psql database (linked to the config/database.yml)
- Run `rails db:create` and then `rails db:migrate`
- Run `rails server`
- Open Browser `http://localhost:3000/`

### .env File Structure

See the [.env.example file](.env.example)

Replacing the variable values where needed (most importantly `username` and `password`)

### Usage

To run the project, execute the following command:

```sh
  rails server
```

### Testing

To test and utilize the code, use the terminal and run ruby by inputting `irb` in the command line, or by using an extension in Visual Studio Code like _Code runner_

The user then can modify and play with the files as needed

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👥 Authors <a name="authors"></a>

👤 **Lucas Mullen**

- GitHub: [@mullenlucas](https://github.com/mullenlucas)
- LinkedIn: [LinkedIn](https://www.linkedin.com/in/lucas-mullen-447312119/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ⭐️ Show your support <a name="support"></a>

Give a ⭐️ if you like this project!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 🙏 Acknowledgments <a name="acknowledgements"></a>

- Hat tip to anyone whose code was used
- Inspiration
- To all the collaborators for the Readme Template
- The Microverse Team
- Tutorial for setting-up this project taken from [this tutorial](https://betterprogramming.pub/react-with-rails-2022-bd28e1fcd355#ad0a)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE.md) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
