# Owncloud
This ansible role installs owncloud to the server.
It also configures nginx.

## Optional variables

* owncloud_version: Version of owncloud to install.
* owncloud_domain: Domain under which to publish the site.
* owncloud_storage_path: Directory for owncloud to upload files to.
* owncloud_base_path: Ownclouds install directory
* owncloud_ssl_cert: Path to the on server certificate file to use for TLS.
* owncloud_ssl_key: Path to the on server key file to use for TLS.

## Don't change unless you know what you're doing
* owncloud_url: URL to owncloud install package.
* owncloud_package: Owncloud package file name.
* owncloud_owner: Which user should owncloud run as. Should be the same as the webserver user.
