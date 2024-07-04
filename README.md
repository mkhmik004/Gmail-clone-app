# Mail Client - GMail clone Django project

This project is a single-page application (SPA) email client built with Django, JavaScript, HTML, and CSS. The application allows users to send, receive, and manage emails within a simulated environment. All emails are stored in the database and are not sent to real email servers.

## Features

1. **User Registration and Authentication**: Users can register and log in to access their mail client.
2. **Compose Email**: Users can compose and send new emails.
3. **Inbox**: Users can view received emails in their inbox.
4. **Sent Mailbox**: Users can view emails they have sent.
5. **Archive**: Users can archive emails from their inbox and unarchive them.
6. **View Email**: Users can view the contents of an email.
7. **Reply to Email**: Users can reply to received emails.

## API Routes

The application provides the following API routes for interacting with emails:

- **GET /emails/<str:mailbox>**: Retrieve all emails in a specified mailbox (inbox, sent, archive).
- **GET /emails/<int:email_id>**: Retrieve details of a single email by its ID.
- **POST /emails**: Send a new email.
- **PUT /emails/<int:email_id>**: Update an email's read/unread or archived/unarchived status.

## Getting Started

### Prerequisites

- Python 3.10
- Django 3

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/mail-client.git
   cd mail-client

