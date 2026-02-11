# aiogram3_stepik_course

This repository contains practical examples and mini-projects built while studying **aiogram 3** (Telegram Bot framework for Python).

It includes multiple standalone bots and feature demonstrations covering core Telegram Bot API concepts, middleware, FSM, callback queries, inline buttons, logging, and modular architecture.

---

## Overview

The project serves as a hands-on learning collection for:

- Building Telegram bots with **aiogram v3**
- Understanding bot architecture and modular design
- Working with FSM (Finite State Machine)
- Implementing inline and reply buttons
- Handling callback queries
- Middleware usage
- Logging configuration
- Polling and server-based deployment

---

## Included Examples

The repository contains multiple subprojects and examples, including:

- Echo bot
- Modular echo bot
- Book bot
- Shop bot
- Rock-paper-scissors bot
- Guess the number bot
- Text quest bot
- Database echo bot
- Inline and reply button examples
- Callback data factory usage
- FSM examples
- Middleware examples
- Logging configuration examples
- APScheduler experiments
- Formatting and HTML examples

Each directory typically represents an independent bot or focused example.

---

## Requirements

- Python 3.10+
- aiogram 3.x
- Other dependencies listed in `requirements.txt`

Install dependencies:

```bash
pip install -r requirements.txt
```

Or if using `pyproject.toml`:

```bash
pip install .
```

---

## Configuration

Create a `.env` file or export your bot token:

```bash
export BOT_TOKEN=your_telegram_bot_token
```

Never commit your real bot token to version control.

---

## Running an Example

Navigate to the desired example directory and run:

```bash
python main.py
```

Some examples may use polling; others may demonstrate server-based setups.

---

## Learning Goals

This repository is intended to help with:

- Understanding aiogram 3 architecture
- Practicing async programming in Python
- Implementing real-world Telegram bot features
- Exploring modular bot design patterns

---
