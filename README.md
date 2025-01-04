## Set up and run the application locally

**1. Prerequisites:**

* A text editor or IDE (e.g., Visual Studio Code)
* A web browser (e.g., Chrome)

**2. Clone the repository:**

* Clone this repository to your local machine using Git. You can do this using the following command in your terminal:
  
  ```bash
  git clone https://[your_github_repo_url].git

**3. Open the project in your code editor**

**4. Run the application locally:**

* Navigate to the directory containing your source code (e.g., index.html).
* Open the index.html file in your browser by double-clicking it or using a local web server.
* After running a local server, open http://localhost:port in your browser.


## Deployment Instructions


**1. Set up a Google Cloud project:**

  * Sign in to Google Cloud Console.
  * Create a new project or select an existing project.

**2. Enable Cloud Storage API:**

  * In the Google Cloud Console, navigate to the **APIs & Services** section and enable the **Cloud Storage API** for your project.

**3. Create a Cloud Storage bucket:**

  * In the Cloud Storage console, create a bucket to store your application files. Choose a unique name for your bucket.

**4. Upload Files:**

  * Open your bucket and click "Upload Files".
  * Upload all files from your portfolio project folder (e.g., index.html, styles.css, images, etc.).

**5. Make the Website Public:**

  * Go to the "Permissions" tab of your bucket.
  * Click "Grant Access".
  * Add allUsers and set the role to "Storage Object Viewer."

**6. Access Your Website:**

  * Your portfolio will be accessible at the bucket’s index.html files's public URL.
