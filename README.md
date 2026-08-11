# AR Board — Environmental Safety

## Run locally

1. Make sure Python 3 is installed.
2. Copy `.env.example` to `.env`.
3. Put your Anthropic API key into `.env`:

```text
ANTHROPIC_API_KEY=your_key_here
```

4. Start the site:

```bash
python3 server.py
```

5. Open http://localhost:8000

The browser talks to `/api/chat`; the Python server talks to Anthropic. The API key is never sent to the browser.

## Stop

Press `Ctrl+C` in the terminal.
