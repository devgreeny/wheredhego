# Wheredhego

Daily Wordle-style sports quiz game at wheredhego.com. Founded July 2025.

**Traction:** 23K+ unique visitors, 500K+ page hits within 3 months of launch, all organic.

## Stack
- Backend: Flask (Python), SQLite (dev) / MySQL (prod)
- Frontend: JavaScript, HTML/CSS
- AI: Generative AI for dynamic content generation
- Deployment: WSGI (wsgi.py), run via run.py

## Games
- **CreatorPoll** — college football creator poll (poll voting, standings)
- **Starting 5** — NBA quiz game
- More quiz formats in `quizzes/` directory

## Key files
- `run.py` — Flask app entry point
- `wsgi.py` — production WSGI config
- `app/` — main Flask application (routes, models, templates)
- `app/creatorpoll/` — College Football Creator Poll feature
- `app/starting5/` — NBA Starting 5 quiz
- `quizzes/` — quiz data
- `scripts/` — utility scripts

## Current state
- Live and getting traffic
- Multiple quiz games running
- MySQL for production, SQLite for local dev
