### Bearer Authorization
**1-What is a JSON Web Token (JWT)?**
A JSON Web Token (JWT) serves as a concise and secure method for exchanging data between multiple entities in the form of a JSON object. It comprises a header, payload, and signature. JWTs find application in web applications and APIs to facilitate authentication and authorization processes.
**2-When should we use JSON Web Tokens?**
JWTs are utilized in various contexts where robust authentication and authorization mechanisms are necessary. They are commonly employed in web applications, mobile applications, and APIs to ensure secure authentication and authorization processes.
**3-Claims are expected in which structural component of a JWT?**
Payload component of JWT

##### Are JWTs Secure?

**1- If I get a JWT and I can decode the payload, how can we call that secure?**
>JWT security relies on digital signature verification for integrity and authenticity. Secure transmission protocols like HTTPS prevent interception and tampering. Implementing these measures reduces unauthorized access risk.

**2-If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.**
>Both must know the secret key that is used for generating and verifying the token's signature. The secret key is appended to the signature part of the JWT

**3- Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.**
>Content and secret key should be shared securely. Recruiters must store the key offline, ensuring its confidentiality and not sharing it with others.

##### JWTs Explained

**1- Why use JWT?**
>JWTs are widely favored in web and application development due to their ability to offer secure authentication, authorization, and information exchange.

**2- JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.**
>JWTs are compact and self-contained information packages that streamline the secure transmission and handling of data. They eliminate the reliance on external storage or complex setups, simplifying the overall process.

**3-What are the three components (the structure) of a JWT signature?**

* Header.

* Payload 

* Signature

