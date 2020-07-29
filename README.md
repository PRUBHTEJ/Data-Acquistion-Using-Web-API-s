# Data Acquistion Using Web API's
This repository contains information about how we may use different API requests to acquire data from a particular website. 

(API --> Application Programming Interface)

##### Structure of an API:

``` URL + ? + Query Parameter(contains key and value pairs)``` 

Whenever we send a GET request to a particular website, in most of the cases the data is returned in the form of an image, JSON or an XML file.
Also in the case of a JSON file, we can convert it to a string by using the ```json.dump(json_data)``` function present in the JSON library.

Typically a web browser sends a GET request to a website, so as to acquire data. But here we've written a script in Python programming language which will be sending various kinds of requests to the website.

#### The following Python libraries have been used:

1. urllib (It is a traditional library, that has been used for a long time for acquiring the data)

2. requests( It is one of the most downloaded libraries as far as the Python programming language is concerned & works really well with Python3) 

The following API requests have been used:
1. GET
2. POST
3. DELETE
4. PUT
5. PATCH

API's from the following websites have been used as a tutorial so as to depict the steps for acquiring the data from a particular website:

1. **[OpenWeatherMap API]()**

2. **[FaceBook API]()**

3. **[Google API]()**
