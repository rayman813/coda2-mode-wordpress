Coda 2 - Wordpress Custom Syntax Mode
==================================

This repository contains a custom syntax mode for Wordpress in Coda 2. The mode includes the following:
* HTML/PHP syntax highlighting
* Wordpress code completion
* A snippet clip set for Wordpress queries

Installation
------------
To install this mode you must navigate to the Coda 2 install directory and copy the .mode file into the Modes folder.

Open Terminal and run the following command:

    cd ~/Library/Application\ Support/Coda\ 2/

Then, to open the directory in Finder enter this command:

    open .

When Finder opens, you will see multiple folders. Drag WordPress.mode into the Modes folder. 

If you would like to use the WordPress clips you can also add them here by dragging the WordPress.clips file into the Clips directory.

Clip Instructions
-----------------

Clips are default functionality within Coda. I have created a few snippets to help speed up the development process. To use a clip simply type the clip shortcode and **press [TAB]**. You can also open the clips sidebar from Window > Clips and drag a clip to the document.

|Clip Shortcode|Output|
|--------------|------|
| wpq | Creates a standard WP_Query with argument placeholders and starter loop |
| wpql | Creates a standard WP_Query loop |
| wpgp | Same as **wpq** except using get_posts() and foreach loop |
| wpgpl | Creates a standard get_posts() loop |
| wpmq | Creates the arguments for a complex meta query |
