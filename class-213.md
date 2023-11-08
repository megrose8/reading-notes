# Local Storage: 
## Guiding Questions:
1. Why Would a developer use local storage for a web application?    
*Storing data with HTTP on the web is stateless. The state will be reset the next time you open it. Local storage allows you to store the state of your interface. This way you can read the state out to a user when they return.*  
* Cookies: Text file hosted on user's computer and connected to domain.   
* Local Storage in HTML5: Modify the local storage object in JS `localStorage.setItem` and/or `localStorage.getItem`
2. What information should not be stored in local storage?  
* Personal user information should not be stored in local storage.
3. Local storage can store what type of data? How would you convert it to that type before storing?    
* Local storage can only store strings in keys. It cannot store objects correctly. You can fix this by using `JSON.stringify` and `JSON.parse`

## Curiosities:   
* What solutions have been found to solving the abuse of storing user information?    
* If cookies are outdated, why does the pop-up asking for cookies always appear?

