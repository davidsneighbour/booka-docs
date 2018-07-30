---
title: "Documentation Format"
date: 2018-04-06
weight: 1101
chapter: true
---

# Documentation Format

Following the used PHPDoc tags in Booka based on their location. Note that we apply a strict inheritance rule to keep code lines low. If the tag is defined on file or class level don't repeat it further down if it's not changed.

Refer to api5/class-template.php for a fully documented object file.

## Official documentation

- [PHPDoc reference — phpDocumentor](https://docs.phpdoc.org/references/phpdoc/index.html)
- [Basic Syntax — phpDocumentor](https://docs.phpdoc.org/references/phpdoc/basic-syntax.html)
- [Types — phpDocumentor](https://docs.phpdoc.org/guides/types.html)
- [Inheritance — phpDocumentor](https://docs.phpdoc.org/guides/inheritance.html)

## File tags

| tag | location | text |
| --- | -------- | ---- |
| author | Any | documents the author of the associated element. |
| category | File, Class | groups a series of packages together. |
| copyright | Any | documents the copyright information for the associated element. |
| deprecated | Any | indicates that the associated element is deprecated and can be removed in a future version. |
| example | Any | shows the code of a specified example file or, optionally, just a portion of it. |
| filesource | File | includes the source of the current file for use in the output. |
| ignore | Any | tells phpDocumentor that the associated element is not to be included in the documentation. |
| internal | Any | denotes that the associated elements is internal to this application or library and hides it by default. |
| license | File, Class | indicates which license is applicable for the associated element. |
| link | Any | indicates a relation between the associated element and a page of a website. |
| package | File, Class | categorizes the associated element into a logical grouping or subdivision. |
| see | Any | indicates a reference from the associated element to a website or other elements. |
| since | Any | indicates at which version the associated element became available. |
| subpackage | File, Class | categorizes the associated element into a logical grouping or subdivision. |
| todo | Any | indicates whether any development activity should still be executed on the associated element. |
| uses | Any | indicates a reference to (and from) a single associated element. |
| version | Any | indicates the current version of Structural Elements. |

## Class tags

| tag | location | text |
| --- | -------- | ---- |
| author | Any | documents the author of the associated element. |
| category | File, Class | groups a series of packages together. |
| copyright | Any | documents the copyright information for the associated element. |
| deprecated | Any | indicates that the associated element is deprecated and can be removed in a future version. |
| example | Any | shows the code of a specified example file or, optionally, just a portion of it. |
| ignore | Any | tells phpDocumentor that the associated element is not to be included in the documentation. |
| internal | Any | denotes that the associated elements is internal to this application or library and hides it by default. |
| license | File, Class | indicates which license is applicable for the associated element. |
| link | Any | indicates a relation between the associated element and a page of a website. |
| method | Class | allows a class to know which ‘magic’ methods are callable. |
| package | File, Class | categorizes the associated element into a logical grouping or subdivision. |
| property | Class | allows a class to know which ‘magic’ properties are present. |
| property-read | Class | allows a class to know which ‘magic’ properties are present that are read-only. |
| property-write | Class | allows a class to know which ‘magic’ properties are present that are write-only. |
| see | Any | indicates a reference from the associated element to a website or other elements. |
| since | Any | indicates at which version the associated element became available. |
| source | Any, except File | shows the source code of the associated element. |
| subpackage | File, Class | categorizes the associated element into a logical grouping or subdivision. |
| todo | Any | indicates whether any development activity should still be executed on the associated element. |
| uses | Any | indicates a reference to (and from) a single associated element. |
| version | Any | indicates the current version of Structural Elements. |

## Method tags


| tag | location | text |
| --- | -------- | ---- |
| api | Methods | declares that elements are suitable for consumption by third parties. |
| author | Any | documents the author of the associated element. |
| copyright | Any | documents the copyright information for the associated element. |
| deprecated | Any | indicates that the associated element is deprecated and can be removed in a future version. |
| example | Any | shows the code of a specified example file or, optionally, just a portion of it. |
| ignore | Any | tells phpDocumentor that the associated element is not to be included in the documentation. |
| internal | Any | denotes that the associated elements is internal to this application or library and hides it by default. |
| link | Any | indicates a relation between the associated element and a page of a website. |
| param | Method, Function | documents a single argument of a function or method. |
| return | Method, Function | documents the return value of functions or methods. |
| see | Any | indicates a reference from the associated element to a website or other elements. |
| since | Any | indicates at which version the associated element became available. |
| source | Any, except File | shows the source code of the associated element. |
| throws | Method, Function | indicates whether the associated element could throw a specific type of exception. |
| todo | Any | indicates whether any development activity should still be executed on the associated element. |
| uses | Any | indicates a reference to (and from) a single associated element. |
| version | Any | indicates the current version of Structural Elements. |

## Variable and properties tags

| tag | location | text |
| --- | -------- | ---- |
| author | Any | documents the author of the associated element. |
| copyright | Any | documents the copyright information for the associated element. |
| deprecated | Any | indicates that the associated element is deprecated and can be removed in a future version. |
| example | Any | shows the code of a specified example file or, optionally, just a portion of it. |
| global | Variable | informs phpDocumentor of a global variable or its usage. |
| ignore | Any | tells phpDocumentor that the associated element is not to be included in the documentation. |
| internal | Any | denotes that the associated elements is internal to this application or library and hides it by default. |
| link | Any | indicates a relation between the associated element and a page of a website. |
| see | Any | indicates a reference from the associated element to a website or other elements. |
| since | Any | indicates at which version the associated element became available. |
| source | Any, except File | shows the source code of the associated element. |
| todo | Any | indicates whether any development activity should still be executed on the associated element. |
| uses | Any | indicates a reference to (and from) a single associated element. |
| var | Properties | ... |
| version | Any | indicates the current version of Structural Elements. |


{{% notice info %}}
**This documentation is work in progress (WIP)**

Feel free to [open an issue](https://bitbucket.org/pkollitsch/booka-docs/issues?status=new&status=open) for a topic you miss, or give back to the project by cloning the repository and [commit changes by yourself](https://bitbucket.org/pkollitsch/booka-docs/src).
{{% /notice %}}
