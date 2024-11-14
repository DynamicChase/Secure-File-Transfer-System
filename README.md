## Secure File Transfer System

### Description
The **Secure File Transfer System** is a web application designed to facilitate secure file uploads and downloads. It employs encryption techniques to protect sensitive data during transmission, ensuring that only authorized users can access the files. The application is built using Flask and provides a user-friendly interface for file handling.

### Key Features
- **File Upload**: Users can upload files securely through a web interface.
- **Encryption**: Each uploaded file is encrypted using a unique key generated for each transaction, enhancing security.
- **Decryption**: Users can decrypt their files by providing the correct encryption key.
- **User-Friendly Interface**: The application includes HTML templates for easy navigation and interaction.

### Folder Structure
```
/project-root
│
├── Data/
│   └── Secret.key          # Key used for encryption and decryption.
│
├── Result/                 # Directory for storing processed files.
│
├── src/                    # Contains the main application code.
│   ├── client.py           # Client-side logic for file operations.
│   ├── encryption.py       # Functions for encrypting and decrypting data.
│   ├── file_handle.py      # Handles file operations such as saving and retrieving files.
│   ├── generate_key.py     # Generates encryption keys.
│   ├── key_manager.py      # Manages encryption keys securely.
│   └── server.py           # Server-side logic to handle requests.
│
├── statics/                # Static files like CSS stylesheets.
│   └── style.css           # Stylesheet for the web application.
│
├── Template/               # HTML templates for the web interface.
│   ├── decrypt.html        # Page for decrypting files.
│   ├── index.html          # Main landing page of the application.
│   ├── response.html       # Page displaying responses after file operations.
│   └── upload.html         # Page for uploading files securely.
│
└── app.py                  # Main entry point of the application that starts the Flask server.
```

### Installation Instructions
1. Clone the repository:
   ```
   git clone https://github.com/DynamicChase/Secure-File-Transfer-System.git
   ```

2. Navigate to the project directory:
   ```
   cd Secure-File-Transfer-System
   ```

3. Install required dependencies (if specified):
   ```
   pip install -r requirements.txt
   ```

4. Run the application:
   ```
   python app.py
   ```

### Usage
- Access the application by navigating to `http://localhost:5000` in your web browser.

### Contributing
Contributions are welcome! Feel free to open issues or submit pull requests for enhancements or bug fixes.

### License
This project is licensed under the MIT License.

This description provides a clear overview of your project, its structure, and how to use it, making it easier for others to understand and contribute.

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/30473232/dd088b6a-22f0-436b-8db9-481acb789c97/app.py
[2] https://github.com/DynamicChase/Secure-File-Transfer-System
