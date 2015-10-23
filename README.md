# Approach

* Used drush to download and install Drupal 7 in a generic confiuration following the "Quick installation with Drush" section of https://www.drupal.org/documentation/install/developers.
* Downloaded and enabled necessary contributed modules using drush.
* Used devel_generate to generate 10 nodes.
* Created a basic page view of Article content.
* Changed the style of the basic page view of Article content to 'XML data document' using 'Raw XML' as the format.
* Changed permission of the view so that only Authenticated users were able to view it.
* Created a new feature and added this view and all it's dependencies to it.
* Tested by creating a new blank site, downloading and enabling contrib modules, and enabling the feature.
* Tested by logging out of the test site and attempting to access the feed.
* Added all to the repository.

# Contributed modules used

* views, views_ui
* devel, devel_generate
* views_datasource - only enabled the views_xml plugin



# Your task
   
A client wants to build a site where he exposes content via an XML feed.
   
* Create a Drupal site and include it into the repository.
* Create an architecture which exposes the list of the basic Drupal Article content as an XML feed
* Protect the XML feed so that it can only be accessed by authorised third parties.
* Describe the chosen approach and contributed modules used in the README file.
* Commit any work you need to make the site operational.
* Do not commit a database into the repository. The site should work with devel_generate.
* The output of this task will likely include feature modules and an architecture description.
* If you have questions, file issues against this repository.
   
Notes: Your account is read only, please file an issue against this repository if you need write access.
