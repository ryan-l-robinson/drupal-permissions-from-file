# Drupal Permissions from File

This Drupal 7 module checks if a user account is in a list in a file, and adjusts the user's roles accordingly.

This was a specific custom build for a site, not designed to be generalized and installable on any site. There is no configurable settings page. 

For this to work, you would need:

1. Have a role on the site called 'test role'.
2. Have a file in the specified position /var/usernames/roleusernames.csv and formatted with one line per username.
