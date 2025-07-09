''' mermaid
sequenceDiagram
  participant User
  participant Browser
  participant Server

  User -->> Browser: Types note and clicks "Save"
  Browser -->> Server: POST /new_note (with note data)
  Server -->> Browser: 302 Redirect to /notes
  Browser -->> Server: GET /notes
  Server -->> Browser: HTML + Updated notes lists
  Browser -->> User: Displays updated notes

'''
  

    

    
  
