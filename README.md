# Email Client Front-end

## Demonstration
Watch the [YouTube video](https://youtu.be/kl9StSXaxj4) to see the application in action.

## Project Overview
Design a front-end for an email client that makes API calls to send and receive emails. The application is a single-page app that allows users to manage their emails, including composing, sending, viewing, replying, archiving, and unarchiving.

### Features
- **Send Mail**: Compose and send emails using the provided form.
- **Mailbox**: View inbox, sent, and archived emails. Emails are displayed with sender, subject, and timestamp. Unread emails have a white background, while read emails have a gray background.
- **View Email**: Click on an email to view its content. Mark the email as read upon viewing.
- **Archive and Unarchive**: Archive and unarchive received emails. Viewing an Inbox email provides an archive button, and viewing an Archive email provides an unarchive button.
- **Reply**: Reply to an email. The reply button pre-fills the composition form with the recipient, subject, and original email content.
  
## Getting Started

### Prerequisites
- Python 3.x
- Django 2.x or 3.x

### Installation
1. Clone the project
2. Open a terminal and navigate to the `mail` directory.
3. Run the following commands to set up the application:
   ```sh
   python manage.py makemigrations mail
   python manage.py migrate
   ```
4. Start the Django development server:
   ```sh
   python manage.py runserver
   ```
5. Open a web browser and go to `http://127.0.0.1:8000` to access the application.

## Usage
- **Compose Email**: Click the "Compose" button to create and send a new email.
- **View Mailbox**: Navigate between the Inbox, Sent, and Archive mailboxes.
- **View Email**: Click on an email to view its content. Mark the email as read.
- **Archive/Unarchive**: Archive or unarchive an email based on the mailbox being viewed.
- **Reply**: Click the "Reply" button to reply to an email. The composition form is pre-filled with relevant details.


## License
Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgments
- Harvard University's CS50 course for the project idea and initial guidelines.
- Django and JavaScript communities for their support and resources.
