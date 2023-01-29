# weather-app
build a weather app using javascript 

#index.html file:
- Explain comments above element
- First link element will connect html file to css file
- Content of element represents main content of website; add text, headers, images, etc here
  -  Within tag can add elements such as regular text or headings
  - Pay attention to class/id keywords
- Run file now to view output
- No information about weather shows because we have not coded in javascript file yet
- Content is not styled either


#style1.css file:
- Css file allows for styling of elements on a website, works in conjunction with html file
- Keywords added before curly brackets are called selectors
- Hover over each property to understand what it does (pretty self explanatory :) )
- Edit name of file to be style.css
- Rerun code; show how now that the css file name matches what is in the html file, the html file can communicate with the css file and vice versa


#script.js file:
- How to get weather data? Use API from website into our app
- API is a medium between server (website) and client (users on our app) to serve data based on client’s request
- We need API key from this website https://openweathermap.org/
    - Create account
    - Click on API on top menu 
    - Current weather data - subscribe
    - Select free option “get API key”
    - Find API key in “My API keys” on top (will be different for everyone)
- We can use the unique API key to view the json file by adding the name of our selected city and the API key to the url at the beginning of the js file