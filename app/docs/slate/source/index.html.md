---
Title: API Reference

Language_tabs:
  - ruby

Toc_footers:
  - <a href='http://github.com/tripit/slate'>Documentation Powered by Slate</a>

Includes:
  - errors

Search: true
---

# Introduction

API docs

# Get user information

## V1

## HTTP requests

`GET http://my-site/api/v1/users/<id>`

## Request params

Key | Required | description
-----| --------| -------
id   |  Yes      | user id|

## Response

```json

{
  "user":
  {
    "id":1,
	"email":"test-user-00@mail.com",
	"name":"test-user-00",
	"activated":"2015-05-02T07:47:14.697Z",
	"admin":false,
	"created_at":"2015-05-02T07:47:14.708Z",
	"updated_at":"2015-05-02T07:47:14.708Z"
   }
}
