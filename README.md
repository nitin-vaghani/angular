# angular
Install angular in Ubuntu

# install angular package
sudo apt install ng-common

# Uninstall angular package
sudo apt remove ng-common

*cli version as per your package.json file

# Install Globablly
npm install -g @angular/cli

# Install Locally
npm install @angular/cli

# Install Specific Version (Example: 6.1.1)
npm install -g @angular/cli@12.2.7

# Usage
ng help


# Setup project :
> npm install

# Run Project
ng serve or ng serve --open

Open it from http://localhost:4200/

# To clean the cache:
npm cache clean

# Run the following commands when error :
npm uninstall -g @angular/cli
npm cache verify
npm install -g @angular/cli@next
npm update

# Then
ng serve

# ThankYou ;)
