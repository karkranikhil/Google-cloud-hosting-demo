# Google-cloud-hosting-demo
<h4>Step 1 - Creating a Google Cloud Platform project</h1>

<p>To use Google's cloud for your own site or app, you need to create a new project on Google Cloud Platform. This requires having a Google account.</p>
<ul>
<li>Go to the <a href="https://console.cloud.google.com/projectselector/appengine">App Engine dashboard</a>on the Google Cloud Platform Console and press the Create button.</li>
<li>If you already have a project use it or otherwise create the project.</li>
<li>If you are creating new, Enter a name for the project, edit your project ID. For this tutorial, the following values are used:</li>
<li>Project Name: nikhilkarkra</li>
<li>Project ID: nikhilkarkra-217807</li>
<li>Click the Create button to create your project</li>
</ul>
 
 <h4>step 2 - Application structure</h4>
    <ul>
        <li>The website folder(You can give any name to the folder) contains your website content</li>
        <li>app.yaml is your application configuration file.</li>
        <li>Landing page must be called index.html inside website</li>
        <li>The app.yaml file is a configuration file that tells App Engine how to map URLs to your static files.</li>
   </ul>
 
<h4>step 3 - Install & Deploy with Google Cloud SDK</h4>
<ul>
<li>Use the below link to download gcloud sdk based on your OS. (I am using mac)</li>
    
    https://cloud.google.com/sdk/docs/downloads-interactive
<li> Mac user just write below command in terminal</li>
   
    curl https://sdk.cloud.google.com | bash
<li>After successfull completion,  run the below command to check the installed verion</li> 
    
    gcloud -v

<li>Go inside the folder - in our case its </li>
    
    cd Google-cloud-hosting-demo
<li>Initialize the project by running the b below command</li>
    
    gcloud init
<li>Run the below command to deploy</li>   
    
    gcloud app deploy
<li>As soon as deployment is done, you can run your app in the browser using following command.</li>
    
<li>My deployment has done for the below URL </li>
    
    https://nikhilkarkra-217807.appspot.com/
</ul>

<h5>References</h5>
 <p>MDN web docs</p>
 <p>Medium</p>
