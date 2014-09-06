###Install Bolt as a Web-Root Composer Package

This skeleton installs the Bolt app outside of the web root, with a public directory to handle
public assets.

To install:

`composer create-project rossriley/boltcomposer-webroot mybolt-project dev-master`

After install for speed of configuration on *nix based machines you can do the following within the project root:

`mkdir -p ./app & chmod 0777 ./app`

`mkdir -p ./extensions & chmod 0777 ./extensions`

`mkdir -p ./public/extensions & chmod 0777 ./public/extensions`


Then navigate to `/bolt` and you should see the first user setup screen.