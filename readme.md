Desktop Cleaner
The Desktop Cleaner is a script that organizes your desktop by sorting files into separate folders based on their file types. It categorizes files into images, documents, media, and other files.

Table of Contents
Installation
Usage

How it Works
Customization
License
Installation
Clone or download the project repository.
Make sure you have Python 3 installed.
Navigate to the project directory using the command line.
Run the script by executing the following command:
bash
Copy code
python main.py
Usage
To run the script, simply execute the main.py file from the terminal in the directory where you want to organize files. It will create the folders (Images, Docs, Media, Others) if they don't exist, and then sort your files accordingly.

How it Works
The script organizes files into the following categories:

Images: Files with extensions .png, .jpg, and .jpeg are moved to the Images folder.
Docs: Files with extensions .txt, .docx, .doc, and .pdf are moved to the Docs folder.
Media: Files with extensions .mp4, .mp3, and .flv are moved to the Media folder.
Others: Any files that do not fall into the above categories and are not directories are moved to the Others folder.
The script uses the os module to create folders if they don't exist and to move files based on their extension.

Customization
You can customize the script to sort other types of files by modifying the file extensions in the lists:

imgExts for images
docExts for documents
mediaExts for media
License
This project is licensed under the MIT License. See the LICENSE file for more information.

