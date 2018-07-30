---
title: "Documentation Tags"
date: 2018-04-06
weight: 1101
chapter: true
---

# authentication system

@access private|public|protected|hybrid
@class  AccessControl {@requires user}
@class AccessControl {@requires user} {@level 5}

# documentation parameters

@access private|public|protected|hybrid

// @cache headerCacheControlValue
// @expires numberOfSeconds
// @throttle numberOfMilliSeconds
// @status httpStatusCode
// @header httpHeader
// @param [type] Name [Description] {@name value}
// @var [type] [Description] # authentication system

@access private|public|protected|hybrid
@class  AccessControl {@requires user}
@class AccessControl {@requires user} {@level 5}

# documentation parameters

@access private|public|protected|hybrid

// @cache headerCacheControlValue
// @expires numberOfSeconds
// @throttle numberOfMilliSeconds
// @status httpStatusCode
// @header httpHeader
// @param [type] Name [Description] {@name value}
// @var [type] [Description] {@name value}
// @throws httpStatusCode [Reason]
// @return type [Description]
// @view Name
// @errorView Name
// @param [type] $name [Description] {@from path|body|query|head}
// @param string $name [Description] {@type email|date|datetime|timestamp}
// @param string $name [Description] {@choice option1,option2...}
// @param string|int|float|array $name [Description] {@min value}{@max value}
// @param string|int|float|array $name [Description] {@fix true} (will attempt to fix the value when wrong)
// @param string $name [Description] {@pattern /REGEX_HERE/REGEX_OPTIONS}
//       @param string $password  {@pattern /^(?:[0-9]+[a-z]|[a-z]+[0-9])[a-z0-9]*$/i}
//                     {@message Strong password with at least one alpha and one numeric character is required}
// @param string|int|float $name [Description] {@message value} (custom error message)
// @param string|int|float $name [Description] {@example value}
// @param type $name [Description] {@label Custom Name}
// @return array {@label Sign In} (name for submit button)
// @field
// @message
// @form
// @input
// @textarea
// @radio
// @select
// @submit
// @fieldset

// https://github.com/Luracast/Restler/blob/master/ANNOTATIONS.md
// https://github.com/Luracast/Restler/blob/master/PARAM.md
// @see http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api
{@name value}
// @throws httpStatusCode [Reason]
// @return type [Description]
// @view Name
// @errorView Name
// @param [type] $name [Description] {@from path|body|query|head}
// @param string $name [Description] {@type email|date|datetime|timestamp}
// @param string $name [Description] {@choice option1,option2...}
// @param string|int|float|array $name [Description] {@min value}{@max value}
// @param string|int|float|array $name [Description] {@fix true} (will attempt to fix the value when wrong)
// @param string $name [Description] {@pattern /REGEX_HERE/REGEX_OPTIONS}
//       @param string $password  {@pattern /^(?:[0-9]+[a-z]|[a-z]+[0-9])[a-z0-9]*$/i}
//                     {@message Strong password with at least one alpha and one numeric character is required}
// @param string|int|float $name [Description] {@message value} (custom error message)
// @param string|int|float $name [Description] {@example value}
// @param type $name [Description] {@label Custom Name}
// @return array {@label Sign In} (name for submit button)
// @field
// @message
// @form
// @input
// @textarea
// @radio
// @select
// @submit
// @fieldset

// https://github.com/Luracast/Restler/blob/master/ANNOTATIONS.md
// https://github.com/Luracast/Restler/blob/master/PARAM.md
// @see http://www.vinaysahni.com/best-practices-for-a-pragmatic-restful-api



{{% notice info %}}
**This documentation is work in progress (WIP)**

Feel free to [open an issue](https://bitbucket.org/pkollitsch/booka-docs/issues?status=new&status=open) for a topic you miss, or give back to the project by cloning the repository and [commit changes by yourself](https://bitbucket.org/pkollitsch/booka-docs/src).
{{% /notice %}}

