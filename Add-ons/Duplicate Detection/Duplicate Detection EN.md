## Overview
This add-on allows you to configure duplicate detection rules for entities. You define a "base" and a "match" entity, define which fields to "match" on, and add a small snippet of code to your UI. The add-on does the rest.

Duplicate Detection add-on allows CUBA Platform users to configure rules to prevent "duplicate" data entry into the system. For example, if you want to ensure that no two customer's can have the same email address, you can set up a duplicate detection rule to prevent users from creating duplicate data. This add-on is beneficial because it supports duplicate detection across entities (so customer and user records can be set up to not allow the same email, for example). Additionally, Associations to other records are supported (as long as the other record extends StandardEntity).