---
layout: doc
title: openApiv2-lint
permalink: /tools/openapiv2-lint
---

# openApiv2-lint

Lint the endpoint provided using OpenAPI v2 spec. It will lint from the file
passed as first parameter otherwise it will read the endpoint specification to
lint from standard input.

This tool accepts an endpoint specification written using OpenAPI v2 as input
and outputs the same specification, if no erros are encounterd, or the list of
errors deteted.

In case of error an error code of 1 is returned, 0 otherwise.