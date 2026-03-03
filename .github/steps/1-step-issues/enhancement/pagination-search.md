# 📄 Support Pagination and Search in API

The larger backend exposes paginated/searchable endpoints for listing
workshops, filtering by title/provider/subject, and returning metadata such as
`PaginatedResult<T>` or `SearchResult<T>`.

Enhancements:

- Add query parameters `page` and `pageSize` to `GET /activities`.
- Implement server-side pagination logic (skip/limit or database cursor).
- Accept additional filters like `title`, `providerId`, or `day`.
- Return a response object containing data + pagination metadata.

This improves performance and scalability when the number of activities
grows.
