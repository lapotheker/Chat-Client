# Chat Client
## A full-featured messaging application built with JavaFX featuring server selection, user authentication, and real-time chat room functionality.
### Features
* **User Authentication** : Secure login system with username/password validation
* **Server Selection** : Connect to multiple chat servers with dynamic server discovery
* **Real-time Messaging** : Instant message delivery and receipt across chat rooms
* **Scene-Based Navigation** : Transitions between login, server selection, and chat interfaces
* **Custom Theming** : Multiple CSS themes including Cupertino Dark for personalized UI experience
* **Multi-threaded Communication** : Non-blocking TCP/IP socket connections for responsive UI
#### Build the project
javac --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml -d bin src/chatclient/*.java src/chatclient/scenes/*.java
#### Run the projecct
java --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml -cp bin chatclient.App

