# login_with_facebook


<!-- Login with facebook script -->
<!-- https://drive.google.com/file/d/14K15TUymA2gQl1zXcZgnkfnmyizCpGUI/view -->

<!-- https://developers.facebook.com/docs/javascript/quickstart -->




<!-- then go down to basic setup

Basic Setup
The Facebook SDK for JavaScript doesn't have any standalone files that need to be downloaded or installed, instead you simply need to include a short piece of regular JavaScript in your HTML that will asynchronously load the SDK into your pages. The async load means that it does not block loading other elements of your page.

The following snippet of code will give the basic version of the SDK where the options are set to their most common defaults. You should insert it directly after the opening <body> tag on each page you want to load it: -->

<br/><br/>
<script>
  window.fbAsyncInit = function() {
    FB.init({
      appId            : 'your-app-id',
      autoLogAppEvents : true,
      xfbml            : true,
      version          : 'v3.2'
    });
  };

  (function(d, s, id){
     var js, fjs = d.getElementsByTagName(s)[0];
     if (d.getElementById(id)) {return;}
     js = d.createElement(s); js.id = id;
     js.src = "https://connect.facebook.net/en_US/sdk.js";
     fjs.parentNode.insertBefore(js, fjs);
   }(document, 'script', 'facebook-jssdk'));
</script>
<br/><br/><br/><br/>
<!-- This code will load and initialize the SDK. You must replace the value in your-app-id with the ID of your own Facebook App. You can find this ID using the App Dashboard https://developers.facebook.com/apps   -->




<!-- Now goto setting, and add domain -->


<!-- then add platform, as website -->

<!-- then, copy the APP ID, and paste it in the basic code -->



