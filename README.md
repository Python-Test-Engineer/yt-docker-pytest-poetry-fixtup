This is based on the following article: 

 - https://dev.to/farcellier/test-beyond-your-code-with-docker-pytest-3b7g

Copy and run from outside PyTest-Full-Stack

- `python -m venv venv`
- `.\venv\Scripts\activate` or Mac equivalent
- `pip install -r requirements.txt`
- `python -m pytest -vs`

If changing password for Postgres it needs to be changed in `test/fixtures/.hooks/hook_started.py` as it retries auth here.

*Make sure docker is running!*