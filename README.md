# Trinkerr Live Interview for React

### Problem Statement
1. You need to create the search functionality, where the user can 


### API Documentation

BASE_URL: `http://3.108.225.220:5000`

1. `GET /api/user-access-token`
    ```
    This API will fetch the user-access-token, which will be required
   in the headers of the other private API Requests
    ```
2. `GET /api/data`
    ```
    This API will require the user-access-token as one of the header
    parameters, otherwise it will throw an unAuthorized Error.
    ```
3. `POST /api/data`
   ```
   This API will also require the user-access-token as one of the header
   parameters. The data should be in the format as fetched from the GET 
   API call. 
   ```
   `Example`
   ```json
   {
      "name": "....",
      "ltp": 20,
      "lcp": 30
   }
   ```
