# Study Hub
#### Video Demo:https://youtu.be/m7MGDL9XsK8
#### Description:

**Study Hub** is a simple yet powerful web-based notes management application built using Flask, SQLite, HTML, CSS, and Bootstrap 5.

Study Hub allows users to:
- Add new study notes with a title and detailed content.
- View all saved notes organized in a beautiful card layout.
- Edit existing notes easily.
- Delete notes (with a confirmation to prevent mistakes).
- Search through notes by title using the search bar.
- Enjoy a responsive and user-friendly interface on both desktop and mobile devices.

## Project Files:
- `app.py`: The main Flask application handling all routing, database interactions, and template rendering.
- `templates/layout.html`: Base layout that other pages extend. It includes the navigation bar, search functionality, and footer.
- `templates/index.html`: Main page for adding, viewing, and managing notes.
- `templates/edit.html`: Edit page where users can modify existing notes.
- `static/style.css`: Custom styles applied on top of Bootstrap for better aesthetics.
- `notes.db`: SQLite database file (automatically generated when running the app for the first time).

## Design Choices:
- **Bootstrap 5** was used for styling and responsive layout, ensuring a modern and clean design.
- The application uses **Flask’s Jinja2 templating** to organize HTML efficiently with template inheritance (`layout.html` as the base).
- **SQLite** was chosen for simple, file-based database management.
- **Confirmation pop-up** when deleting a note to avoid accidental deletions.
- **Search functionality** for easy and fast retrieval of notes based on titles.
- Custom **CSS** was added to polish the visual experience further.

## Technologies Used:
- Python 3
- Flask
- SQLite3
- HTML5
- CSS3
- Bootstrap 5


---

## 📌 How It Works

1. Run `app.py` to start the Flask server.
2. The app automatically creates a `notes.db` database on the first run.
3. Navigate to `http://localhost:5000` in your browser.
4. Add, view, edit, or delete notes directly in the interface.

---

## 💡 Design Decisions

- **Bootstrap 5** for clean styling and responsive layout.
- **Jinja2 Templates** for maintainable and modular HTML.
- **Confirmation Prompts** before deletion to prevent data loss.
- **Custom CSS** enhancements for a better UI/UX.

---

## 🙋‍♂️ Author

Developed by [Your Name] as part of my CS50x learning journey.

---

## 📃 License

This project is open-source and free to use under the MIT License.




---

This project, **Study Hub**, demonstrates a real-world CRUD (Create, Read, Update, Delete) web application. It was developed fully by me, following the skills and knowledge learned through CS50x.

I hope **Study Hub** can be a small but meaningful contribution towards making study organization easier!
