# ChatElephant
A multi-room, secure, PHP-based chat service useful for shared hosting scenarios

_Currently in Planning_

Goals:

* Is designed for the protection of free speech interaction.
* Is designed to work in most PHP Linux Shared Hosting plans.
* KISS Methodology
* Uses the [PHP Painless Framework](https://github.com/volomike/painless) so that it is easy to comprehend and extend, and supports a potential plugin framework.
* Uses an MIT License so that others can fork and extend, make hassle-free commercial and free variations, etc.
* Will use a JSON interface in its service. This permits developers to build their own front-end clients with it.
* Can be accessed with a companion responsive design chat application via jQuery/AJAX called [Mowgli](https://github.com/volomike/Mowgli) (which chats with elephants). Developers can utilize that or build their own to interface with the JSON service.
* Tries to be very secure.
* Is easy to install. Simply unzip the project into a folder, connect to the index.php, and it will walk you through the setup scenario, build the configuration, and connect to your MySQL/MariaDB.
* The super user role builds the chatrooms and has full power.
* The moderator role can manage chatrooms.
* The user role can register, join a chatroom, chat, and moderate undesirable stuff in chats such as 1:1 conversations, noisy chats that need muting, etc.
* Some chatrooms are invite only with a special link and are not publicly visible.
* Some chatrooms are publicly posted but must be applied for and a moderator can add.
* Some chatrooms are publicly posted and anyone can join.
* Users can chat 1:1 privately with each other.
* Chatrooms only store 500 responses. Beyond that, they pop the top response off the array (scrolling responses).
* Users can delete their own chat messages at any time with no sign that the message was there.
* Messages can only be 500 characters long. Messages are simple, support no formatting, and code can be shared via this system.
* Messages can support attachments up to a certain size if moderators permit this in a given chat room. These attachments will be removed once the message for them scrolls out of view. Acceptable attachment types are jpg, png, gif, zip, txt, and pdf only. Images will be thumbnailed. Animated gifs will automatically display without thumbnail if they are under 600x300 in size.
* Users must create a unique username alias, use the default avatar, or create a new one. Users can optionally post their true name that other users can see if they click the avatar.






