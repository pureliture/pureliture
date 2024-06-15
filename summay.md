### Question 11

### English Version

This question requires that you evaluate the underlined text to determine if it is correct.

Your Azure Active Directory Azure (Azure AD) tenant has an Azure subscription linked to it.

Your developer has created a mobile application that obtains Azure AD access tokens using the OAuth 2 implicit grant type.

The mobile application must be registered in Azure AD.

You require a redirect URI from the developer for registration purposes.

Instructions: Review the underlined text. If it makes the statement correct, select `No change is needed.` If the statement is incorrect, select the answer choice that makes the statement correct.

- A. No change required.
- B. a secret
- C. a login hint
- D. a client ID

<details>
<summary>Answer</summary>
**Correct Answer: A**  
For Native Applications, you need to provide a Redirect URI, which Azure AD will use to return token responses.  
Reference: [Azure AD OAuth 2.0 Implicit Grant](https://docs.microsoft.com/en-us/azure/active-directory/develop/v1-protocols-oauth-code)
</details>
