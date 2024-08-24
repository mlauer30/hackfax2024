
# Study Buddy

[Frontend Description](#frontend-install)
[Backend Description](#backend-build-and-install)

## Project Information
A platform where users can connect with study partners through a user-friendly dashboard.
Offers a comprehensive experience for users, featuring an activity tracker for time studied, a metric system, and a group chat feature. Scoring system pairs users up based on criteria that they specify. 

## Frontend Install
### System Dependencies
This project requires:
```bash
nodejs
npm
nvm
```

### Building and Installing the package

1. Clone the repository:
```bash
$ git clone https://gitlab.com/the-cat-collective/hackathon/study_buddy_frontend
```
2. Navigate to the Project Directory
```bash
$ cd study_buddy_frontend
```
3. Install dependencies
```bash
$ npm install
```
4. Start the dev server
```bash
$ npm dev run
```
## Backend Build and Install

### System Dependencies
This project requires:
```bash
python
flask
flask_cors
openai
```

### Building and Installing the package

1. Clone the repository:
```bash
$ git clone https://gitlab.com/the-cat-collective/hackathon/study_buddy_backend
```
2. Navigate to the Project Directory
```bash
$ cd study_buddy_backend
```
3. Create a virtual environment
```bash
$ python3 -m venv env
$ source ./env/bin/activate
```
4. Build and Install the Package (without docs)
```bash
$ pip install flask flask_cors openai
```

## Acquiring API Keys
Acquire your own ChatGPT access key from OpenAI to use for this project. Please do keep in mind you will need to provide a payment method to access the API.

## Example usage
Start the backend by running the following command and complete any further configuration via the [frontend](https://gitlab.com/the-cat-collective/hackathon/study_buddy_frontend).
```bash
$ python3
```

## Licensing
* This project is licensed under the BSD 3-Clause License. Please refer to the [LICENSE](LICENSE) file for the full text of the project's license.

* For licensing information related to first and third-party components used in this project, please refer to the [LICENSING](LICENSING.md) file.

## Disclaimer
The code within this repository is provided "as-is", and no former, current, or future owners of this project and/or repository are liable for any modifications or changes undertaken to the script that violate Spotify's terms of use.
