## Password Security Checker

The Password Security Checker is a Python script that helps you assess the security of your passwords by checking whether they have been compromised in previous data breaches. It utilizes the "Have I Been Pwned" API to determine if your password has been found in publicly available datasets of compromised passwords.

![Password Security Checker](screenshot.png)

### Features

- Checks the security of your passwords against known breaches.
- Provides information on how many times a password has been found in data breaches.
- Helps you make informed decisions about changing compromised passwords.

### Prerequisites

- Python 3.x
- `hashlib` library (usually included with Python)
- `requests` library (install using `pip install requests`)

### Usage

1. Clone or download this repository to your local machine.
2. Open a terminal or command prompt and navigate to the project directory.

3. Run the script by executing the following command:
   ```shell
   python password_checker.py <password1> <password2> ...
   ```
   Replace `<password1>`, `<password2>`, etc. with the passwords you want to check.

4. The script will display the results for each password:
   - If the password has been compromised, it will show how many times it was found in breaches and suggest changing it.
   - If the password has not been compromised, it will indicate that it's secure.

### Example

```shell
python password_checker.py Password123 SecurePass! MySecretPassword
```

### Screenshots

You can find screenshots of the script in action in the `screenshots` directory.

### Contributing

Contributions are welcome! If you find any issues or want to enhance the script, feel free to fork this repository and submit a pull request.

### License

This project is licensed under the [MIT License](LICENSE).

### Disclaimer

This script communicates with a third-party API to check the security of your passwords. While efforts have been made to ensure the accuracy of the information, there are no guarantees. Use this tool as a part of your security practices, but always exercise caution and follow best practices for password security.

