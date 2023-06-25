# PYTHON-DJANGO-PROJECT
Project Description: CMS Application API

The CMS Application API is a Django-based web service that provides a comprehensive set of CRUD (Create, Read, Update, Delete) operations for managing users, posts/blogs, and likes. This API allows users to create, read, update, and delete user accounts, create, read, update, and delete posts/blogs, and also like/unlike posts.

Key Features:

User Management: The API allows users to create, retrieve, update, and delete user accounts. Each user account contains information such as name, email, password, and other relevant details.

Post/Blog Management: The API enables users to create, retrieve, update, and delete posts/blogs. Each post/blog consists of a title, description, content, creation date, and other relevant details. Users can also specify whether a post/blog is public or private.

Like System: The API incorporates a like system, allowing users to like or unlike posts/blogs. Each like is associated with a specific post/blog and user. The API provides the ability to create, retrieve, update, and delete likes.

Access Control: The API enforces access control rules to ensure proper data protection. PUT and DELETE operations for posts/blogs are restricted to the owner of the post/blog. Only the owner of a private post/blog can access it, while public posts/blogs can be accessed by any user.

Post/Blog Likes Count: The API includes a feature to retrieve the number of likes for each post/blog. When retrieving all posts/blogs, the response includes the likes count for each post/blog, providing valuable insights into the popularity of the content.

Single Query Retrieval: The API optimizes database queries by retrieving both post/blog details and their associated likes in a single query. This efficient retrieval ensures improved performance and reduces unnecessary database operations.

The CMS Application API offers a secure and efficient solution for managing users, posts/blogs, and likes within a Content Management System. It provides a well-defined set of endpoints that can be easily integrated with frontend applications or used as a standalone backend service.
