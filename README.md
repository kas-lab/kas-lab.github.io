# Information
Currently has been created and edited using this [google site](https://sites.google.com/d/1UQF6gsHwUSUk-Xvc8ijk4Eea7XsPrvoQ/p/1wv9rxmGsqJPXeADVysBtccI5aDW1tl35/edit) owned by [chcorbato](https://github.com/chcorbato) and hosted by GitHub pages as the repository [kas-lab.github.io](https://github.com/kas-lab/kas-lab.github.io)

# How to edit the website
The website can be modified by editing it on Google sites [link] and committing the modified files to [kas-lab.github.io](https://github.com/kas-lab/kas-lab.github.io). To do so, you need to request access to the google site and the GitHub repository from [chcorbato](https://github.com/chcorbato).

The Google site is stored as a file named `kas-lab-website` contained in the [KAS Lab website](https://drive.google.com/drive/folders/1fpc1uO4gT4ZBJebG-M4Jv5sYHr37G6R9?usp=drive_link) google drive folder.

Once you have access to the required resources, you can follow these steps (based on https://support.google.com/sites/thread/240618003/i-d-like-to-download-an-offline-version-of-my-website-as-created-in-new-sites-how-is-this-done?hl=en):

0. Clone https://github.com/kas-lab/kas-lab.github.io in your machine. 
1. Open [Google Takeout](https://takeout.google.com/)
2. Deselect all files first and then scroll down to "Google Drive"
3. Activate the checkbox and click on "All Drive data included"
4. Deselect "Include all files and folders in Drive" and choose the folder `KAS Lab website`.
5. Scroll down and click "next step" button
6. Transfer to: "Add to Drive", Frequency: Export once, File type: Zip
7. Click "Create export"
8. A zip file is added in your Google Drive, search for it with "type:archive"
9. Download the zip file and unzip it (it will probably create a folder called `Takeout`).
10. Copy the files in `Takeout/Drive/KAS Lab website/kas-lab-website/DRAFT/` in the root of your local clone of https://github.com/kas-lab/kas-lab.github.io, overwriting existing files.
11. Create a new `index.html`` file in the root directory with the same content than `Home.html``
12. Commit and push the changes to https://github.com/kas-lab/kas-lab.github.io