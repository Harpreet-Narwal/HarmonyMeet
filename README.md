# Omegle Clone using WebRTC (p2p)

This project is an Omegle clone built using WebRTC (peer-to-peer) technology. It allows users to anonymously chat with each other in real-time without the need for a server intermediary.

## Features

- **Peer-to-Peer Communication**: Utilizes WebRTC for establishing direct connections between users.
- **Anonymous Chatting**: Users can engage in anonymous conversations with strangers.
- **Text-based Communication**: Supports text-based chatting between users.
- **Minimalistic Interface**: Simple and intuitive user interface for ease of use.

## Setup

1. Clone the repository:

    ```
    git clone https://github.com/your-username/omegle-clone.git
    ```

2. Navigate to the project directory:

    ```
    cd omegle-clone
    ```

3. Serve the files using a local server. You can use Python's built-in HTTP server:

    ```
    python3 -m http.server
    ```

4. Open your web browser and go to `http://localhost:8000` to access the application.

## Usage

1. Once the application is opened in the browser, you will be prompted to allow access to your camera and microphone.
2. After granting permissions, you will be connected to a random stranger.
3. Start typing your messages in the chat box and hit enter to send.
4. Enjoy chatting with strangers anonymously!
5. To disconnect from the current chat, simply close the browser tab or click on a "Disconnect" button if provided.

## Dependencies

- **WebRTC**: WebRTC is a free, open-source project that provides web browsers and mobile applications with real-time communication via simple application programming interfaces (APIs). It allows audio and video communication to work inside web pages by allowing direct peer-to-peer communication.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify it for your own purposes.
