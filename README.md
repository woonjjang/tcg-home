## Just a few more steps and you're ready to go:

1. Download a theme into the same-named folder.
   Choose a theme from https://themes.gohugo.io/ or
   create your own with the "hugo new theme <THEMENAME>" command.
2. Perhaps you want to add some content. You can add single files
   with "hugo new <SECTIONNAME>/<FILENAME>.<FORMAT>".
3. Start the built-in live server via "hugo server".

## Installation 
Before starting, please be sure that you have installed Hugo and created a new site. After that, you ready to install Mainroad.

In your Hugo site themes directory, run:

```git clone https://github.com/vimux/mainroad```

Or, if you don’t plan to make any significant changes, but want to track and update the theme, you can add it as a git submodule via the following command:

```git submodule add https://github.com/vimux/mainroad```
Next, open config.toml in the base of the Hugo site and ensure the theme option is set to mainroad:

```theme = "mainroad"``
For more information read the official setup guide of Hugo.
