### Authentication
**Securing Passwords**
**1- Explain to a non-technical friend how you would safely hash and store a password.**
> To securely hash and store a password, the process entails transforming it into a distinct and jumbled sequence using a specialized function. To enhance its security, we incorporate a random value known as a salt. Subsequently, we store this encrypted version within a safeguarded database, never storing the actual password itself.
 
**2 - What is Bcrypt?**
The purpose of the bcrypt algorithm is to securely encrypt passwords, making it challenging for attackers to guess them due to its ability to significantly slow down their attempts.


**3- Q3: How are username:password in Basic Auth encoded?**

Basic Authentication encodes the username and password using Base64 encoding. The encoded credentials are then included in the "Authorization" header of the HTTP request as "Basic"

#### Basic Auth
**1- What is Basic Authentication?**
>Basic Authentication is a widely used and straightforward authentication protocol in web-based applications and APIs. It is part of the HTTP protocol and provides a simple method for user authentication.

**2- What properties are necessary in the header of a Basic Auth request?**
>
The "Authorization" property is used to indicate to the server that authentication information is included. The encoded "Credentials" property contains the username and password, which are encoded using Base64 to enhance their readability protection.

**3-How are username:password in Basic Auth encoded?**
>Basic Authentication encodes the username and password using Base64 encoding, combining them with a colon separator ("username:password") before encoding.

#### OWASP auth cheatsheet

**1- Define the authentication process to a non-technical recruiter.** 
>Authentication is the procedure used to validate the identity of an individual seeking access to a system, website, or application. Its primary purpose is to verify that the person attempting access is indeed the individual they claim to be.

**2- How should your error messaging respond (both HTTP and HTML)? Why?**
>Error messaging in both HTTP and HTML should prioritize delivering clear and user-friendly feedback. The goal is to enhance the user experience, facilitate troubleshooting, and provide meaningful information regarding encountered errors.















