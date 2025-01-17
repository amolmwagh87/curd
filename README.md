

## Project Structure

```
crud_project/
├── app/
│   ├── __init__.py
│   ├── models.py
│   ├── routes.py
├── static/
│   ├── main.js
├── templates/
│   ├── index.html
├── config.py
├── run.py
├── requirements.txt

```

# CRUDify

CRUDify is a simple web application that allows users to perform basic CRUD (Create, Read, Update, Delete) operations without requiring a page refresh. This application is built using Flask, SQLAlchemy, AJAX, and MySQL.

## Features

- **Create**: Add new contacts with Name, Email, and Phone fields.
- **Read**: View a list of all contacts stored in the database.
- **Update**: Modify existing contact details (implementation can be added).
- **Delete**: Remove contacts from the list.
- **AJAX Integration**: Submit forms and retrieve data without refreshing the page.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript (with jQuery)
- **Backend**: Python, Flask
- **Database**: MySQL
- **ORM**: SQLAlchemy

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/crudify.git
   cd crudify
   ```

2. **Set up a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages**:
   ```bash
   pip install -r requirement.txt
   ```

4. **Set up MySQL Database**:
   - Create a database named `crud_db` in your MySQL server.
   - Update the database connection string in `config.py`:
     ```python
     SQLALCHEMY_DATABASE_URI = 'mysql://root:root@localhost/crud_db'
     ```

5. **Run the application**:
   ```bash
   python run.py
   ```

6. **Access the application**:
   Open your web browser and navigate to `http://127.0.0.1:5000/`.

## Usage

1. Fill out the form with Name, Email, and Phone.
2. Click "Add Contact" to submit the form.
3. The contact will be added to the list displayed below the form.
4. Click "Delete" next to a contact to remove it from the list.

## Client-side Validation

Ensure that all fields are filled out correctly before submission. The client-side validation is implemented using JavaScript.

## Future Enhancements

- Implement an **Update** feature for modifying contact details.
- Add functionality for the contact list.
- only create time validation done.


#   s a m p l e _ p r o j e c t  
 