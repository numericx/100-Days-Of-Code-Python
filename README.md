This repository contains the code for the [100 Days of Code: The Complete Python Pro Bootcamp](https://www.udemy.com/course/100-days-of-code/) on Udemy.

| Day | Topic |
|-----|-------|
| 01 | Working with variables in Python to Manage Data |
| 02 | Understanding Data types and How to Manipulate Strings |
| 03 | Control Flow and Logical Operators |
| 04 | Randomisation and Python Lists |
| 05 | Python Loops |
| 06 | Python Functions & Karel |
| 07 | Hangman |
| 08 | Function Parameters & Caesar Cipher |
| 09 | Dictionaries, Nesting and the Secret Auction |
| 10 | Functions with Outputs |
| 11 | The Blackjack Capstone Project |
| 12 | Scope & Number Guessing Game |
| 13 | Debugging |
| 14 | Higher Lower Game Project |
| 15 | Local Development Environment Setup & The Coffee Machine |
| 16 | Object Oriented Programming (OOP) |
| 17 | The Quiz Project & The Benefits of OOP |
| 18 | Turtle & The Graphical User Interface (GUI) |
| 19 | Instances, State and Higher Order Functions |
| 20 | Build the Snake Game Part I - Animation & Coordinates |
| 21 | Build the Snake Game Part II - Inheritance & List Slicing |
| 22 | Build Pong: The Famous Arcade Game |
| 23 | The Turtle Crossing Capstone Project |
| 24 | Files, Directories and Paths |
| 25 | Working with CSV Data and the Pandas Library |
| 26 | List Comprehension and the NATO Alphabet |
| 27 | Tkinter, *args, **kwargs and creating GUI Programs |
| 28 | Tkinter, Dynamic Typing and the Pomodoro GUI Application |
| 29 | Building a Password Manager GUI App with Tkinter |
| 30 | Errors, Exceptions and JSON Data - Improving the Password |
| 31 | Flash Card App Capstone Project |
| 32 | Send Email & Manage Dates |
| 33 | API Endpoints & API Parameters - ISS Overhead Notifier |
| 34 | API Practice - Creating a GUI Quiz App |
| 35 | Keys, Authentication & Environment Variables - Send SMS |
| 36 | Stock Trading News Alert Project |
| 37 | Habit Tracking Project - API Post Requests & Headers |
| 38 | Workout Tracking Using Google Sheets |
| 39 | Capstone Part I - Flight Deal Finder |
| 40 | Capstone Part II - Flight Club |
| 41 | Web Foundation - Introduction to HTML |
| 42 | Web Foundation - Intermediate HTML |
| 43 | Web Foundation - Introduction to CSS |
| 44 | Web Foundation - Intermediate CSS |
| 45 | Web Scraping with Beautiful Soup |
| 46 | Create a Spotify Playlist using the Musical Time Machine |
| 47 | Create an Automated Price Tracker |
| 48 | Selenium Webdriver Browser and Game Playing Bot |
| 49 | Automating your Exercise Routine at the Gym |
| 50 | Auto Tinder Swiping Bot |
| 51 | Internet Speed Twitter Complain Bot |
| 52 | Instagram Follower Bot |
| 53 | Web Scraping Capstone - Data Entry Job Automation |
| 54 | Introduction to Web Development with Flask |
| 55 | HTML & URL Parsing in Flask and the Higher Lower Game |
| 56 | Rendering HTML/Static Files and Using Website Templates |
| 57 | Templating with Jinja in Flask Applications |
| 58 | Web Foundation Bootstrap |
| 59 | Blog Capstone Part II - Adding Styling |
| 60 | Make POST Requests with Flask and HTML Forms |
| 61 | Building Advanced Forms with Flask-WTForms |
| 62 | Flask WTForms, Boostrap and Coffee & Wifi Project |
| 63 | Databases with SQLite and SQLAlchemy |
| 64 | My Top 10 Movies Website |
| 65 | Web Design School - How to Create a Website that People will Love |
| 66 | Building your Own API with RESTful Routing |
| 67 | Blog Capstone Project Part III - RESTful Routing |
| 68 | Authentication with Flask |
| 69 | Blog Capstone Part IV - Adding Users |
| 70 | Git, Github and Version Control |
| 71 | Deploying your Web Application |
| 72 | Data Exploration with Pandas - College Major vs Your Salary |
| 73 | Data Visualization with Matplotlib - Programming Languages |
| 74 | Aggregate & Merge Data with Pandas - Analyse the LEGO Dataset |
| 75 | Google Trends Data - Resampling and Visualising Time Series |
| 76 | Beautiful Plotly Charts & Analysing the Android App Store |
| 77 | Computations with Numpy and N-Dimensional Arrays |
| 78 | Linear Regression and Data Visualisation with Seaborn |
| 79 | Analysing the Nobel Prize with Plotly, Matplotlib & Seaborn |
| 80 | The Tragic Discovery of Handwashing Part I - t-tests & Distributions |
| 81 | Capstone Project - Predicting House Prices |
| 82 | Professional Portfolio Project - Python Scripting |
| 83 | Professional Portfolio Project - Python Web Development |
| 84 | Professional Portfolio Project - Python Scripting |
| 85 | Professional Portfolio Project - GUI |
| 86 | Professional Portfolio Project - GUI |
| 87 | Professional Portfolio Project - Game |
| 88 | Professional Portfolio Project - Web Development |
| 89 | Professional Portfolio Project - Web Development |
| 90 | Professional Portfolio Project - GUI Desktop App |
| 91 | Professional Portfolio Project - HTTP Requests & APIs |
| 92 | Professional Portfolio Project - Image Processing and Data Science |
| 93 | Professional Portfolio Project - Web Scraping |
| 94 | Professional Portfolio Project - GUI Automation |
| 95 | Professional Portfolio Project - Game |
| 96 | Professional Portfolio Project - HTTP Requests & APIs |
| 97 | Professional Portfolio Project - Web Development |
| 98 | Professional Portfolio Project - Python Automation |
| 99 | Professional Portfolio Project - Data Science |
| 100 | Professional Portfolio Project - Data Science |

---

# Opencode Subagents Reference

This project uses **opencode** with 16 specialized subagents. In the OpenCode TUI, invoke them via the **agent selector** (`@` key) or **slash commands**.

## Quick Reference Table

| Agent | Purpose | Best For |
|-------|---------|----------|
| `api` | API endpoints, Pydantic schemas, OpenAPI docs | REST/GraphQL APIs, validation, specs |
| `cicd` | CI/CD pipelines, Dockerfiles, PyPI publishing | GitHub Actions, Docker, releases |
| `db` | SQLAlchemy models, Alembic migrations, query optimization | Database schema, migrations, performance |
| `docs` | MkDocs/Sphinx setup, docstrings, README creation | Documentation sites, API docs |
| `env` | Docker, docker-compose, devcontainers, env vars | Containerization, dev environments |
| `explore` | Codebase exploration, pattern searching, Q&A | Finding files, understanding code |
| `fix` | Bug fixes for logic, syntax, runtime errors | Debugging, error resolution |
| `general` | Multi-step research and complex task execution | Open-ended research, multi-phase tasks |
| `help` | Routes requests to appropriate specialized agent | Triage, agent selection |
| `perf` | Python profiling, bottleneck identification, optimization | Performance tuning, profiling |
| `quality` | Ruff, mypy, pre-commit config, lint/type fixes | Code quality, linting, type checking |
| `refactor` | Extract functions, rename symbols, reduce duplication | Code restructuring, DRY principles |
| `review` | Code review for correctness, style, types, security | PR reviews, security audits |
| `scaffold` | New Python projects: uv init, pyproject.toml, src/ layout | Project initialization, boilerplate |
| `security` | Security audits, dependency vulnerability scanning | Vulnerability assessment, hardening |
| `test` | Pytest setup, test writing, coverage config, deptry | Test suites, coverage, test quality |

---

## TUI Invocation Methods

### Method 1: Agent Selector (Recommended)
Press **`@`** in the input area → type agent name → select → enter your prompt

### Method 2: Slash Command
Type `/agent <name>` followed by your request

### Method 3: Explicit Task Tool
Type `/task` then fill in: agent, description, prompt

---

## Agent Details & TUI Examples

### `api` — API Development Agent
**Use when:** Building REST APIs, GraphQL endpoints, or need OpenAPI documentation

**Capabilities:**
- FastAPI/Flask endpoint design
- Pydantic model generation
- Request/response validation
- OpenAPI/Swagger spec creation

**TUI Example:**
```
@api Design RESTful CRUD endpoints for User resource with Pydantic models and OpenAPI docs
```
Or:
```
/agent api Design RESTful CRUD endpoints for User resource with Pydantic models and OpenAPI docs
```

---

### `cicd` — CI/CD Pipeline Agent
**Use when:** Setting up GitHub Actions, Dockerfiles, or publishing to PyPI

**Capabilities:**
- GitHub Actions workflows
- Multi-stage Dockerfiles
- PyPI release automation
- Matrix testing configurations

**TUI Example:**
```
@cicd Create GitHub Actions workflow for testing on Python 3.10-3.12, building Docker image, and publishing to PyPI on tag push
```

---

### `db` — Database Agent
**Use when:** Working with SQLAlchemy, Alembic migrations, or query optimization

**Capabilities:**
- SQLAlchemy model definitions
- Alembic migration scripts
- Query performance analysis
- Index optimization strategies

**TUI Example:**
```
@db Design SQLAlchemy models for User (id, email, hashed_password) and Post (id, title, content, user_id FK) with Alembic migration
```

---

### `docs` — Documentation Agent
**Use when:** Setting up MkDocs/Sphinx, writing docstrings, or creating README files

**Capabilities:**
- MkDocs Material configuration
- Sphinx project setup
- NumPy/Google docstring generation
- README.md creation

**TUI Example:**
```
@docs Initialize MkDocs Material with API reference from docstrings, add navigation for guides and examples
```

---

### `env` — Environment & Containerization Agent
**Use when:** Creating Dockerfiles, docker-compose, devcontainers, or managing env vars

**Capabilities:**
- Multi-stage Dockerfiles
- docker-compose for local dev
- VS Code devcontainer.json
- .env.example templates

**TUI Example:**
```
@env Create multi-stage Dockerfile for FastAPI app, docker-compose with PostgreSQL and Redis, and devcontainer for VS Code
```

---

### `explore` — Codebase Exploration Agent
**Use when:** Finding files, searching patterns, or understanding unfamiliar code

**Capabilities:**
- Fast glob/grep searches
- Codebase Q&A
- Architecture analysis
- Dependency mapping

**TUI Example:**
```
@explore Locate all authentication-related code: login, JWT tokens, middleware, and protected routes
```

---

### `fix` — Bug Fix Agent
**Use when:** Resolving logic errors, syntax issues, or runtime exceptions

**Capabilities:**
- Exception traceback analysis
- Logic error identification
- Syntax correction
- Test case creation for regressions

**TUI Example:**
```
@fix Investigate and fix ZeroDivisionError in calculate_average() at utils/math.py:42 when input list is empty
```

---

### `general` — General Purpose Agent
**Use when:** Multi-step research, complex open-ended tasks, or orchestrating multiple agents

**Capabilities:**
- Parallel task execution
- Web research + code implementation
- Complex multi-phase workflows
- Decision-making with tradeoffs

**TUI Example:**
```
@general Research Redis vs in-memory caching for our use case, implement chosen solution with fallback, add tests
```

---

### `help` — Agent Router
**Use when:** Unsure which agent to use; routes to appropriate specialist

**Capabilities:**
- Request analysis
- Agent recommendation
- Task decomposition

**TUI Example:**
```
@help I need to add JWT authentication to my FastAPI app with refresh tokens. Which agent should handle this?
```

---

### `perf` — Performance Optimization Agent
**Use when:** Profiling Python code, identifying bottlenecks, or optimizing slow operations

**Capabilities:**
- cProfile/line_profiler analysis
- Memory profiling
- Async optimization
- Database query tuning

**TUI Example:**
```
@perf Profile the get_user_feed() function - it takes 2s+ for 10k users. Identify bottlenecks and optimize
```

---

### `quality` — Code Quality Agent
**Use when:** Configuring Ruff, mypy, pre-commit, or fixing lint/type issues

**Capabilities:**
- Ruff configuration (ruff.toml)
- mypy strict mode setup
- pre-commit hooks
- Auto-fix lint violations

**TUI Example:**
```
@quality Configure Ruff with recommended rules, mypy strict mode, and pre-commit hooks for black, isort, and mypy
```

---

### `refactor` — Refactoring Agent
**Use when:** Extracting functions, renaming symbols, reducing duplication, or restructuring code

**Capabilities:**
- Function/class extraction
- Symbol renaming across files
- DRY principle application
- Design pattern implementation

**TUI Example:**
```
@refactor Extract duplicated validation logic from user.py, post.py, comment.py into shared validators.py module
```

---

### `review` — Code Review Agent
**Use when:** Reviewing PRs for correctness, style, types, security, and architecture

**Capabilities:**
- Correctness verification
- Security vulnerability scanning
- Type safety checking
- Architectural feedback

**TUI Example:**
```
@review Review the authentication changes in PR #234: check for timing attacks, proper token validation, and secure password handling
```

---

### `scaffold` — Project Scaffolding Agent
**Use when:** Creating new Python projects with uv, pyproject.toml, src/ layout

**Capabilities:**
- uv project initialization
- pyproject.toml with modern config
- src/ package layout
- Dependency management setup

**TUI Example:**
```
@scaffold Scaffold a FastAPI project with uv, SQLAlchemy, Pydantic, pytest, and Ruff pre-configured
```

---

### `security` — Security Audit Agent
**Use when:** Auditing code for vulnerabilities, scanning dependencies, or hardening applications

**Capabilities:**
- SAST vulnerability detection
- Dependency scanning (pip-audit, safety)
- OWASP Top 10 checks
- Secrets detection

**TUI Example:**
```
@security Scan all dependencies for known CVEs, check for hardcoded secrets, and review authentication implementation
```

---

### `test` — Testing Agent
**Use when:** Setting up pytest, writing tests, managing coverage, or running deptry

**Capabilities:**
- Pytest configuration
- Unit/integration test writing
- Coverage thresholds
- Test organization patterns

**TUI Example:**
```
@test Write unit tests for UserService.create_user() with fixtures, parametrize edge cases, and achieve 90%+ coverage
```

---

## Quick Tips

| Action | Keybinding / Command |
|--------|---------------------|
| Open agent selector | `@` |
| List all agents | `@` then type to filter |
| Slash command | `/agent <name> <prompt>` |
| Explicit task form | `/task` |
| View agent help | `/agent help` or `@help` |

**Pro tip:** Start with `@help` if you're unsure which agent fits your task.
