
# BreachShield


BreachShield is a web application that enables users to conduct secure searches across various data breaches, helping them ascertain whether their password has ever been compromised. Additionally, it offers essential recommendations to strengthen passwords and presents a comprehensive roster of breached websites, complete with breach dates, the number of compromised accounts, and the breached data.

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#Key Features">Key Features</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
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
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


## Key Features
- Securely search multiple data breaches to determine if a password has been compromised.
- Provide password strength recommendations based on industry best practices.
- Display an exhaustive list of breached websites with breach dates, compromised account counts, and breached data.

## Project Setup Instruction

1. Clone the project

```bash
  git clone https://github.com/bhavy2202/BreachShield.git
```

2. Make sure python 3.8 or above and pip is installed. Refer [here](https://www.python.org/downloads/) for python installation.


3. Create and activate a virtual environment.

4. Navigate to project directory and run this command on terminal to install all the project requirements.
```bash
pip install -r requirements.txt
```

5. Run this on terminal to set the FLASK_APP environment variable. 

- For Mac/Linux:
```bash
 export FLASK_APP=pwned_credentials.py
```

- For Windows:
```bash
 set FLASK_APP=pwned_credentials.py
```

6. Execute this command on the terminal to launch the application.

```bash
 flask run
```
