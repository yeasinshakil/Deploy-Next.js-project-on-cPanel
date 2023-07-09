<h1 align="center">
  Deploy Next.js on cPanel
</h1>

## 🚀 How to run

Clone this repository and Navigate into your directory. Run


    ```shell
    cd my-nextjs-site/
    npm install
    ```
1.  **Start developing.**

    Navigate into your new site’s directory and start it up.

    ```shell
    cd my-nextjs-site/
    npm run start
    ```

2.  **Open the code and start customizing!**

    Your site is now running at http://localhost:3000!


## 🚀 How to Deploy

****Step 1: Create a Production Build****



Before we proceed, ensure that you have a Next.js app ready for deployment.

Run the command: npm run build 

This will generate a production-ready build of your Next.js app in the “out” directory.

 <img alt="Gatsby" src="https://bitbyhost.com/wp-content/uploads/2023/06/Screenshot-103-1.png" />

The out folder is essentially a super-compressed version of your program that has everything your browser needs to identify and run your app.

Go to your “out” folder. Select all of your file and compress them into a zip file.

<img alt="React" src="https://bitbyhost.com/wp-content/uploads/2023/06/Screenshot-99-768x432.png" />

<br/>

***Step 2: Prepare Your cPanel Account***



To deploy your React.js app on cPanel, you need to perform the following preparations:

Access your cPanel account.

Set up a new subdomain or use an existing one for your React app. For example, “react.yourdomain.com”.

To create a subdomain. Go to your cPanel account. Find domains section Click “Domains” under the “Domains” section.

<img alt="Gatsby" src="https://bitbyhost.com/wp-content/uploads/2023/06/Screenshot-82-768x432.png" />

Click the “Create A New Domain” button.

<img alt="Gatsby" src="https://bitbyhost.com/wp-content/uploads/2023/06/Screenshot-47-4-768x432.png />

Enter the subdomain name to add in the “Domain” text box.

Deselect the “Share document root (/home/username/public_html) with “domain.tld”.” option.

Enter the directory where you want the files for this subdomain to exist.

Click the “Submit” button.

<img alt="Gatsby" src="https://bitbyhost.com/wp-content/uploads/2023/06/Screenshot-89-768x432.png" />


<br/>
***Step 3: Upload Your Next.js App to cPanel***



Now, let’s upload your Next.js app to cPanel

After submit the subdomain name you will see your newly created subdomain in domain list.

now click on document root to navigate root folder

<img alt="Gatsby" src="https://bitbyhost.com/wp-content/uploads/2023/06/Screenshot-104-768x432.png" />

it will redirects you to a new tab with cPanel file manager where you will see your subdomain root folder and click on it. After clicking the folder the folder should be empty.

<img alt="Gatsby" src="https://bitbyhost.com/wp-content/uploads/2023/06/Screenshot-91-768x432.png" />

on top bar you will see a upload button. click on it and it will redirect you to a new tab where you can upload your Next.js file.

<img alt="Gatsby" src="https://bitbyhost.com/wp-content/uploads/2023/06/Screenshot-92-768x432.png" />

Upload your zip file from public folder what you have created little earlier.

<img alt="Gatsby" src="https://bitbyhost.com/wp-content/uploads/2023/06/Screenshot-100-768x432.png" />

After uploading 100% go to cPanel file manager tab and click on refresh button.

You will see uploaded zip file there and extract the file

<img alt="Gatsby" src="https://bitbyhost.com/wp-content/uploads/2023/06/Screenshot-102-768x432.png" />

Now you’ll see extracted folder file here.

<img alt="Gatsby" src="https://bitbyhost.com/wp-content/uploads/2023/06/Screenshot-105-768x432.png" />

Once the upload is complete, ensure that the subdomain folder contains the “index.html” file and other assets.

***Step 4: Access Your Deployed Next.js App***



Congratulations! Your Next.js app is now deployed on cPanel shared hosting. To access it, simply open your web browser and visit your subdomain URL (e.g., next.yourdomain.com). You should see your Next app running smoothly.


to learn more <a href="https://bitbyhost.com/next-js-deployment-on-cpanel-shared-hosting/" target="_blank">Next js Deployment on cPanel Shared Hosting: Your Ultimate cPanel Guide</a>


## 🚀 Resources

Some usefull resorces: 

<a href="https://bitbyhost.com/next-js-deployment-on-cpanel-shared-hosting/" target="_blank">Next js Deployment on cPanel Shared Hosting: Your Ultimate cPanel Guide</a> <br/>
<a href="https://bitbyhost.com/best-wordpress-hosting/" target="_blank">How to Choose the Best WordPress Hosting for Your Agency’s Needs</a><br/>
<a href="https://bitbyhost.com/deploy-a-react-app-on-cpanel/" target="_blank">Deploy a React App on cPanel: Overcoming Limitations of Shared Hosting(Step-by-Step Guide)</a><br/>

## 🚀 Credits

https://bitbyhost.com/
&
https://bitbytesoft.com/