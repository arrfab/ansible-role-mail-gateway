# Mail Gateway Role

## Goal
The goal of that Ansible role is to configure a dedicated node as a mail relay/gateway that would perform antivirus/antispam checks, and would log everything in a DB. Then it would forward all the mails to the real mail server.
The tools used/configured/deployed by this role are : 
* postfix
* mailscanner
* mailwatch
* clamav/clamd
* spamassassin
* selinux custom policies

## Tested platform
This role has been tested only on CentOS 7 (so should work on RHEL 7 too)

## Dependencies 
Some other roles, defined in meta/main.yml

## Variables and explanations
See defaults/main.yml 
 
