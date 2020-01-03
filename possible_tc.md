### Generic Experiements



<table> 
    <tr> <th colspan=2>   Pod Delete  </th> </tr>
    <tr > <td rowspan=3> Litmus lib  </td> 
        <td> kill_count == '' </td>
    </tr>
    <tr> 
         <td> kill_count == 2 </td>
    </tr>
    <tr>
         <td> kill_count == value > pod-list.size() </td>
    </tr> 
    <tr > <td rowspan=3> Powerfulseal lib  </td> 
        <td> kill_count == '' </td>
    </tr>
    <tr> 
         <td> kill_count == 2 , not supported</td>
    </tr>
    <tr>
         <td> kill_count == value > pod-list.size(), , not supported </td>
    </tr> 
         </table>
         
 <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=2>   Container Kill  </th> </tr>
    <tr > <td rowspan=2> target_container  </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> name of container </td>
    </tr>
         </table>
         
   <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=2> Cpu Hog  </th> </tr>
    <tr > <td rowspan=2> auxiliary appinfo </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> provided auxiliary appinfo </td>
    </tr>
         </table>
         
 <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=2> Disk Fill </th> </tr>
    <tr > <td rowspan=2> auxiliary appinfo </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> provided auxiliary appinfo </td>
    </tr>
    
    
  <tr > <td rowspan=2> target container </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> provided container name</td>
    </tr>
         </table>
         
  <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=2> pod network latency </th> </tr>
    <tr > <td rowspan=2> target container </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> value of conatiner </td>
    </tr>
         </table>
         
  <br> <hr> <br>  
  
  <table> 
    <tr> <th colspan=2> pod network loss </th> </tr>
    <tr > <td rowspan=2> target container </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> value of conatiner </td>
    </tr>
         </table>
         
  <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=2> pod network corruption</th> </tr>
    <tr > <td rowspan=2> target container </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> value of conatiner </td>
    </tr>
         </table>
    
    
        
    
    
