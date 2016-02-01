# Test Nava Planetary Sound API

**Assumptions**

1. Parameter q is used to search text in description to filter results
2. The Sound API service is currently not working with parameter q specified therefore correspoinding tests will fail
3. Nasa developer key has hourly limit of 1,000 requests and is used in general API calls to avoid over rate limit exception

## Test Sound Search Text
* No Search Text 
* Valid Search Text 
* Invalid Search Text Format 
* Empty Search Text
* Null Search Text

## Test Sound Return Limit
* Default Limit 
* Valid limit Size 
* Invalid Limit Format 
* Max Limit Size
* Out of Bound Limit
* Negative Limit Size
* Zero Limit Size

## Test API Key 
* No API Key
* Non Exist API Key
* Invalid API Key 
* Empty API Key
* Null API Key
* Demo API Key
* Developer API Key

## Test Parameter Permutations
* No Parameters
* All Parameters
* Text and Limit Parameters 
* Text and Key Parameters 
* Limit and Key Parameters
* Search Text Only Parameter
* Return limit Only Parameter
* API Key Only Parameter
