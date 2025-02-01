*note:* I am using VSCode on Linux, in Installed mode.

# A step-by-step guide
on how to build this from scratch, in the inevitable event that I forget how I did any of it in the first place.

## Installing
1. Install **VSCode**!
2. Install the **vscode-icons** extension in VSCode. (I just searched for it in the Extensions tab.)

    Consider reading the vscode-icons documentation on [github](https://github.com/vscode-icons/vscode-icons) to understand what is happening minimally. Focus on the [Fine tuning](https://github.com/vscode-icons/vscode-icons/wiki/FineTuning) and the [Custom Icons](https://github.com/vscode-icons/vscode-icons/wiki/Custom) pages.

## The icons
1. Create a directory for your icon files:

    ```Linux command line
    $ cd /home/<user name>/.config/Code/User
    $ mkdir vsicons-custom-icons
    ``` 
2. Create your icons! ;)
3. Insert your icons, **correctly named**, in your created repository.

### How to name your files

as seen in [vscode-icons](https://github.com/vscode-icons/vscode-icons/wiki/Custom):

- Icons for **files**:
    - default icon: `default_icon-name.png`;
    - others: `file_type_icon-name.png`.
- Icons for **folders**:
    - default folder: `default_icon-name.png` *and* `deafult_icon-name-opened.png` (my settings only use default folders);
    - others: `folder_type_icon-name.png` *and* `folder_type_icon-name_opened.png`.

## The settings
1. Open the `settings.json` file in `/home/<user name>/.config/Code/User`;

2. declare all your icons there.

You can copy everything in [the model_settings file](model_settings.json), which also includes some other vsicons features I like to have turned on, like hiding the folders' arrows. If you want to go rogue, follow the same structure, or the official ones for [files](https://github.com/vscode-icons/vscode-icons/blob/master/src/iconsManifest/supportedExtensions.ts) and [folders](https://github.com/vscode-icons/vscode-icons/blob/master/src/iconsManifest/supportedFolders.ts).

## Don't forget!
Run the command `Icons: Apply Icons Customization` from the Command Palette (`F1`) at will to check if everything is showing up correctly.