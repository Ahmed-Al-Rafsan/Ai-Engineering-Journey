# 03 · API basics with `requests`

> **Level: beginner practice.** I wrote this while learning, and I left it unpolished on purpose, so it shows what I actually practised.

## What this does
Three small exercises with Python's `requests` library:
1. Fetch one post from a public test API (JSONPlaceholder) and print its title.
2. Fetch every post for one user with query parameters (`params`), then loop over them and print each title.
3. Get Melbourne's current temperature from the Open-Meteo weather API. The request has a timeout, checks the status code with `raise_for_status()`, and catches errors with `try/except`.

## How to run
```bash
pip install requests
```
Open `step_5_requests.ipynb` and run the cells from top to bottom. No API key is needed.

## What I learned
- A **client** (my Python code) sends a **request** to a **server**, and the server sends back a **response**.
- An address (URL) has parts: the scheme (`https://`), the host, the path, and query parameters after the `?`.
- A **status code** tells me what happened: 200 means OK, 404 means not found, and 5xx means the server had a problem.
- **JSON** is text that looks like Python dictionaries and lists. `response.json()` turns it into a dictionary or list.
- `timeout=10` stops my program from waiting forever. `raise_for_status()` raises an error for bad status codes. `try/except` catches that error, so the program prints a clear message instead of crashing.

## What I'm still unsure about
- I first thought `raise_for_status()` prevents crashes. It actually *raises* the error, and `try/except` is what handles it. I want to practise this more.
- I have only used GET so far. I haven't practised POST, PUT or DELETE yet.