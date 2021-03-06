# XMPP connection
#### Configures an XMPP connection that can in turn be referenced by other components.
<a href="http://docs.spring.io/spring-integration/docs/2.1.x/reference/html/xmpp.html#xmpp-connection" target="_blank">Documentation</a>


#### Port
The port on which the host is running.

Default is '5222'.

#### Service name
The XMPP service name for this connection.

#### Resource
The resource field specifies the XMPP resource you are using. The use of unique resources allows you to connect to your XMPP server from multiple locations simultaneously.

#### Subscription mode
The subscription mode for the XMPP connection. Dictates the policy for handling inbound messages from entries not already on the roster. Values can be "accept_all", "manual", or "reject_all".

Default is 'accept_all'.

#### Id
Name that uniquely identifies this flow component.

<i>Required</i>

#### User
The user name (e.g., someuser@gmail.com) that will be used by this connection object.

#### Password
The user's password.

#### Host
The host name to connect TO.

