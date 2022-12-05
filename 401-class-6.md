# 401 Class 6 Reading Notes - Authentication

[Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

1. Explain to a non-technical friend how you would safely hash and store a password.
You have to create hasing algorithms that will has your data. Nashing cannot be reversed so it's good to always check data that does not have to be translated or read directly. With hashing, you can store a password without worrying about the risk of it being read directly.

2. What is Bcrypt?
An algorithm that is an adaptive hash function based on the Blowfish symmetric block cipher cryptographic algorithm and introduces a work factor (also known as security factor), which allows you to determine how expensive the hash function will be. it Uses Key Stretching to generate hash values in different time spans, this helps defend against brute force attacks.

3. Why might you use something like Bcrypt?
Bcrypt is useful because of how understandable it is across multiple languages as well as it being a solid hashing algorithm.

[Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

1. What is Basic Authentication?
a method (like REST) that request credentials to a HTTP router for it to be authorized to allow access to a source.

2. What properties are necessary in the header of a Basic Auth request?
- Header
- Username & password
- To encode/authenticate, use prefix of “Basic”

3. How are `username:password` in Basic Auth encoded?
- Through Base64

[OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)
1. Define the authentication process to a non-technical recruiter.
Authentication is the process of verifying that an individual, entity or website is whom it claims to be. Authentication in the context of web applications is commonly performed by submitting a username or ID and one or more items of private information that only a given user should know.

2. How should your error messaging respond (both HTTP and HTML)? Why?
Our error messaging should respond as generically as possible. In text, this should be something like "Login failed; Invalid user ID or password," as opposed to "Login for user foo; invalid password" or "Login failed; account disabled." For HTTP, the codes should be 200 for positive (OK) responses or 403 (Forbidden) for negative responses. Anything too specific will reveal unnecessary information to attackers. By having this variation, we could create discrepency factors that will give hints to attackers about specific users and/or passwords that they're targeting.

3. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

[bcrypt docs](https://www.npmjs.com/package/bcrypt)

1. Looking ahead at this module’s course schedule, What do you look forward to learning?
I am looking forward to learning more about React and implementing that into cool projects.

2. What are your learning goals after reading and reviewing the class README?
To have a deeper understanding of all the topics covered in this course
