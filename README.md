# How i solved it
A list of hacks, tips and tricks on how I solve common programming &amp; engineering problems

1. ## Unable to access php website, prompts “Download” file?

  ## Solutions
    * If you are running the app in a different enviroment, ensure that your php version is same or higher.
    * Check the app's config settings for things like base_path, base_url, db variables etc.
    * Modify .htaccess file to rewrite your url to point to the right enviroment.
