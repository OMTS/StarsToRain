# StarsToRain

Python script that exports all Github Stars for a given user into an HTML file importable by Raindrop.io

## Installation and Usage

Installation/running the script has been verified with Python 3.8.6.

1. Clone this repo
2. Set up a virtual environment:

```
python3 -m venv venv && source venv/bin/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the script:

```bash
python starsToRain.py
```

You will be prompted for your Github username and password. If you're using two-factor authentication, you may need to set up a [Github token](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/creating-a-personal-access-token) (it only requires user-level permissions).

Once the script is done doing the export you'll find your html file in the `output` directory.
