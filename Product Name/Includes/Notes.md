
# Notes 

## Endpoints

Base endpoints for this documentation can be referenced from this table:

|Function|Sandbox|Production|
|---|---|---|
|Function name(Links to reference the Api docs for the function could be included here)| Sandbox url | Passport url  |

#### **For parameters like AuthData, Nonce, Timestamp, Tansaction references e.t.c. Descriptions (links to necessary resources and possibly email addresses that could be contacted for more information), Code Samples, Sample Implementations and Pseudocodes should be included here as required. Below are some sample templates.**

## AuthData

> Code Samples are in Java

```java
  
  "Sample Code"
  
```

Brief Description of AuthData which could include links and email addresses that could be contacted for more information.


## Nonce

> Sample implementation in PHP

```php
	
  "Sample implementation code"

```
Brief description of Nonce.

## Timestamps


> Sample pseudo code

```
  "Psedocode to generate timestamp parameter."

```
Brief description of Timestamps which should include link to neccesary resources needed to generate the timestamp.

<!-- ## Transaction References

 <a id="transaction-references"></a>

 > Implementation

 ```
    
    "Sample Implementation"
    
 ```

 Brief description of Transaction reference. -->

#### **For key valued pairs, json or yaml is allowed, which must be specified in the Sample request, and added to the language list in the index file. Below is a sample template in json.**

# Signatures

> Request header sample is in JSON

Signature = url_encode(access_url+endpoint)
```json
{
    "Authorization": "<ACCESS_TOKEN>",
    "Timestamp": "<Timestamp>",
    "Nonce": "Nonce",
    "Signature": "Signature",
    "SignatureMethod": "Signature Method"
}
```


