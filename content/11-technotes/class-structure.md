---
title: "Class Structure"
date: 2018-06-06
weight: 1101
chapter: true
---

# Class Structure

## Variables

### Fields

Work in Progress (WIP) and changes might occur!

Variable `$fields` contains an array with parameters for an easy form setup based on the fields of an object of this type:

- title - internal title (slug) of the field
- label - label for the formfield
- description - note about the meaning/usage of this field, will be displayed small greyed out below the field
- type - one of the following
	+ checkbox
	+ checkboxes-inline
	+ checkboxes
	+ color
	+ country
	+ date
	+ daterange
	+ datetime
	+ editor
	+ email
	+ formfields
	+ gender
	+ header
	+ image
	+ integer
	+ multi-email
	+ password
	+ radio-inline
	+ radio
	+ select
	+ text
	+ textarea
	+ time
	+ upload
	+ url
	+ userrights
	+ users
	+ yesno
- class - class attached to the field
- gridclass - layout grid class attached to the form group
- default - default value if no value exists
- values - array with key => values for selects
- options - array containing additional setup

This variable will replace `static::FIELDS` in the near futurte, enabling the system to create easily forms and validate content of the fields and submissions in post/put methods.

## Constants

### general 

- APIROOT (string|false) - path to API5 method, used for initialization of restler interface (in the near future)
- ERROR_CODE_PREFIX - class error prefix, used in global Exceptions
- FIELDS - comma separated list of column names that objects of this kind returns (obsolete, see variable $fields)
- MAINTABLE - table containing objects of this kind

- POSITIONFIELD - If items of this object are manually sortable in lists (like indexLabels) which field is the sort indicator

### index helpers

- FILTER - filter to use per default in the index method
- IDFIELD - column that contains the unique identifier for objects of this kind
- LIMIT - default limit to return for objects of this kind (used in index method)
- SORT - default sort column for index method

### sorting helpers 

- IS_SORTABLE - is this table sortable (used in index method)
- SORTFIELD - if IS_SORTABLE=true then what column(s) to sort by
- SORTDIRECTION - sort direction (ASC|DESC)

### labelling helpers

- TITLEFIELD - column name for labelling results
- TITLESTRING - string to use for labelling results (contains valid SQL string)

If `TITLESTRING` is set it overwrites `TITLEFIELD`. If none of these fields is set the first field that is not the `IDFIELD` in the $fields array is used.

## Methods

### index
### get
### post
### put
### delete
### cleanupFields(Multi?)
### prepareFields(Multi?)
