# ClassChat - Your Online Discussion Platform

ClassChat is a web application built with Django and PostgreSQL that allows users to create and join channels to discuss various topics in a chat-based environment. Similar to Discord, ClassChat provides a platform for users to engage in conversations, share ideas, and connect with others who share similar interests.

![preview](https://github.com/Jayzeen/class_chat_backend/assets/63718579/cb3ff717-f3b5-40da-9a06-d437fa7a1839)
[Demo website](https://classchat-jayzeen.vercel.app/) 

## Features

- **User Authentication**: Secure user registration and authentication system.
- **Channel Creation**: Users can create channels for different topics or interests.
- **Real-time Chat**: Real-time messaging for instant communication.
- **Join Channels**: Users can join and participate in existing channels.
- **User Profiles**: Profiles with customizable avatars and user information.
- **Responsive Design**: User-friendly interface accessible on various devices.

## Getting Started

These instructions will help you set up a local development environment and run ClassChat on your machine.

### Prerequisites

- Python (3.7+)
- PostgreSQL
- Django (3.0+)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/ClassChat.git
   ```

2. Create a virtual environment

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install project dependencies

    ```bash
    pip install -r requirements.txt
    ```

4. Create a PostgresSQL database and configure database settings accordingly in **settings.py**

5. Apply Database Migrations

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```
6. Start the Development Server

    ```bash
    python manage.py runserver
    ```

## Usage

- Register or log in to your account.
- Explore existing channels or create your own.
- Join channels to participate in discussions.
- Use the chat feature to send and receive messages in real-time.
- Customize your profile and avatar.


## Acknowledgments

- Special thanks to the Django and PostgreSQL communities for their excellent documentation and open-source contributions.
- Special thanks to [Dennis Ivy](https://github.com/divanov11) for his amazing tutorial that inspired and helped me in the development of ClassChat.


## Contact

If you have any questions, suggestions, or need assistance, please contact me at [jayzjj7@gmail.com](mailto:jayzjj7@gmail.com).



