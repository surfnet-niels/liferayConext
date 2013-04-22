liferayConext
=============

A connection library for SAML2 AuthN and VOOT based groups for Liferay

How to build the OpenConext plugins.

See http://www.liferay.com/community/wiki/-/wiki/Main/Plugins+SDK

## cd plugins
## ant all

Following properties can be overridden by adding a portlet-ext.properties file to the classpath of the portal.

saml2.header.mapping.id=persistent-id
saml2.header.mapping.screenname=persistent-id
saml2.header.mapping.email=emailaddress
saml2.header.mapping.fullname=displayname

opensocial.server.url=https://api.surfconext.nl/v1/

opensocial.consumer.key=
opensocial.consumer.secret=
opensocial.redirect.url=
