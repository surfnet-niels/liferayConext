liferayConext
=============

A connection library for SAML2 AuthN and OAuth (VOOT) based groups for Liferay
This plugin is a generic liferay plugin. For generic usage, prerequisites and build instructions see: http://www.liferay.com/community/wiki/-/wiki/Main/Plugins+SDK

##Building this plugin
* Get the contents of this repo
* cd plugins
* ant all

## Configuration
Following properties can be overridden by adding a portlet-ext.properties file to the classpath of the portal.

* saml2.header.mapping.id=persistent-id
* saml2.header.mapping.screenname=persistent-id
* saml2.header.mapping.email=emailaddress
* saml2.header.mapping.fullname=displayname

* opensocial.server.url=https://api.surfconext.nl/v1/

* opensocial.consumer.key=
* opensocial.consumer.secret=
* opensocial.redirect.url=

