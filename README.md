
import axios from "axios";


axios.get('/user?ID=12345')

 .then(response => {
	 
          console.log( response.data);
	  
 })
 .catch(error => {
        console.log("Error to load reports list");
 });
