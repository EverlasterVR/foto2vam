# foto2vam
Software by ChrisTopherTa54321. This is just a fork without code changes.

Readme adapted from the reddit post https://www.reddit.com/r/VAMscenes/comments/8knjb5/foto2vam_vam_models_from_photographs/ by the original author.

## Installation

1. clone/download this repo

2. Download and install python 3.6 - https://www.python.org/downloads/release/python-365/

In the first window, click "Install launcher for all users" and "Add Python 3.6 to PATH", then click "Install Now".

3. download and install Visual Studio 2015 Community Edition (required for Python to build dependencies) https://go.microsoft.com/fwlink/?LinkId=532606&clcid=0x409

- open a command prompt as an administrator and navigate to this dir
- install the dependencies:

    pip install -r requirements.txt

It might be pip3, not pip.

4. download the required models/ dir from https://mega.nz/file/hBcQlLqI#0g1vgpxeGftzlFH6Ez_hSLULzT01Sd1VtXEe1avbxtk and extract to this dir

## Usage

You need two files images in the Input directory:

`facename_angle0.png`
`facename_angle35.png`

The facename can be anything.

The angle0 file must be a forward facing photo with a neutral expression on their face.

The angle35 file 

The files must end in .png but if they're .jpg you can just change the extension.

Finally run in a command prompt:

    python foto2vam.py

You can also double click the foto2vam.py in Windows Explorer.

