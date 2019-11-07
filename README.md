# zimbra-ssdb
SSDB Package for Zimbra 8.8

(https://zimbra.github.io/adminguide/latest/#ephemeral_data)

There are 3 main types of ephemeral data stored in LDAP during normal operation of Zimbra Collaboration.

Last Logon Time Stamps (zimbraLastLogonTimestamp)

Auth Tokens (zimbraAuthTokens)

CSRF Tokens (zimbraCsrfTokenData)

On small systems, storage of these types of ephemeral data may be done in the LDAP Server. However, mail systems with large numbers of active users have been found to overload LDAP for short-lived data storage. Therefore, the preferred option is to store this ephemeral data using an external server.
