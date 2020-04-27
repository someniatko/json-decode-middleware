# Json Decode Middleware

Simple PSR-15 middleware, which decodes JSON body of a PSR-7 Server Request,
if it has a `Content-Type: application/json` header, into array, which you can
obtain via `getParsedBody()` call on the Server Request.
