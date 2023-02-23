# Simple library to deal with not so simple ldap

## Repository description

I find working with ldap to be cumbersome so this is a simple library with various methods that make life easier.

## How to configure

Pass in a credential file when initializing the library.

from ldaplib import LdapLib as lquery\
linit = lquery("path to json config file")

## Json config file format

{\
	"userdn": "users fill ldap distinguished name",\
	"password": "password for userdn",\
	"server": "IP Address or hostname of a node that has ldap available on port 636"\
}
