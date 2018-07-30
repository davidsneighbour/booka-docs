---
title: "HTTP Status Code"
date: 2018-04-06
weight: 1101
chapter: true
---

# HTTP Status Code

## 1xx: Informational

Request received, continuing process

| Code | Explanation |
| ---- | ----------- |
| 100 | Continue |
| 101 | Switching Protocols |

## 2xx: Success

Request was successfully received, understood, and accepted

| Code | Explanation |
| ---- | ----------- |
| 200 | OK --- Response to a successful GET, PUT, PATCH or DELETE. Can also be used for a POST that doesn't result in a creation. |
| 201 | Created --- Response to a POST that results in a creation. Should be combined with a Location header pointing to the location of the new resource |
| 202 | Accepted |
| 203 | Non-Authoritative Information |
| 204 | No Content --- Response to a successful request that won't be returning a body (like a DELETE request) |
| 205 | Reset Content |
| 206 | Partial Content |

## 3xx: Redirection

Further action must be taken in order to complete the request

| Code | Explanation |
| ---- | ----------- |
| 300 | Multiple Choices |
| 301 | Moved Permanently |
| 302 | Found |
| 303 | See Other |
| 304 | Not Modified --- Used when HTTP caching headers are in play |
| 305 | Use Proxy |
| 307 | Temporary Redirect |

## 4xx: Client Error

The request contains bad syntax or cannot be fulfilled

| Code | Explanation |
| ---- | ----------- |
| 400 | Bad Request --- The request is malformed, such as if the body does not parse |
| 401 | Unauthorized --- When no or invalid authentication details are provided. Also useful to trigger an auth popup if the API is used from a browser. |
| 402 | Payment Required |
| 403 | Forbidden --- When authentication succeeded but authenticated user doesn't have access to the resource. |
| 404 | Not Found --- When a non-existent resource is requested. |
| 405 | Method Not Allowed --- When an HTTP method is being requested that isn't allowed for the authenticated user |
| 406 | Not Acceptable |
| 407 | Proxy Authentication Required |
| 408 | Request Time-out |
| 409 | Conflict |
| 410 | Gone --- Indicates that the resource at this end point is no longer available. Useful as a blanket response for old API versions. |
| 411 | Length Required |
| 412 | Precondition Failed |
| 413 | Request Entity Too Large | |
| 414 | Request-URI Too Large |
| 415 | Unsupported Media Type --- If incorrect content type was provided as part of the request. |
| 416 | Requested range not satisfiable |
| 417 | Expectation Failed |
| 422 | Unprocessable Entity --- Used for validation errors |
| 429 | Too Many Requests --- When a request is rejected due to rate limiting |

## 5xx: Server Error

The server failed to fulfill an apparently valid request

| Code | Explanation |
| ---- | ----------- |
| 500 | Internal Server Error |
| 501 | Not Implemented |
| 502 | Bad Gateway |
| 503 | Service Unavailable |
| 504 | Gateway Time-out |
| 505 | HTTP Version not supported |


{{% notice info %}}
**This documentation is work in progress (WIP)**

Feel free to [open an issue](https://bitbucket.org/pkollitsch/booka-docs/issues?status=new&status=open) for a topic you miss, or give back to the project by cloning the repository and [commit changes by yourself](https://bitbucket.org/pkollitsch/booka-docs/src).
{{% /notice %}}
