
Thymeleaf Layout Dialect and Spring Boot - working example
==========================================================

This is an example showing how easy it is to extend Spring Boot based application using Thymeleaf templates with "Thymeleaf Layout Dialect" (that allows to 'decorate' Thymeleaf templates with common 'layout' templates).

Notes
-----
- as 'spring-boot-starter-thymeleaf' provides all configuration required to out-of-the-box working Thymeleaf there's no need to configure manually any 'templateEngine', 'templateResolver' etc.
- due to way the templateResolver suffix is configured instead of `layout:decorator="Layout.html"` (as in most samples) only `layout:decorator="Layout"` (no `.html`) should be used.

This project derives from pieces of code from https://github.com/ultraq/thymeleaf-layout-dialect and https://github.com/ewolff/user-registration.