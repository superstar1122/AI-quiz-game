# AI Quiz — Simple Game

A lightweight quiz game that uses AI-generated questions and simple scoring. Designed for local play and easy extension.

## Features
- AI-generated multiple-choice questions (configurable difficulty)
- Timed rounds and score tracking
- CLI and web UI examples included
- Easy to extend and test

## Tech stack
- PHP, JS, HTML, CSS, API Integration

## Run
Web UI (if included):
```bash
# then open http://localhost
```

## How to play
- Start the app (CLI or web).
- Choose a category and difficulty.
- Answer multiple-choice questions before time runs out.
- Points awarded for correct and quick answers. Final score shown at end of round.

## Project structure (example)
- /src — source code
    - /cli — command-line interface
    - /web — frontend (minimal)
    - /api — AI/question logic
- /data — static questions and assets
- README.md, package.json, .env.example

## Development
- Add tests under /tests
- Keep AI calls abstracted behind an adapter to allow swapping providers
- Use linting and formatters (ESLint, Prettier)

## Contributing
- Fork → feature branch → PR with tests and description
- Follow repository coding style and add documentation for new features

## License