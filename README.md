# Flask To-Do App

A simple To-Do application built using Flask and SQLAlchemy. This app allows users to create, update, and delete tasks.

## Features

- Add new tasks with a title and description.
- View all tasks in a list.
- Update existing tasks.
- Delete tasks.
- Data is stored in a SQLite database.

## Prerequisites

- Python 3.x installed on your system.
- `pip` package manager installed.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/nandkumarcoder/Do-To-App-Using-Flask-.git
   cd Do-To-App-Using-Flask-
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   python app.py
   ```

5. Open your browser and navigate to:
   ```
   http://127.0.0.1:5000/
   ```

## File Structure

- `app.py`: Main application file containing routes and database models.
- `templates/`: Folder containing HTML templates (`index.html`, `update.html`).
- `todo.db`: SQLite database file (created automatically when the app runs).

## Usage

1. Open the app in your browser.
2. Add tasks by filling out the form and submitting.
3. View, update, or delete tasks from the task list.

## Screenshots

_Add screenshots of your app here if available._

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- [Flask Documentation](https://flask.palletsprojects.com/)
- [SQLAlchemy Documentation](https://docs.sqlalchemy.org/)
