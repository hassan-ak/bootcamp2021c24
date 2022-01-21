# Step07 - Open API Testing and Development with Swagger and Postman

## Class Notes

- [Designing APIs with Swagger and OpenAPI](https://www.manning.com/books/designing-apis-with-swagger-and-openapi)
  - Chapter 06
    - Path parameters
      - Path parameters are described in the same way as as query parameters. Each parameter requires the following properties to describe it.
        1. name — name of the parameter.
        2. in — the location of the parameter (query, path, header, cookie).
        3. schema — schema of the parameter (string, number, array, boolean, null).
      - Parameters can also include the following properties (we’ll cover some of them later on) required — Whether or not this parameter is required (which for path parameters must ALWAYS be true).
        1. example — An example of the parameter’s value.
        2. examples (plural) — List of examples, which is mutually exclusive with . example
        3. deprecated — Whether or not this parameter is marked as deprecated.
        4. style — How the value will be serialized.
        5. explode — Whether or not to create a separate value for arrays/objects.
        6. allowedReserved — Allow reserved characters (ie: / or ?). Useful for when you want to catch-all parameter.

## Reading Material

- [Design and Prototype an API](https://www.youtube.com/watch?v=r4kb3jOSsmk&ab_channel=Postman)
- [API Testing and Development with Postman Book](https://www.packtpub.com/product/api-testing-and-development-with-postman/9781800569201)
- [Book on Oreilly Website](https://www.oreilly.com/library/view/api-testing-and/9781800569201/)
- [Book Repo](https://github.com/PacktPublishing/API-Testing-and-Development-with-Postman)
