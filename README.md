# FlyWrite – simple notepad for Linux

FlyWrite is a terminal-based text editor with a black and gold color scheme. It allows you to create simple text files quickly without leaving the command line.

## Installation

If you have the .deb package, install it with:

sudo dpkg -i flywrite_1.0.0_all.deb

Alternatively, you can run the script directly:

git clone https://github.com/Eldar52/flywrite.git
cd flywrite
chmod +x flywrite
./flywrite

## How to use

1. Create a folder for your text file if you want to keep it organized:

mkdir -p /home/your_username/your_location

Replace your_username and your_location with your actual path.

2. Navigate to that folder:

cd /home/your_username/your_location

3. Launch FlyWrite by typing:

flywrite

4. Follow the instructions shown in the terminal:

   - Enter a file name when asked
   - Type your text content
   - When you are finished, type "end" on a new line to save and exit

The file will be saved in the folder where you ran FlyWrite.

## Example

cd /home/eldar/Documents
flywrite

File name: notes.txt
Enter text (type 'end' to finish):
Buy milk
Call mom
Finish project
end

The file notes.txt will be created in /home/eldar/Documents.

## Uninstall

If you installed via .deb package, run:

sudo dpkg -r flywrite

If you installed from source, simply delete the flywrite folder.

## License

This project is licensed under the GNU General Public License v3.0.

## Author

Eldar52

## Final note

Why? Because this is a nothing. Nothing.
