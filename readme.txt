Use Python 2* version to run the script. Sudo is required.

Usage:
python use-firefox *version*


Common output:
***Already run with requested version***  -->  No actions requiered, requested version already active
***Please write Firefox version***  --> script run without argument pointing to the version
***Couldn't fetch this Firefox's version***  --> Firefox version doesn't exist as a resource, be sure version you wrote is correct
***Downloading Firefox***  -->  version you need doesn't exist and should be downloaded before activating
***Firefox {version} has been activated***  -->  Firefox was successfully activated with requested version



After running the script and activating requested firefox version, CURRENT_FIREFOX_VERSION variable will be added to /etc/environment.
This will be available after the next login.
