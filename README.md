![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# The Flask Framework

Welcome to my first Flask Project.

In this project, I learn how Flask, a Python Framework, is used for web development. By following the video lessons provided by the Code Institute learning platform, I was able to create a basic fan page website for Thorin & Company, character's from Lord of The Rings.

👉[Quick Preview](https://thorin-first-flask-app.herokuapp.com/)
 
## UX
 
The website was built for Lord of The Rings' fans that are particularly interested in learning more about Thorin and his companions. The site provides background of each character in the group to satisfy the curiousity of the users.

## Features

The following are the features of the website:

    - About Page - displays some information about each character in Thorin's group.
        - The heading of each character redirects the user's to the member profile of the selected character 
    - Home Page - introduces the user to some featured articles of the websites
    - Contact Page - allows for user's to be  able to submit request to the site owners.

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Clean Blog - Bootstrap theme](https://startbootstrap.com/theme/clean-blog)
    - The project uses **Clean Blog** [startboorstrap](https://startbootstrap.com/) to build the basic structure of the website.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.

- [Python](https://startbootstrap.com/)
    - The project uses **Python** to insert server based logic/functionality.

- [Flask](https://flask.palletsprojects.com/en/1.1.x/)
    - The project uses **Flask** speed up the web development by serving HTML files from the backend and processing python logic integrated.


## Testing

The jinja template engine automates the testing of the scripts in the project to detect errors included in the project any time the page is reloaded.

### Manual Testing

1. Contact form:
    1. Go to the "Contact" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
        - Not addressed yet - no validation added
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Submitting the form should send feedback to users to let them know it has been successfully sent.

## Deployment

The project files has been uploaded to Github and deployed live on [Heroku](https://thorin-first-flask-app.herokuapp.com/).

## Credits

### Content
- The contents for this projects was provided by Code Institute with Tim Nelson leading the lessons.

### Acknowledgements

- I am grateful for the guidance I received in from building my first Flask project to deployment on Heroku.

