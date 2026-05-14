---
date: 2026-04-16
title: API vocabulary essentials
authors:
  - guest
description: A concise overview of the most important API design terms for readers new to API development.
tags:
  - api
  - design
  - vocabulary
  - rest
  - openapi
---

# API vocabulary essentials

This article explores the most important terms used in API design and development.

## 1. API

An API, or Application Programming Interface, is a set of rules that lets one software system communicate with another.

## 2. Endpoint

An endpoint is a specific URL where an API exposes a resource or action, such as `/users` or `/orders/42`.

## 3. Resource

A resource is the thing an API manages, like a user, product, invoice, or post.

## 4. Request

A request is the message a client sends to an API to ask for data or trigger an action.

## 5. Response

A response is the message the API sends back after processing a request.

## 6. HTTP method

An HTTP method describes the action the client wants to perform, such as `GET`, `POST`, `PUT`, `PATCH`, or `DELETE`.

## 7. Status code

A status code is the numeric result of a request, such as `200` for success, `201` for created, or `404` for not found.

## 8. Parameter

A parameter adds input to an API call. Common types include path parameters, query parameters, and header parameters.

## 9. Payload

A payload is the data sent in a request body or returned in a response body, often in JSON format.

## 10. Authentication

Authentication is the process of verifying who a client or user is, often using an API key, token, or OAuth flow.

## 11. Authorization

Authorization determines what an authenticated user is allowed to do, such as reading data but not deleting it.

## 12. Rate limiting

Rate limiting controls how many requests a client can make in a given time period to prevent abuse and keep the API stable.

## 13. Versioning

Versioning is the practice of managing changes to an API over time, often by using paths like `/v1/` and `/v2/`.

## 14. Schema

A schema defines the structure and rules for data, including required fields, data types, and formats.

## 15. Pagination

Pagination splits large result sets into smaller pages so responses stay fast and manageable.

## 16. Sorting

Sorting lets clients control the order of returned data, such as by name, date, or price.

## 17. Filtering

Filtering narrows results based on criteria, such as only showing active users or published posts.

## 18. Serialization

Serialization converts data into a format that can be sent over the network, such as JSON.

## 19. Deserialization

Deserialization converts received data back into a usable object or structure in code.

## 20. Documentation

Documentation explains how to use the API, including endpoints, request formats, examples, and error handling.

## Formatting notes

For MkDocs Material, this page works well with clear headings, short paragraphs, and simple Markdown structure. You can also add callouts, code blocks, and tables later if you want to expand the article.  