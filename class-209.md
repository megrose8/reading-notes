# Forms and JS Events
## Things I want to Know More About


## HTML Forms: [MDN Guide](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)
* Forms: Allow users to enter data which is sent to a web server for processing and storage.  
    * Made up of form controls. Options can be single/multi-line fields, dropdown boxes, checkboxes, or radio buttons. They are created using the `input` element.  
    * Form validation enforces specific formats or values to be entered.  
* Creating a form: `form` element defines the form. `action` defines the URL wehere the data should be submitted. `method` defines which HTTP method to send the data with (`get` or `post`)
    `<form action = "/my-handling-form-page" method="post>  </form>`  
* `<label>` for each input type. EX `<label form="name >Name:</label>`
* `<input type` controls what the option is for the user to inpu7t their data.  
* `<text area` is where the multiline text field would me inserted.  
* `<button>` element allows user to submit data.   

## Introduction to Events 
* Events: System produces a signal when an event occurs and code runs. Events are typically tied to a specific item within the browser window.   
* To react to an event use an **event handler** , when the code block runs in response we are "registering the event handler"  
* `addEventListener()` is the recommended method for adding event handlers. We can pass in parameters to the method. Including how we indicate to listen to the event (click, mouseover, etc) and the function to call when the event occurs.
