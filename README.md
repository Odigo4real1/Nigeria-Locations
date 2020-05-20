# Nigeria-Locations
This repo is for free contribution of State, LGA &amp; Communities in each LGA of a state in Nigeria.

HOW TO ENTER DATA
 
 LGA DATA
 The repo include a state.js file. As you know there are 37 states in Nigeria plus FCT. Volunteers will pick a state and enter the LGA data and submit.
 Say you want to enter for Abia, the LGA data should be in the format:

       {

name: 'Abia', value: 'abia', 

lgas: [
                {name: "Aba", value: 'aba'},
                
                {name: "Oru", value: 'oru'}
                
             ]
}

COMMUNITY DATA
 Community data will be source online and links may be provided by volunteers to list of communities in a LGA. Volunteers will pick a LGA and enter the communities data in the format below.
 Say you want to enter for Abia, the LGA data should be in the format:
   
          
                 states : [
                 
              { name: 'Abia', value: 'abia', 
              
              LGA: [{name: 'Aba', value: 'aba', 
                
                      communities: [
                      
                        {name: "Orumba", value: 'orumba'},
                        
                        {name: "Onitsha", value: 'onitsha'},
                        
                        ]} 
                        
    },  
    ]
    
            
            
 
