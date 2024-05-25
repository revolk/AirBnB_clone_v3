# AirBnB Clone - RESTful API

## Description

This project is part of the Holberton School curriculum and involves creating a RESTful API for an AirBnB clone. The API interacts with a MySQL database and supports operations for managing users, places, reviews, and more.

## Installation

### Prerequisites

- Python 3.8 or later
- pip (Python package installer)
- MySQL database

### Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. **Install the `python3-venv` package if not already installed:**

    ```bash
    sudo apt install python3.8-venv
    ```

3. **Create and activate a virtual environment:**

    On macOS and Linux:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

    On Windows:
    ```bash
    python3 -m venv venv
    .\venv\Scripts\activate
    ```

4. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

5. **Set up environment variables and run the application:**

    ```bash
    HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db python3 -m api.v1.app
    ```

## Usage

To run the application, use the following command:

```bash
HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db python3 -m api.v1.app

Authors
Muna Elmetwally
GitHub: Muna-Elmetwally
Email: munaelmetwally2397@gmail.com
Ramy Al Sorogy
GitHub: revolk
Email: finalrevolk@gmail.com
Acknowledgements
We would like to extend our special thanks to the instructors and peers at Holberton School for their guidance and support throughout the development of this project. Your feedback and assistance have been invaluable in helping us achieve our learning objectives and complete this project successfully.
