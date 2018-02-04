# gitlab-heroku-ci

Example `.gitlab-ci.yml` config file to be used for CI/CD between GitLab and Heroku. 

## Getting Started

These instruction will help you setup CI/CD between GitLab and Heroku.

### Prerequisites

- [GitLab](https://gitlab.com/) Project
- [Heroku](https://heroku.com/) App

### Installing

#### Get Heroku API Key
Obtain your Heroku API key under `Account Settings > Account > API Key`. The API key follows this pattern: 00000000-0000-0000-0000-000000000000.

#### Set GitLab Variables
Define APP_DOMAIN, HEROKU_APP_NAME, and HEROKU_API_KEY variables under `Settings > CI/CD > Secret Variables` on Gitlab.

- **APP_DOMAIN** – *domain of your heroku app (ex.: google.com)*
- **HEROKU_APP_NAME** – *name of your heroku app*
- **HEROKU_API_KEY** – *the API key from previous step*

#### CI/CD Configuration File
1) Download the `config-ci.yml` file and put it into the root directory of your project  
2) Edit the `config-ci.yml` file according to your needs
3) Push the project to the upstream
4) Debug it under `CI/CD > Pipelines` on GitLab

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **</unchained** - *Initial work* - [https://unchained.studio](https://unchained.studio)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
