# Ktor Task Manager (Requests and Responses)

Implements the tutorial tasks from Ktor 3.3.0: handling GET/POST, extracting parameters, error handling, and unit tests.

- Tutorial: [Ktor Requests and Responses](https://ktor.io/docs/server-requests-and-responses.html)

## Endpoints

- `GET /tasks` — HTML table of all tasks
- `GET /tasks/byPriority/{priority}` — filter tasks by priority (`Low|Medium|High|Vital`)
- `GET /tasks/byName/{taskName}` — find task by name
- `POST /tasks` — create a new task (form urlencoded: `name`, `description`, `priority`)
- Static UI: `GET /task-ui/task-form.html`

## Run locally

PowerShell on Windows:

```bash
./gradlew.bat run
```

Then open:

- http://localhost:8080/tasks
- http://localhost:8080/tasks/byPriority/Medium
- http://localhost:8080/task-ui/task-form.html

## Tests

```bash
./gradlew.bat test
```

## Screenshots

Place screenshots of each step in `docs/screenshots/` and link them below:

- `docs/screenshots/01-static-tasks.png`
- `docs/screenshots/02-all-tasks.png`
- `docs/screenshots/03-by-priority.png`
- `docs/screenshots/04-form.png`
- `docs/screenshots/05-post-success.png`

## GitHub

Repository URL: https://github.com/Kmanill/kotik-7


