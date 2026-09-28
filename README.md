# quotecrate

Discord utility bot for my study group server

Started as a weekend hack, grew on me.

## Installation

```bash
pip install -r requirements.txt
cp .env.example .env  # put your token in .env
```

## Examples

```bash
python bot.py
# then /remind 10m stretch and /quote in your server
```

## Highlights

- Recurring reminders stored in a JSON file
- Graceful shutdown flushing state to disk
- Slash commands via discord.py app_commands
- Rate-limit friendly: single task loop

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .env.example
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── bot.py
└── requirements.txt
```

## FAQ

**Is this production ready?**  
It works for my use case; review the code before relying on it.

**Why no framework?**  
The stdlib covers what this project needs.

## License

MIT. Do whatever you want.
