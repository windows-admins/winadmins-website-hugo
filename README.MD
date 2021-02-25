# What is this?

These files are the core Hugo files for the WinAdmins public website.  When uploaded to GitHub, these files are read and converted into static HTML files and hosted through GitHub Pages.

# Can I update the website?

Yes!  We do not limit website management to any single administrator or person.  All members of the WinAdmins community are welcome to update this site.  All changes are reviewed and approved by a member of the administrators team to ensure that they meet our guidelines.

## Updating the Website - Forking the Repository

The first thing you'll need to do to update the website is to fork the repository into your own GitHub account.  This creates a copy of the site in your account that you can play with.

- Login to GitHub.com (create an account if you don't have one already)
- Visit https://github.com/windows-admins/winadmins-website-hugo
- Click the "Fork" button in the upper-right corner and follow the prompts

## Updating the Website - On GitHub Website

For minor updates, you can make all of your changes right in the forked repository you created in the previous step.

In your fork (which will be at https://github.com/<yourusername>/winadmins-website-hugo), select the file you'd like to open and then click the edit button (a picture of a pencil) to make the changes.  There is more information below on where each file resides.

Once complete, add in a title and optional description of your change and select "Create a new branch for this commit and start a pull request".  Click "Propose Changes".

That's it, we'll now get a request for your update and either incorporate it into the site, ask for some modifications, or let you know why we can't use your changes at this time.

## Updating the Website - Local Hugo/Git Installation

The steps involved in setting up a Git client are beyond the scope of this README.  Once you have that setup, use the below steps to setup a local copy of the page for updating.

These instructions assume you're making these changes from a Windows client when referencing Hugo, adjust as needed for alternative Operating Systems.

1. From your Git client, clone your fork of the WinAdmins-Website-Hugo repo using a command such as `git clone https://github.com/<yourusername>/winadmins-website-hugo`
2. Download Hugo from [here](https://github.com/gohugoio/hugo/releases).  Place the Hugo.exe into the new repository folder or into a path easily referenced.
3. Start the webserver by running `hugo server` from within the repository (you may need to specify a path to Hugo.exe if you haven't put it inside the same folder)
4. Browse the website by visiting http://localhost:1313/ (default path).
5. Make necessary changes
6. Stop the webserver, commit your changes using Git, and push to your fork.
7. Navigate to your fork of the website within GitHub (https://github.com/<yourusername>/winadmins-website-hugo) and select the option to submit a Pull Request.

That's it, we'll now get a request for your update and either incorporate it into the site, ask for some modifications, or let you know why we can't use your changes at this time.

# Web Server Files

Please note the following about the structure of our website files:

- All main content will be in the `content` folder.
- Configurations and menu options are in the `config.toml` file.
- We use a public theme `hello-friend-ng` that we do not modify.  Requests to modify any files in that folder will be denied. If there is a theme bug, please notify us or the author.
- Overrides to CSS can be made in the `static/overrides.css` file.
- Overrides to the theme's HTML can be made in the `layouts` folder.
- Please put a .gitkeep in any folder that will be purposely left empty.

# Font Awesome

The Font Awesome kitcode is maintained by @ChrisKibble & @ACC, two of the WinAdmins.io webmasters.  You may use any of these icons as part of updating the WinAdmins.io website if you wish to contribute, but you may not use these outside of this site.
