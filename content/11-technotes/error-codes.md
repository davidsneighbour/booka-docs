---
title: "Error Codes"
date: 2018-04-06
weight: 1101
chapter: true
---

# Error Codes

## Core Class Error Indicators

| ID | Class | Notes |
| --- | ----- | ----- |
| 300### | Users |  |
| 305### | Userroles | |
| 307### | Userrights | |
| 307### | AccessControl | |
| 310### | Notifications | |
| 330### | Customers | |
| 335### | CustomerData | |
| 339### | Countries | |
| 340### | Settings | |
| 343### | Flags & Flagitems | |
| 345### | Setup | |
| 350### | Agencies | |
| 355### | Agencygroups | |
| 360### | Menu | |
| 361### | Messages | |
| 362### | Page | |
| 363### | PageObjects | |
| 364### | Pager | |
| 365### | Stylesheets | |
| 360### | Menu | |
| 370### | Transactions | |
| 375### | Accounts | |
| 377### | AccountingClasses | |
| 380### | Notifications | |
| 390### | Database | |
| 391### | Filepath | |
| 392### | Helpers | |
| 398### | Log | |
| 399### | ErrorScreen | |

## Tour Class Error Indicators

| ID | Class | Notes |
| --- | ----- | ----- |
| 500### | Tours |  |
| 505### | Categories | |
| 509### | Calendar | |
| 510### | Seats | |
| 520### | Addons | |
| 522### | Addonselections | |
| 530### | Pickupsets | |
| 535### | Pickupspots | |
| 540### | Prices | |
| 580### | Bookings | |
| 589### | RecentBookings | |
| 590### | Invoices | |

## CRUD

| ID | Error | HTTP status code | Notes |
| --- | ----- | ---------------- | ----- |
| ###510 | index not implemented | 412 | |
| ###520 | get not implemented | 412 | |
| ###521 | get-parameter $id missing | 412 | |
| ###522 | internal error while retrieving data for $id | 500 | |
| ###530 | post not implemented  | 412 | |
| ###540 | put not implemented | 412 | |
| ###550 | delete not implemented  | 412 | |
| ###551 | parameter $id missing | 412 | |
| ###552 | internal error while setting is_deleted to 1 | 500 | |
| ###553 | internal error while deleting row with id $id | 500 | |
| ###561 | no labelling information available | 500 | |


{{% notice info %}}
**This documentation is work in progress (WIP)**

Feel free to [open an issue](https://bitbucket.org/pkollitsch/booka-docs/issues?status=new&status=open) for a topic you miss, or give back to the project by cloning the repository and [commit changes by yourself](https://bitbucket.org/pkollitsch/booka-docs/src).
{{% /notice %}}

