# Trinkerr Live Interview for React

### Problem Statement
1. You need to create the search functionality, where the user can search a desired stock from the list of stocks. You will require API `1` and `2` from the Documentation. You need to make the API fetching as efficient as possible.
2. You need to create a simple form, where the user can send a POST request to API number `3` and add the relevant data, and make sure you handle the necessary errors which Arise.

### Note
You need to implement the problem statement in order. Only if you are done with problem statement `1`, you need to move the next one. All the very best.
### API Documentation

BASE_URL: `http://3.108.225.220:5000`

1. `GET /api/user-access-token`
    ```
    This API will fetch the user-access-token, which will be required
    in the headers of the other private API Requests
    ```
2. `GET /api/data?search_string=`
    ```
    This API will require the user-access-token as one of the header
    parameters, otherwise it will throw an unAuthorized Error. It takes
    search_string as one of the query parameters and returns the data
    which matches the string. 
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
