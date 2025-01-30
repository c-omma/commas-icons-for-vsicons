*note:* I am using VSCode on Linux, on Installed mode.

# A step-by-step guide
on how to build this from scratch, in the inevitable event that I forget how I did any of it in the first place.

## Installing
1. install **VSCode**!
2. install the **vscode-icons** extension in VSCode. (I just searched for it in the Extensions tab.)

    consider reading the vscode-icons documentation on [github](https://github.com/vscode-icons/vscode-icons) to minimally understand what is going on. Focus on the [Fine tuning](https://github.com/vscode-icons/vscode-icons/wiki/FineTuning) and the [Custom Icons](https://github.com/vscode-icons/vscode-icons/wiki/Custom) pages.

## The icons
1. create a repository for your icon files:

    ```Linux command line
    $ cd /home/<user name>/.config/Code/User
    $ mkdir vsicons-custom-icons
    ``` 
2. create your icons! ;)
3. insert your icons, **correctly named** in the repository you created.

### How to name your files

## The settings
1. open the `settings.json` file.

    ```Linux command line
    $ cd /home/comma/.config/Code/User
    ```
    the file should be here
2. declare all your icons there.

## Don't forget!
Run the command `Icons: Apply Icons Customization` from the Command Palette (`F1`) at will to check if everything is showing up correctly.