# homepage# Personal Academic Homepage

This repository contains the files for Wang Ma's personal academic homepage.

## Structure

* `index.html`: The main HTML file containing the page structure and content.
* `main.css`: The CSS file for styling the homepage.
* `/images/`: Folder to store images like your profile picture (`profile.jpg`) and WeChat QR code (`wechat_qr.png`). Create this folder.
* `/files/`: Folder to store files like your CV (`CV_Wang_Ma.pdf`) and project reports/slides. Create this folder.

## Deployment to GitHub Pages

This site is designed to be easily deployed using GitHub Pages.

**Steps:**

1.  **Create a GitHub Repository:**
    * If you haven't already, create a new **public** repository on GitHub.
    * The standard repository name for a user/organization site is `<your-username>.github.io`. Using this name will make your site available at `https://<your-username>.github.io`.
    * Alternatively, you can use any other repository name (e.g., `homepage`). Your site will then be available at `https://<your-username>.github.io/<repository-name>`.

2.  **Upload Files:**
    * Clone the repository to your local machine or use GitHub Desktop.
    * Place the `index.html` and `main.css` files in the **root** directory of the repository.
    * Create an `images` folder and add your `profile.jpg` and `wechat_qr.png` (or other images) inside it.
    * Create a `files` folder and add your `CV_Wang_Ma.pdf` (or other files) inside it.
    * Commit and push the files to your GitHub repository.

3.  **Configure GitHub Pages:**
    * Go to your repository on GitHub.com.
    * Click on the "Settings" tab.
    * In the left sidebar, click on "Pages".
    * Under "Build and deployment":
        * Select Source: "Deploy from a branch".
        * Select Branch: Choose the branch where you pushed your files (usually `main` or `master`).
        * Select Folder: Choose `/ (root)`.
    * Click "Save".

4.  **Wait and Visit:**
    * GitHub Actions will start building and deploying your site. This might take a minute or two. You can monitor the progress under the "Actions" tab of your repository.
    * Once deployed, the Pages settings page will display the URL where your site is live (e.g., `https://<your-username>.github.io/` or `https://<your-username>.github.io/<repository-name>/`).
    * Visit the URL to see your homepage!

**Updating Your Site:**

* To update your homepage, simply modify the files (`index.html`, `main.css`, images, etc.) locally, commit the changes, and push them to your GitHub repository. GitHub Pages will automatically redeploy the updated site.

## Customization

* **Content:** Edit `index.html` to update your About Me text, news, projects, experience, contact links (especially placeholder URLs like `YOUR_LINKEDIN_URL`), etc.
* **Styling:** Modify `main.css` to change colors, fonts, layout, and other visual aspects. Colors and basic dimensions are defined using CSS variables near the top of the file for easier changes.
* **Images/Files:** Replace the placeholder images and files in the `/images/` and `/files/` folders with your own. Ensure the paths in `index.html` match the file locations.
