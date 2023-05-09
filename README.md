# Templating Titans: Using Jinja2 for Dynamic Web Content

## Description
In this lab, students will learn how to use Jinja2 templates to generate dynamic content for Flask web applications. They will create templates in Flask, pass data to templates using context variables, and handle user requests.

## Instructions

- [ ] Begin by introducing Jinja2 and its benefits to the students.
- [ ] Explain how Jinja2 templates can be used for dynamic content generation in Flask.
- [ ] Have the students create a basic Flask application with the following code:

```
from flask import Flask, render_template

app = Flask(__name__)

@app.route("/")
def home():
    return render_template("home.html", name="World")

if __name__ == "__main__":
    app.run(debug=True)
```

- Explain how to create and use templates in Flask applications.
- Have the students create a new template called home.html that displays a personalized greeting message.
- Explain how to pass data to templates using context variables.
- Have the students pass the user's name as a context variable to the home.html template.
- Explain how to handle user requests in Flask applications and generate responses.
- Have the students create a new route that handles a user input form and generates a response based on the user's input.

