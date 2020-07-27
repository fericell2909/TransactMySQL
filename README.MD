
![N|Solid](https://camo.githubusercontent.com/e0e3e4ad47134bff0f4d1f01c8e0882b2240c486/68747470733a2f2f7777772e6d7973716c2e636f6d2f636f6d6d6f6e2f6c6f676f732f6c6f676f2d6d7973716c2d313730783131352e706e67)

### Scripts

    Functions :
      
        1. Name Function : extract_string 
           Description :  
           we can extract a portion of a string separated by a specific character in the desired position. 
           Example: 
               Parameters
               _x :  'marco*estrada* lopez' 
               _delim_ : '*'
               _pos :  1
               
               select extract_string(_x,_delim_,_pos);

               select extract_string('marco*estrada* lopez','*',1);
               
               Result is equal :   marco  

               select extract_string('marco*estrada* lopez','*',2);

               Result is equal : estrada

               select extract_string('marco*estrada* lopez','*',3);

               Result is equal : lopez 

        2. Name Function : UpperCaseWords 
           Description :  
           Transform of Words with the First Letter to Upper 
           Example: 
               Parameters
                p_string :  'marco estrada lopez'
               
               select UpperCaseWords('marco estrada lopez');

               Result is equal : Marco Estrada Lopez  

### More functions