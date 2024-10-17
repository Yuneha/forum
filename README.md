# FORUM

Forum is a cursus project from Zone01. This project is a forum that display posts. If you're a guest, you can only see posts and comments. For a logged user, you can create a post, comment posts and like/dislike a post or comment. You can filter the posts by categories. A user can see is profile in the profile page.

You can register/log in via Google or Github.

There is different role in the forum, Guest, User(logged user), Moderator and Aministrator.

- User can request to be promote as moderator. And a Moderator can be demote to User.
- Moderator or Admin can report/delete a post. A report post is in a report list that the admin can check.
- Admin have access to an admin panel in the profile page. Admin can accept or decline a request to be a Mod and see all the reported post.

You can create a post or a comment with an image.

## Prerequisites

- A web browser (ex: Google Chrome, FireFox, ...)
- A code editor (ex: vscode, ...)
- A terminal (ex: powershell, wsl, ...)

## Technologies Used

- Golang version 1.18 or higher ([go](https://go.dev/))
- HTML and CSS

## Installation

Open the folder with your code editor.

## Usage

1.  On a Terminal

    1.  If you are not in the forum folder, navigate to **../forum** using **cd** command

            cd forum

    2.  Use this command line to run the program :

            go run .

2.  Go to **[http://localhost:8080](http://localhost:8080)** on your browser.

## License

Distributed under the MIT License. See **LICENSE.txt** for more information.
