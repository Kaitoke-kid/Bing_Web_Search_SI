# Bing_Web_Search_API

This is a REST API sending get requst which takes name as a params that name is a user wants to search in a Bing webpage. API gets request from the Azure cognitive service in that subpart it calls bing web search url and fetch all the details as par the condition. The output of the API is all the corresponding URL's related to that specific word. Anyone can use this API to search a specific word from the Internet.

Technologies:-
Node.JS Express

Instructions to use API:-
For specific word URL to enter in the postman: http://206.81.14.184/:name,
Request Type: Get,
Set headers: Content-Type to application/x-www-form-urlencoded,
In: Params,
In URL write any word in replace of name,
For example:- http://206.81.14.184/ShalvikShah,
It will search the results for ShalvikShah and return JSON data from the azure bing web search API.

