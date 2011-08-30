# Jenkins Chef Cookbook
## Description
Installs a full Jenkins CI with Chef. Runs on Ubuntu.
This cookbook installs the Github and authorization plugins for Jenkins. Comment out if necessary.
The example recipe has a few...example commands for plugins or jobs.
Forked from Boundary cookbooks repo: https://github.com/boundary/boundary_cookbooks
## Requirements
* Ubuntu
* Chef
* Java: Jenkins requires Java to be installed. I recommend Sun Java as OpenJDK may have issues. The Java cookbook provided by Opscode is great; just make sure to set the installation to Sun.
You can find the cookbook at http://community.opscode.com/cookbooks/java
The Java cookbook also requires http://community.opscode.com/cookbooks/apt

