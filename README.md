## Welcome to MYEC Colorado

This repository contains the host for the MYECColorado.com website. Any changes made in the master branch /docs folder, is automatically updated in the original website. Changes to the website can be requested by anyone in the form of "Pull Requests", but can only be approved to be merged by the Owner. The ownership is easily transferable, making for a lean future passover.

### Useful resources
---------
MYECColorado.com/Documentation/index.html located here MYEColorado/docs/Documentation/index.html contains a good quick start guide on what changes to make.

### Want to help improve the website?
---------
1. Download the Github client, Fork this repository, then click on Clone or Download-> Open in Desktop       
2. Make the changes you would like to see, test the website and make sure it works locally
3. Commit your changes at feature completion points using a suitable commit message and push your changes
4. Once you are done with a feature, or you have completed all the work, just submit a Pull Request from your repository by going to your repo and clicking the "New pull request" button and submit

### Steps to replicate this yourself
---------
Do you want to make your own website, or are curious how we did this? Here is the steps, you can just replace myeccolorado with your website name ->

#### 1. Buy the domain

Purchase the domain from namecheap.com myeccolorado.com, making sure I used Promo codes available on the internet. I have noticed that other domains are cheaper for the first year but cost more to renew every other year. Go to your purchased website and you shall see a namecheap.com error page telling you that there is nothing to show.

#### 2. Setup a Github repository

Create a repository "Myeccolorado" and clicked on "Create new file" button inside the repo with a blank file of the name docs/README.md, and committed the changes.

#### 3. Change the settings

* Go back to the repository main page and 
* Click on the "Settings" button, and 
* Under the "GitHub Pages" section, 
  * Select the option of Source-> Master branch /docs folder and Save
  * Under custom domain, enter myeccolorado.com and Save
  * Check the enforce https option

#### 4. Edit Namecheap Settings

* Login and click on Manage your account. Then go to Domain List, Select MYECColorado.com, Click on Advanced Settings, Delete the older Host Records and put in the following values 
![NameCheap.com Screenshot](https://raw.githubusercontent.com/saamerm/MYECColorado/master/ReadmeImages/Screen%20Shot%202018-11-20%20at%2012.33.06%20AM.png)
* Once saved, you should now see some Github 404 error page, if you go to the website.

#### 5. Get theme, Put in the website

* Find a website theme on themeforest.com or codepen.io, download it and unzip it.
* Now go back to the Github repository, and click "Clone or Download"->Open in Desktop.
* Locate the repository on your computer in the Github folder and then paste in the code into the docs/ subfolder.
*Note that the index.html file must be directly in the MYECColorado/docs/ and not in another layer of folders.*
* Commit your changes in the Github Desktop and Push your changes. Refresh the website myeccolorado.com, and you should now see a working website.

### Support or Contact
---------
Having trouble with anything, or curious about anything particular, feel free to contact me at i@saamer.me

**Markdown**
---------
Editing readme files, requires using Markdown. Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
