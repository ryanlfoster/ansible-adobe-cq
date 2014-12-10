# ansible-adobe-cq5

Ansible module to automate configuration of Adobe CQ

## cqagent

Create and modify replication agents

## cqgroup

Create a basic group. This module doesn't handle access control lists so it's not that useful. It's more to create groups that contain other groups, e.g. a 'sysadmin' group is in the administrator group; 'developers' are in the 'readonly' group.

## cqpassword

Change a user's password. Usually used to change the admin password from the default of 'admin'

## cqpkg

Manage CQ packages

## cquser

Create and modify users

## cqbundle

Enable and disable bundles

## cqservice

Start and stop CQ instances
