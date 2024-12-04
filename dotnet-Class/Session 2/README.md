HTTP METHOD:
1. GET
The GET method is used to retrieve data from a server without affecting the state of the resource. It sends data through the URL in the form of query parameters. Commonly used for fetching web pages or specific data, GET requests do not include a request body.

2. POST
The POST method is used to send data to a server to create or update a resource. The data is included in the body of the request, often in JSON or form-data format. It is typically used for actions like submitting forms or uploading files.

3. PUT
The PUT method replaces the current representation of a resource with the new data provided in the request body. It is idempotent, meaning repeated requests with the same data yield the same result. Commonly used for updating existing resources on the server.

4. PATCH
PATCH is used to make partial updates to a resource, as opposed to completely replacing it like PUT. It is not necessarily idempotent and typically includes only the fields to be updated in the request body. Often used for updating specific attributes of a resource.

5. DELETE
The DELETE method is used to remove a resource from the server. It is idempotent, as performing the action multiple times yields the same outcome—ensuring the resource is deleted. Commonly used for actions like removing user accounts or records.

6. HEAD
The HEAD method is similar to GET but retrieves only the headers of the response, without the body. It is often used to check resource availability or metadata before making a full GET request. HEAD is useful for tasks like verifying links or cache validation.

7. OPTIONS
OPTIONS is used to describe the communication options available for a resource. It returns headers detailing the allowed HTTP methods and other capabilities of the server. Often used in CORS (Cross-Origin Resource Sharing) preflight requests.

8. CONNECT
The CONNECT method is used to establish a tunnel to the server, often for secure SSL/TLS connections. It is primarily used for proxy servers to facilitate secure communication. Common in scenarios like HTTPS connections through HTTP proxies.

9. TRACE
The TRACE method performs a message loop-back test to see what changes or additions are made to the request by intermediate servers. It is mainly used for debugging or testing purposes. TRACE is generally disabled in production systems due to security risks like cross-site tracing attacks.
10. LINK
The LINK method is used to establish a relationship between two resources. It allows clients to create associations or links explicitly. This method is rarely used in modern applications and is not widely supported.

11. UNLINK
The UNLINK method removes a relationship between two resources. It undoes links previously created by the LINK method. Like LINK, it is not commonly used in contemporary applications.

12. PROPFIND
PROPFIND is an extension of HTTP used by WebDAV (Web Distributed Authoring and Versioning). It retrieves properties, stored as metadata, for a resource or a collection of resources. Often used in collaboration or version-controlled environments for resource management.

13. PROPPATCH
The PROPPATCH method is used to change or update properties of a resource in WebDAV. It is typically used for managing metadata on files or folders. Changes can involve setting new values or removing existing ones.

14. MKCOL
The MKCOL method creates a new collection, such as a directory or folder, in WebDAV. It is analogous to creating a directory in a file system. The server responds with a success status if the collection is created successfully.

15. COPY
COPY is a WebDAV method that duplicates a resource from one location to another. It is used to create exact copies of files or directories. Additional headers can define whether metadata and permissions are copied as well.

16. MOVE
MOVE is another WebDAV method used to move a resource to a new location. It is equivalent to a "cut and paste" operation, deleting the resource from the source after it is successfully created at the destination.

17. LOCK
The LOCK method is used to lock a resource to prevent modifications by others in WebDAV environments. Locks are often used in collaborative editing to avoid overwrites. It can apply to both individual files and entire collections.

18. UNLOCK
UNLOCK is the counterpart to LOCK, used to remove a lock on a resource in WebDAV. This allows other users or processes to modify the resource. Proper credentials are typically required to unlock a resource.

19. SEARCH
The SEARCH method allows clients to perform complex queries against a set of resources. It is commonly used in WebDAV to search for resources based on metadata or content. The request body specifies the search criteria in a query language like XML.
