---
title: 'Proposal: Expand OpenAPI to include RPC APIs'
date: 2017-05-16 19:25:00 Z
tags:
- Definitions
- RPC
---

The OpenAPI 2.0 Specification states that its goal is “to define a standard, language-agnostic interface to REST APIs”. REST is an extremely popular style for implementing APIs that run over HTTP and related protocols (HTTPS, HTTP/2, QUIC). But other transport mechanisms are common and APIs are often defined in ways that correspond to procedure calls. In some ways, procedure calls are more fundamental, as REST APIs are often implemented by systems that convert REST requests into procedure calls.

https://github.com/OAI/OpenAPI-Specification/issues/801?utm_content=buffer080f7&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer