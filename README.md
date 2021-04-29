<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h1 align="center">🎵🎙 Media Server 🎙🎵</h1>
</p>

#### USYD ISYS2120 Assignment 3

The media server contains a flask app and sample data to mimic users, songs, playlists, etc. 

Below is a snapshot of the login page:
![login_page](/readme_imgs/login.PNG)

Task
----------------
The media server is designed to keep track of files and metadata information regarding
various audio and video media.
There are various consumable media:

• Movies

• TV Shows (which have TV Episodes)

• Songs (which are performed by Artists and appear in Albums)

• Podcasts (which have Podcast Episodes)

There is also some User Account information which contains information about the user
including:

• Contact Methods

• Username / password

• Subscribed podcasts

• Consumed media

The database connected is stored on The University of Sydney's server, however, you can change it to any host by specifing in the `database.py` file.

Running the server
----------------

To run this server, edit the `config.ini`, and specifiy your database host, it's possible to just use localhost.

Next specifiy the port number and host `main.py` and run using `python3 main.py`.

To login use a dummy user:

username = james.smith

password = 2KK8oykkvp
