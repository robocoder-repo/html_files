
# Guide: Hosting and Viewing HTML Files Using GitHub Pages

This guide outlines the process of hosting HTML files on GitHub and making them accessible via GitHub Pages.

## Steps:

1. Create a GitHub Repository:
   - Log in to your GitHub account.
   - Create a new repository (e.g., 'html_files').

2. Upload HTML Files:
   - Use GitHub's web interface or Git commands to upload your HTML files to the repository.

3. Enable GitHub Pages:
   - Go to your repository's settings.
   - Scroll down to the "GitHub Pages" section.
   - Under "Source", select the branch containing your HTML files (usually 'main').
   - Save the changes.

4. Create a File List:
   - Create an HTML file (e.g., 'file_list.html') that links to all your other HTML files.
   - Use the GitHub Pages URL format for links: 
     https://<username>.github.io/<repository-name>/<filename>.html

5. Access Your Files:
   - Main file list: https://<username>.github.io/<repository-name>/file_list.html
   - Individual files: https://<username>.github.io/<repository-name>/<filename>.html

## Example File List (file_list.html):

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Files</title>
</head>
<body>
    <h1>HTML Files</h1>
    <ul>
        <li><a href="https://<username>.github.io/<repository-name>/file1.html">File 1</a></li>
        <li><a href="https://<username>.github.io/<repository-name>/file2.html">File 2</a></li>
        <!-- Add more files as needed -->
    </ul>
</body>
</html>
```

Replace <username> with your GitHub username and <repository-name> with your repository name.

## Viewing on Mobile:
1. Open the file list URL in your mobile browser.
2. Tap on any link to view the rendered HTML file.

This method allows you to host and view your HTML files on any device with internet access, including mobile phones.
