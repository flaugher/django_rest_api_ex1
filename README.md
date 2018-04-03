# README

Example from "Build a Django REST API".
https://codeburst.io/create-a-django-api-in-under-20-minutes-2a082a60f6f3

#### API

CRUD = Create Read Update Delete

(C) Create
POST this JSON to http://localhost:8001/api/note/   (URI must include final "/")
{
  "title": "My Second Note",
  "body": "Even better than the first"
}

(R) GET all notes:
http://localhost:8001/api/note

(D) DELETE note 2:
http://localhost:8001/api/note/2/


#### Requires

[Tastypie](http://django-tastypie.readthedocs.io/en/latest/index.html)
[Postman](https://www.getpostman.com/) Dev Environment
