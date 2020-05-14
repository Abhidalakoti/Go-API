# Go-API
A Golang RESTful API demonstrating a full suite of CRUD operations


This is a fully fledged  fully-fledged REST API that exposes GET, POST, DELETE and PUT endpoints that will subsequently allow  to perform the full range of CRUD operations.In this there is no interaction with any backend database technologies to store the articles that we’ll be playing with. However,  REST API is written in such a way that it will be easy to update the functions  defined so that they make subsequent calls to a database to perform any necessary CRUD operations.

Postman an API client tool which helps to test the API's was used during writing the operations.



gorilla/mux router has been used for matching incoming requests against a list of registered routes and calling handler for the route that matches the URL or other consditions.Its features are:
* Requests can be matched based on URL host, path, path prefix, schemes,
  header and query values, HTTP methods or using custom matchers.
* URL hosts, paths and query values can have variables with an optional
  regular expression.
* Registered URLs can be built, or "reversed", which helps maintaining
  references to resources.
* Routes can be used as subrouters: nested routes are only tested if the
  parent route matches. This is useful to define groups of routes that
  share common conditions like a host, a path prefix or other repeated
  attributes. As a bonus, this optimizes request matching.
* It implements the http.Handler interface so it is compatible with the
  standard http.ServeMux.
