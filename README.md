dataRetrieval
=============

R package source for data retrieval specifically for the EGRET R package: 

See master branch for full details. Stable builds are stored in this packageBuilds branch.

Disclaimer
----------
This software is in the public domain because it contains materials that originally came from the United States Geological Survey, an agency of the United States Department of Interior. For more information, see the official USGS copyright policy at [http://www.usgs.gov/visual-id/credit_usgs.html#copyright](http://www.usgs.gov/visual-id/credit_usgs.html#copyright)

This software is provided "AS IS".


Download and Package Installation
---------------------------------

* The latest version of dataRetrieval can be downloaded with this link:
[dataRetrieval_1.2.1](https://github.com/USGS-R/dataRetrieval/blob/packageBuilds/dataRetrieval_1.2.1.tar.gz?raw=true)

### Installation:
While the dataRetreival package is in development (and not on CRAN), the following packages must first be manually installed: 
* zoo
 
To install the EGRET package:

Include the full path to EGRET_1.2.3.tar.gz to install the package (here is a Windows example, note the direction of the slashes -> /, this is backwards from how Windows typically defines a path ):

	install.packages("zoo")
	install.packages("C:/RPackages/Statistics/dataRetrieval_1.2.1.tar.gz", repos=NULL, type="source")

A Mac example:

	install.packages("/Users/userA/RPackages/Statistic/dataRetrieval_1.2.1.tar.gz", repos=NULL, type="source")
	
### Note on updating versions:
Some users have found it necessary to delete the package folders before installing newer versions of either dataRetrieval or EGRET.  If you are experiencing an issue after updating a package, trying deleting the package folder, the default location for Windows is something like this:
C:\Users\ldecicco\Documents\R\win-library\2.15\dataRetrieval
the default for a Mac:
/Users/ldecicco/Library/R/2.15/library/dataRetrieval
Then, re-install the package using the directions above.  Moving to CRAN should solve this problem.

