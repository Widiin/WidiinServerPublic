## Welcome to Wiidin Server

The modem status and the maintenance functions are accessible via the https://widiin.com site.
Every modem is connected to the Widiin server via the mobile network. 

*	The modem to server connection is encrypted and protected by individual encryption key. 
    The Modem keys are signed by the server key during the production time. Protocol: OpenVPN. 

*	The client to server connection is also encrypted. Protocol: https. The server’s key is signed. 


## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
