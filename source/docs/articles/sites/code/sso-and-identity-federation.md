---
title: SSO and Identity Federation on Pantheon
description: Centrally manage user identities and provide seamless integration across multiple applications.
category:
  - developing

---

## Overview
Many organizations need to centrally manage their user's identities and provide seamless integration across multiple applications. Numerous Pantheon customers, including higher educational institutions, school districts, local governments, and other groups use a variety of Single Sign-On (SSO) solutions.  

Pantheon’s flexible infrastructure does not restrict protocols or ports used for communication. There are no outbound restrictions (protocol, port, etc.) for traffic from Pantheon to external services.  


## LDAP and LDAPS (LDAP over SSL)

Both LDAP and LDAPS are supported on Pantheon. For more information, see our article [LDAP and LDAPS on Pantheon](/articles/sites/code/ldap-and-ldaps-on-pantheon/).

## Shibboleth and SimpleSAMLphp

[Shibboleth](http://shibboleth.net/) is an open-source single sign-on solution. [SimpleSAMLphp](http://simplesamlphp.org/) can be used as a Service Provider to connect to either Shibboleth or a SAML 2.0 Identity Provider. For more information on SimpleSAMLphp on Pantheon, see our article  [Using SimpleSAMLphp](http://helpdesk.getpantheon.com/customer/portal/articles/555188-using-simplesamlphp).

## OAuth

[OAuth](http://oauth.net/) is an open authorization standard and customers have reported success using it.  


Also, Pantheon includes the [PECL OAuth](http://us.php.net/oauth) PHP extension. If you need a different version, you can download the library and rename the class to avoid a naming conflict.

## IP-Based Security Considerations

Pantheon is a cloud platform, so there are some considerations that you should be aware of.  














