## 1. Write code that executes asynchronously

The project demonstrates asynchronous execution using async/await when making API requests. This allows the web page to remain responsive while fetching data from the API without blocking the main thread. This can be seen in the event listener below.

<img width="724" alt="Screenshot 2023-11-01 at 20 34 45" src="https://github.com/FAC29A/PHames-portfolio/assets/77605055/88347e45-4cfb-4d54-b80f-8c4872b7df06">

## 2. Use callbacks to access values that aren’t available synchronously

The code does not use callbacks to access values but rather uses async/await to handle promises returned by the fetch method, making it more readable and easier to work with asynchronous operations.

## 3. Use promises to access values that aren’t available synchronously

Promises are effectively used in this project, particularly in the pullFromAPI function, which returns the result of an API call as a promise that is then awaited when calling the function. This demonstrates effective use of promises for handling asynchronous tasks.

## 4. Use the fetch method to make HTTP requests and receive responses

The code utilizes the fetch method to make HTTP requests to an external API (Funtranslations API). This method is used to fetch data from the API and handle the responses.

## 5. Configure the options argument of the fetch method to make GET and POST requests

The chosen API only accepts GET requests. GET is the default request, so no further configuration was required.

## 6. Use the map array method to create a new array containing new values

As our API returned strings rather than arrays, we opted not to use a map array method as it would feel over-engineered.

## 7. Use the filter array method to create a new array with certain values removed

Please see point for map array.

## 8. Access DOM nodes using a variety of selectors

The code effectively accesses DOM nodes using various selectors, such as getElementById, querySelector, and querySelectorAll.

## 9. Add and remove DOM nodes to change the content on the page

The JavaScript effectively manipulates the DOM through the use of innerText.

<img width="734" alt="Screenshot 2023-11-01 at 20 33 31" src="https://github.com/FAC29A/PHames-portfolio/assets/77605055/9d43d5ea-3903-4183-8340-0978d4550833">

## 10. Use consistent layout and spacing

The code demonstrates consistency in layout and spacing through the use of CSS classes, such as parent, child, and specific margin and padding settings.

## 11. Follow a spacing guideline to give our app a consistent feel

The code maintains a consistent spacing guideline by using CSS variables for border widths and margin/padding values, making it easier to maintain a uniform look and feel throughout the application.

## 12. Debug client side JS in our web browser

The web browser console was used throughout to help us debug our code, especially when constructing the event listener.

## 13. Use console.log() to help us debug our code

console.log() was also used for debugging throughout and came in particularly useful when pushing the results of the API call to the DOM.

<img width="612" alt="Screenshot 2023-11-01 at 20 40 35" src="https://github.com/FAC29A/PHames-portfolio/assets/77605055/e9f6077d-9a58-466e-8334-da45de85dfc8">

