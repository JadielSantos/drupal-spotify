# Drupal Challenge
### These are the instructions for the Drupal Challenge website

1. Initialize the site
```
fin init
```

2. Start the project
```
fin start
```

3. Import Database from the file 'drupal-challenge.sql'
```
fin db import ./drupal-challenge.sql --progress
```

4. Go to docroot folder, clear caches using drush, and then login as admin to the website
```
cd docroot/
fin drush cr
fin drush uli
```

5. Now you can access the Drupal Challenge module settings through the admin menu Configuration -> System -> DC Spotify Settings
- ![DC Spotify Settings](/docs/print-1.png)

6. Then you can copy a Spotify Playlist ID from the spotify url and paste in the Spotify Playlist ID config
- Example: https://open.spotify.com/playlist/4KV5PFqKBNauGP1vYwcsrK
- In this case I would insert the Playlist ID **4KV5PFqKBNauGP1vYwcsrK** in the config input field

7. To import Songs, Artists, and Albums using the DC Spotify module you need to run cron
- You can do so through the admin menu by hovering on the Drupal icon -> Run cron
- ![Run Cron](/docs/print-2.png)


### By [Jadiel dos Santos](https://www.linkedin.com/in/jadielsantos)