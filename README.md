generate-modman
===============

Requirements
------------
- Mac or Linux based OS
- awk


Download
--------

    curl -sS https://raw.githubusercontent.com/mhauri/generate-modman/master/generate-modman > generate-modman

Move file to /usr/local/bin

    sudo mv generate-modman /usr/local/bin

Make the file executable
    
    sudo chmod 755 /usr/local/bin/generate-modman

Usage
-----

    generate-modman [options]


Options
-------
    --include-others    Include non default magento directories
    --include-others-files    Include non default magento directories as files
    --include-app-code-core      Include app/code/core files (e.g. for official patches)
    --subdirectory=DIRNAME       If files are in a subdirectory of the module (e.g. src for src/app/code/community))

License
-------

generate-modman is licensed under the MIT License - see the LICENSE file for details
