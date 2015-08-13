INSTRUCTIONS:
    1. Rename config.json.example on config.json and edit the config.json
    2. Upload this script to your server somewhere it can be publicly accessed
    3. Make sure the apache user owns this script (e.g., sudo chmod -R 755 deploy/ )
    4  Create a repository that will store the files of projects (e.g., /var/www/project-repository)
    5. Make sure the apache user owns this directory (e.g., sudo chown www-data:www-data project-repository)
    6. (optional) If the repo already exists on the server, make sure the same apache user from step 3 also owns that
       directory (i.e., sudo chown -R www-data:www-data deploy/)
    7. Go into your Github Repo > Settings > Service Hooks > WebHook URLs and add the public URL
       (e.g., http://example.com/deploy.php)
