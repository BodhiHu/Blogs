# SW Development Workflow - A Samsara

```
                                                                                                                                                                                                                   
      ---------> Main (dev branch)                                                                                                                                                                                                      
      ^                  |                                                                                                                                                                                          
      |                  | To start developing for a new task                                                                                                                                                                                          
      |                  | (feature or bugfix),
      |                  | Create new branch based on "main"
      |                  |
      |                  V                                                                                                                                                                                           
      |          CD pipeline passed
      |                  |                                                                                                                                                                                          
      |                  |                                                                                                                                                                                          
      |                  V                                                                                                                                                                                          
      |       Code & Demo review passed                                                                                                                                                                                           
      |                  |                                                                                                                                                                                          
      |                  |                                                                                                                                                                                          
      |                  V                                                                                                                                                                                          
      |         Reviewer Merge MR/PR  ------ Deploy to Staging ---------> Staging                                                                                                                                         
      |                                                                      |                                                                                                                                          
      |                                                                      | Bugs fixed
      |                                                                      | Tests passed
      |                                                                      |                                                                                                                                          
      |                                                                      V                                                                                                                                          
      |                                                               Deploy to Prod -------------->  Production                                                                                                                                         
      |                                                                                                   |                                                                                                                                          
      |                                                                                                   | Test & Verify
      |                                                                                                   | on production
      |                                                                                                   |                                                                                                                                          
      |                                                                                                   V                                                                                                                                          
      |                                                                                              if found bugs                                                                                  
      |                                                                                                   |                                                                              
      |                                                                                                   |                                                                              
      <---------------------------------------------------------------------------------------------------<                                                                              
                                                Raise a bugfix on main, repeat the Samsamra                                                                                                                                                                   
                                                                                                                                                                                                                   
                                                                                                                                                                                                                    
```
