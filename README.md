
# BreachShield

![1](https://github.com/bhavy2202/BreachShield/assets/114098067/97bec663-8a92-4873-92f4-6e4ba079778f)
BreachShield is a web application that enables users to conduct secure searches across various data breaches, helping them ascertain whether their password has ever been compromised. Additionally, it offers essential recommendations to strengthen passwords and presents a comprehensive roster of breached websites, complete with breach dates, the number of compromised accounts, and the breached data.
It utilizes 
[k-anonymity](https://en.wikipedia.org/wiki/K-anonymity) which allows external parties to use
it and maintain anonymity. The pwned password service only requires first 5 characters of SHA-I 
password hash and returns a list of SHA-I hashes matching the first 5 characters, thus delegating the 
responsibility to the client to match the password hash against the list provided by the service. This 
ensures that the service is not aware about the full password hash and thus cannot use it to generate the 
raw password.
Please refer [here](https://www.troyhunt.com/ive-just-launched-pwned-passwords-version-2/) for further
details with illustrated example.

## Key Features
- Securely search multiple data breaches to determine if a password has been compromised.
- Provide password strength recommendations based on industry best practices.
- Display an exhaustive list of breached websites with breach dates, compromised account counts, and breached data.
![2](https://github.com/bhavy2202/BreachShield/assets/114098067/ba55207c-3f8f-451b-9086-402ffbe3cb4e)

## Technologies Used
- Flask: Backend web framework for Python.
- HTML, CSS, JavaScript: Frontend technologies for creating a user-friendly interface.
- Flask-Bootstrap4: Integration of Bootstrap framework for enhanced UI components.
- Flask-WTF: Simplified form handling using WTForms library.

  
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
## Acknowledgments
I would like to express my gratitude to the developers and contributors of Flask, Flask-Bootstrap4, and Flask-WTF for their valuable libraries and resources.

## Contact Information
For any questions or feedback, please contact me at [bhavyrahangdale2202@gmail.com].
