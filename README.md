# Gulp-setup

This repository provides a Gulp setup to streamline your project's frontend development process. By incorporating this setup, you can benefit from automated tasks to enhance your workflow.

Getting Started
1) Download:
   Clone or download this repository and include it in your project.

2) Install Dependencies:
   Run the following command to install the necessary node_modules in your project:
   npm install

3) Run Gulp:
   Execute the following command in your terminal to run Gulp. This will automatically compress your CSS and JS files each time you save changes.   
   gulp


Usage

1) CSS Changes:
Make CSS changes inside the app folder, where you write your SCSS code. Gulp will compress and save the changes automatically.
Create a new SCSS file in the app/scss/pages directory, for example, "product.scss."
Open the pages.scss file in the app/scss directory. Include your newly created SCSS file using the @import statement. This ensures that your custom styles are integrated into the main stylesheet.
Upon saving the "product.scss" file, Gulp will automatically compress and save the changes in the main style.css file.

Now, your custom styles for the "product" page are seamlessly integrated into the project, providing an organized and modular approach to styling individual pages.

2) JS Changes:
Modify the "script.js" file inside the js folder in the app directory. Your JS code will be compressed and saved in the assets folder as "app.js".

3) Image Compression:
Add PNG and JPG images to the app/images folder. Gulp will compress and save them as .webp files in the assets folder. Access these optimized images in your web pages from the assets folder.


Additional Features:
This setup includes predefined libraries for improved support. Customize the configuration according to your project requirements for a seamless development experience.


Note: 

If Gulp does not automatically save changes, especially after adding images, you may encounter occasional disruptions. In such cases, restarting Gulp can resolve the issue and ensure that your changes are properly saved.

Steps to Resolve:
1) 	Restart Gulp:
	Simply restart Gulp by stopping the current process and running it again. Execute the following command in your terminal:
	gulp

2) 	Check Image Processing:
	Ensure that images are added to the correct directory (app/images) and follow the established naming conventions. Gulp should compress and save these images automatically as specified in the setup.

3) 	Verify Configuration:
	Double-check your Gulp configuration to confirm that the tasks related to image processing are correctly defined.

By restarting Gulp, you refresh the automated processes, and any issues hindering auto-saving, particularly after adding images, should be resolved. This ensures a smooth development experience with Gulp.