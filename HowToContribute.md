# Introduction #

It's not hard to help if you're a creative person. Anyone can submit ideas for consideration, or report bugs found in the software. If you're a programmer, you can also help submit patches, add features, and make code reviews to help the project.


# Non-programming #

If you have an idea about how WWW Helper can be improved, feel free to contact us. Just click the "Issues" tab above, select "Feature request" from the issue menu, and start describing your feature. We accept and benefit from all feedback, so don't hesitate to file an issue!

If you find a defect in the software, you can do that too. Just file an issue, but select "Defect report" instead of "Feature request" and you're good to go!

# Programming #
This section will describe in-depth how to use Subversion to commit and review changes. This program uses Windows for example. Only members can do this.

## Subversion ##
### Basic terms: ###
  * working copy - a copy of the code downloaded to your computer.
  * checkout - to download a working copy.
  * commit - to upload your changes to your working copy to the server.

### Your first checkout ###
  * Download and install the latest copy of algazam's binary of Subversion at http://sourceforge.net/projects/win32svn/ (other libraries at http://subversion.apache.org/packages.html).
  * Create a new folder on your computer to store your files, anywhere. All files will be downloaded to **another** folder inside named "svn".
  * Open the command-line prompt on your computer. The easiest way to do so is by pressing (WinKey)+R, and typing 'cmd'.
  * Type `cd (your folder here)`.
  * Type `svn checkout https://www-helper.googlecode.com/svn --username (your e-mail here)` to get a working copy. You cannot use Ctrl+V, so it's a pain to type.
  * When prompted, enter the password found at https://code.google.com/hosting/settings. IF you get it wrong, you will be prompted for your username and password again.
  * If everything works well, you'll see the message `Checked out revision (blank)`.
  * You've finally checked out your first working copy! You can change the folder name and location, but don't change anything yet.
  * Keep your command line open and run `cd (folder location of the folder that used to be called svn)`. If you restart your computer, just run that again.

### Editing code ###
  * To edit code, just locate your folder and open the `/trunk` directory and there is all your code! You can edit it freely without yet uploading it.