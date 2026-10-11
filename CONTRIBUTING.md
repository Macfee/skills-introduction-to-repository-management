# Contributing to the Mergington High Extra-Curricular Activities Website

Thank you for helping improve our school's website! Whether you want to add club activities, fix a bug, or suggest a feature, this guide will help you get started.

## Development Setup

1. Clone the repository and open it in the provided development container, which prepares the dependencies and services.
2. For a local setup, install the requirements with `python -m pip install -r requirements.txt` and ensure MongoDB is running.
3. From the repository root, run `python -m uvicorn src.app:app --reload --port 8000`.
4. Visit http://localhost:8000 in your browser. Use sample data rather than real student information for development.

## Making Changes

1. Create a branch with a descriptive name such as `art-gallery-feature` or `fix-chess-signup`.
2. Make a focused change and test it locally using the included sample data.
3. Push your branch and open a pull request with a description of the change and validation performed.
4. Wait for review and address feedback before merging into the protected default branch.

## Code Style

- Follow PEP 8 for Python code.
- Use clear names such as `student_name` and `start_time`.
- Comment non-obvious logic and keep changes small enough to review.
- Keep credentials, virtual environments, and generated files out of commits.

## Need help or have ideas?

- Search open issues first. Add useful details to an existing issue, or open a new one with reproduction steps and the expected behavior.
- The exercise's fictional IT Club office hours are Thursdays at lunch in Room 203.
- The sample contact is techclub@mergingtonhigh.example.edu; it is an illustrative address for this fictional school.
