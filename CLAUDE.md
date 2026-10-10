# AI Personal Assistant – Project Context

## Project Goal

Build an educational AI Personal Assistant that helps users manage email and calendar workflows.

The application will receive events from communication providers, normalize incoming data, process events through AI-assisted workflows, and suggest useful next steps.

Consequential actions, such as sending emails or changing calendar events, must require user approval.

## Technology Stack

- Python 3.12
- uv for Python dependency management
- FastAPI for the application API
- Pydantic for data validation
- OpenAI API for AI capabilities
- Nylas API for email and calendar integration
- PostgreSQL and SQLAlchemy for data persistence
- Docker and Docker Compose for containerization
- Git and GitHub for version control



## Project Structure

Follow the architecture described in `README.md` as the application is developed.

The initial project structure for Week 1 is:

- `src/` – source code directory, initially empty
- `tests/` – automated tests, initially empty
- `main.py` – initial Hello World entry point
- `CLAUDE.md` – project context and development guidelines

The README describes a possible future application architecture using `app/` and subdirectories such as `api/`, `integrations/`, `services/`, `workflows/`, `agents/`, and `database/`.

Do not create these future directories until the workshop exercises or implemented functionality require them. Revisit the directory conventions when the application architecture is introduced.

Do not implement business logic or generate unnecessary placeholder modules during Week 1.

## Coding Guidelines

- Write clear, beginner-friendly Python code.
- Prefer small functions with descriptive names.
- Use type hints where appropriate.
- Keep the implementation simple and understandable.
- Explain significant changes before making them.
- Implement and test one feature at a time.
- Follow the existing repository conventions.



## Security and Privacy

- Never commit `.env` files, API keys, tokens, or credentials.
- Read secrets from environment variables.
- Use a dedicated test email account during development.
- Request only the permissions needed for each feature.
- Never send emails or modify calendar events without explicit user approval.
- Do not log sensitive email content unnecessarily.



## Development Workflow

1. Review the existing code and `README.md`.
2. Explain the proposed change.
3. Implement the smallest useful change.
4. Run an appropriate test.
5. Report the result and any remaining issues.

Do not implement business logic or create additional project files unless explicitly requested.