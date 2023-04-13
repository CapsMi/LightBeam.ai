# LightBeam.ai
This is for submission of assignment as part of Internship application process.

problem statement - 
1. Come up with a config (Data Structure) and load a new
directory tree from config.
2. Write a program that does flowing operations on a
directory tree.
a. Add a new folder at a particular path in the
directory tree.
b. Removed a folder from a particular path in the
directory tree.
c. Fetch the path of the given folder.
d. Update name of the folder.


config.json file consists of folder structure.

The code consists of below functions -

def add_folder(tree, path, folder_id, name)
    This function takes folder structure (tree) and adds the folder under parent directory (path),folder_id, name
    as arguments
    .
    The test case considered are -
            1. The folder with name (name) already exists.
            2. Path of parent folder is invalid


def remove_folder(tree, path, name)
    This function takes folder structure (tree) and adds the folder under parent directory (path), name
    as arguments

    The test case considered are -
            1. The folder with name (name) does not exist.


def fetch_folder_path(tree, folder_id)
    This function takes folder structure (tree) and folder_id as arguments

    The test case considered are -
            1. The folder_id does not exist.


def update_folder_name(tree, folder_id, new_name)
    This function takes folder structure (tree), folder_id and new_name as arguments

    The test case considered are -
            1. The folder with name (name) does not exist.
