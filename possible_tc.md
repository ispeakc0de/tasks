### Generic Experiements



<table> 
    <tr> <th colspan=4>   Pod Delete  </th> </tr>
    <tr > <td> Litmus Lib  </td> 
        <td> kill_count == '' </td> 
         <td> kill_count == 2 </td>
         <td> kill_count == value > pod-list.size() </td>
    </tr> 
    <tr > <td> Powerfulseal Lib  </td> 
        <td> kill_count == '' </td> 
         <td> kill_count == 2 </td>
         <td> kill_count == value > pod-list.size() </td>
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
         <td> value of container </td>
    </tr>
         </table>
         
  <br> <hr> <br>  
  
  <table> 
    <tr> <th colspan=2> pod network loss </th> </tr>
    <tr > <td rowspan=2> target container </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> value of container </td>
    </tr>
         </table>
         
  <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=2> pod network corruption</th> </tr>
    <tr > <td rowspan=2> target container </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> value of container </td>
    </tr>
         </table>
         
   <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=2> Drain Node  </th> </tr>
    <tr > <td rowspan=2> auxiliary appinfo </td> 
        <td> null string </td>
    </tr>
    <tr> 
         <td> provided auxiliary appinfo </td>
    </tr>
         </table>
         
   <br> <hr> <br>  
 
  <table> 
    <tr> <th colspan=4> Diss Loss  </th> </tr>
    <tr > <td rowspan=4> platform </td> 
        <td rowspan=2> GKE </td>
        <td rowspan=2> Auxiliary appinfo </td>
         <td >  null string </td>
    </tr>
    <tr>
         <td > some value </td>
    </tr>
    <tr> 
         <td rowspan=2> AWS </td>
        <td rowspan=2> Auxiliary appinfo </td>
        <td > null string</td>
    </tr>
         <tr>
         <td > some value </td>
    </tr>
    
   </table>
         
    
    
        
    
    
