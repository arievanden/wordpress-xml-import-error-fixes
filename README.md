# wordpress-xml-import-error-fixes
Notes on fixing xml import in Wordpress

Install this plugin and deactivate original  Importer if installed
https://github.com/humanmade/WordPress-Importer

php.ini  (add )
extension=xmlreader.so

 #yum install php55w-xml

 Make sure php limits are setup to accept  >2mb files uploads  & processing time is appropriate.
