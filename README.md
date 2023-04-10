# MindMate AI Therapist Mobile Application

Welcome to the MindMate AI Therapist Mobile Application repository! This project aims to create a mobile application that provides cognitive therapy through an AI-powered virtual therapist. The therapist is animated in real-time and responds to the user seeking cognitive therapy. The app calls an API from D-ID to display the virtual therapist, and the therapist charges $4.99 per hour of psychotherapy. The first session is free.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)

## Installation

To install the MindMate AI Therapist Mobile Application, you can follow these steps:

1. Clone the repository: `git clone https://github.com/yourusername/mindmate.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Set up the environment variables required by the application (see `config.py`)
4. Initialize the database: `python src/database.py`
5. Start the application: `python src/app.py`

## Usage

Once the application is running, you can access it through your preferred web browser or mobile device by navigating to the appropriate URL. The home page will allow you to sign up or log in as a user or therapist. From there, you can access the virtual therapist and begin a session.

## API Documentation

The MindMate AI Therapist Mobile Application uses several APIs to function, including the D-ID API for displaying the virtual therapist. Documentation for these APIs can be found at the following links:

- [D-ID API](https://docs.d-id.com/)
- [Payment Gateway API](https://docs.paymentgateway.com/)
- [MindMate User API](https://docs.mindmate.com/user-api)
- [MindMate Therapist API](https://docs.mindmate.com/therapist-api)

## Contributing

We welcome contributions from anyone interested in improving the MindMate AI Therapist Mobile Application. If you have ideas for new features or improvements, please open an issue or pull request on this repository.

## File Structure 

```
mindmate/
├── src/
│   ├── api/
│   │   ├── did_api.py
│   │   ├── therapist_api.py
│   │   └── user_api.py
│   ├── models/
│   │   ├── user.py
│   │   └── therapist.py
│   ├── services/
│   │   ├── auth_service.py
│   │   ├── payment_service.py
│   │   ├── therapist_service.py
│   │   └── user_service.py
│   ├── utils/
│   │   ├── animation.py
│   │   ├── data_validation.py
│   │   ├── error_handling.py
│   │   ├── logger.py
│   │   └── notifications.py
│   ├── views/
│   │   ├── home_view.py
│   │   ├── payment_view.py
│   │   ├── therapist_view.py
│   │   └── user_view.py
│   ├── app.py
│   ├── config.py
│   ├── constants.py
│   ├── database.py
│   └── __init__.py
├── tests/
│   ├── api_tests/
│   │   ├── did_api_test.py
│   │   ├── therapist_api_test.py
│   │   └── user_api_test.py
│   ├── services_tests/
│   │   ├── auth_service_test.py
│   │   ├── payment_service_test.py
│   │   ├── therapist_service_test.py
│   │   └── user_service_test.py
│   ├── utils_tests/
│   │   ├── animation_test.py
│   │   ├── data_validation_test.py
│   │   ├── error_handling_test.py
│   │   ├── logger_test.py
│   │   └── notifications_test.py
│   ├── views_tests/
│   │   ├── home_view_test.py
│   │   ├── payment_view_test.py
│   │   ├── therapist_view_test.py
│   │   └── user_view_test.py
│   ├── __init__.py
│   └── conftest.py
├── .gitignore
├── LICENSE
├── README.md
├── requirements.txt
└── setup.py
`````


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
