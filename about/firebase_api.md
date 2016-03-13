 **Firebase REST API**
 
    * What operations does the Firebase REST API support?
    
    Data from our Firebase database can be read by issuing an HTTP GET request to an endpoint:
    
    * Do I need to authenticate with Firebase to read or create data?
    
    yes?
    
    * What format does Firebase expect data to be in?
    
    list of objects
    
**Restangular**
  
    * How do I configure a REST-ful API like Github?
    
    You can set all these configurations in RestangularProvider or Restangular service to change the global configuration or you can use the withConfig method in Restangular service to create a new Restangular service with some scoped configuration
    
    * How would I request a list of...
    
      * ...Repos for the class Org?
      
      
      
      * ...Issues for the class Repo?
      
      
      
      * ...Issues for a specific Milestone?
      
      customGET(path, [params, headers]): Does a GET to the specific path. Optionally you can set params and headers.
      
**`ngRouter`**

    * How do I define...
    
      * ...a route for my application with `ngRouter`?
      
      
      
      * ...dynamic pieces (params) to routes?
      
      
      
      * ...the template to load for a route?
      
      
      
      * ...the controller to trigger for a route?
      
      
      
    * How do I retrieve...
    
      * ...the params from a route in a controller?
      
      
      
      * ...the controller for a route in the view?
