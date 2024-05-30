# opennebula-migrator-scripts
These are the migrator scripts for OpenNebula.  These are only the migrator scripts that are published by OpenNebula.  This is **NOT** a way to circumvent paying them to upgrade to the latest version.

These instructions are written for me.  Use them at your own risk.

## Most recent script
5.12 -> 6.0 migrator

# Purpose
The purpose of this repository is just to store the scripts and documentation on how to use them.  They are not being modified at all.

# Instructions
If you have instructions for other operating systems, please email me or create a pull request.

## Ubuntu 18.04 and 20.04
These files (execpt the Readme file) should be put into the shared/ and local/ folders in /usr/lib/one/ruby/onedb/

~~~~~~~~.sh
sudo cp -vp shared/* /usr/lib/one/ruby/onedb/shared/
sudo cp -vp local/* /usr/lib/one/ruby/onedb/local/
~~~~~~~~

After the files have been copied to these locations, 'onedb upgrade' should work.

# Log
 * Taken from branch one-6.6 https://github.com/OpenNebula/one /src/onedb/ (Direct link: https://github.com/OpenNebula/one/tree/one-6.6/src/onedb)
 * Taken from branch one-6.4 https://github.com/OpenNebula/one /src/onedb/ (Direct link: https://github.com/OpenNebula/one/tree/one-6.4/src/onedb)
 * Taken from branch one-6.0 https://github.com/OpenNebula/one /src/onedb/ (Direct link: https://github.com/OpenNebula/one/tree/one-6.0/src/onedb)
 * Taken from branch one-5.12 https://github.com/OpenNebula/one /src/onedb/ (Direct link: https://github.com/OpenNebula/one/tree/one-5.12/src/onedb)

# License
Apache 2.0
