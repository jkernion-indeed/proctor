---
layout: default
title: Proctor
exclude_toc: true
---

Proctor is an A/B testing framework written in Java that enables [data-driven product design](http://engineering.indeed.com/blog/2013/05/indeedeng-data-driven-product-design-slides-video/) at Indeed. Proctor consists of data-model, client specification, matrix builder, and Java and JavaScript code generators.

For more details, check out the following blog posts:

- [Proctor: Indeed's A/B Testing Framework](http://engineering.indeed.com/blog/2014/06/proctor-a-b-testing-framework/)

- [How Indeed Uses Proctor for A/B Testing](http://engineering.indeed.com/blog/2014/11/how-indeed-uses-proctor-for-a-b-testing/)

- [Using Proctor for A/B Testing from a Non-Java Platform](http://engineering.indeed.com/blog/2014/09/proctor-pipet-ab-testing-service/)

Source: [https://github.com/indeedeng/proctor](https://github.com/indeedeng/proctor)

# Features
- Consistent tests across multiple applications, services and tools
- Group adjustments without code deploys
- Rule-based group assignment for segmenting users:
  - Logged-in users: 50% A, 50% B
  - Logged-out users: 25% A, 25% B, 25% C, 25% D
- Human-readable test format
- Overriding test groups during internal testing
- Java and JavaScript code generation for A/B tests groups

# Getting Started
Read the [Quick Start]({{ site.baseurl }}/docs/quick-start) guide to start running A/B test using Proctor.

# Example
[https://github.com/indeedeng/proctor-demo](https://github.com/indeedeng/proctor-demo)

# Discussion
Ask and answer questions in our Q&A forum for Proctor: [indeedeng-proctor-users](https://groups.google.com/forum/#!categories/indeedeng-proctor-users)

# License

[Apache License Version 2.0](https://github.com/indeedeng/proctor/blob/master/LICENSE)
