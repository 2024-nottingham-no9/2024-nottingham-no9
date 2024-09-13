<table width="98%">
    <tr> 
      <td colspan="3" ><img src="image/whbf_logo.jpg" width="180" height="70" ><a href="JavaScript:window.open('<? echo $row_Recordset2['map']?>')" ><img src="image/map_bw.jpg" width="57" height="57"></a></td>
    </tr>
  <tr>
      <td height="29" colspan="2" ><div align="center"><img src="image/jetso101.jpg" id="image" alt="Moving Image"></div>	  </td>
  </tr>
  <? if  ($c_rules1 <> ""){ ?>
   <tr>
      <td height="29" colspan="2"  size="3">*<? echo $c_rules1 ?></td>
   </tr>　 
   <? }?>
   <? if  ($c_rules2 <> ""){ ?>
   <tr>
      <td height="29" colspan="2"  size="3">*<? echo $c_rules2 ?></td>
   </tr>　 
   <? }?>
   <? if  ($c_rules3 <> ""){ ?>
   <tr>
      <td height="29" colspan="2"  size="3">*<? echo $c_rules3 ?></td>
   </tr>　 
   <? }?>   
   <? if  ($c_rules4 <> ""){ ?>
   <tr>
      <td height="29" colspan="2"  size="3">*<? echo $c_rules4 ?></td>
   </tr>　 
   <? }?>   
    <tr> 
      <td height="29" colspan="2"  size="3">
	 <? echo $c_terms ?></td>
    </tr>
 
  <? if  ($e_rules1 <> ""){ ?>
   <tr>
      <td height="29" colspan="2" size="3">*<? echo $e_rules1 ?></td>
   </tr>　 
   <? }?>
   <? if  ($e_rules2 <> ""){ ?>
   <tr>
      <td height="29" colspan="2" size="3">*<? echo $e_rules2 ?></td>
   </tr>　 
   <? }?>
   <? if  ($e_rules3 <> ""){ ?>
   <tr>
      <td height="29" colspan="2"  size="3">*<? echo $e_rules3 ?></td>
   </tr>　 
   <? }?>   
   <? if  ($e_rules4 <> ""){ ?>
   <tr>
      <td height="29" colspan="2"  size="3">*<? echo $e_rules4 ?></td>
   </tr>　 
   <? }?>   
    <tr> 
      <td height="29" colspan="2" size="3">
	 *<? echo $e_terms ?></td>
    </tr>
    <tr> 
      <td height="29" colspan="2" size="3">&nbsp;</td>
    </tr>
   <tr> 
      <td rowspan="2"><img src="image/weblogo<? echo $customer_code ?>.png" width="94" height="64"></td>
      <td><span class="style6"> <? echo $company_address ?> </span></td>
   </tr>
   <tr>
     <td><span class="style6"><? echo $company_tel ?></span></td>
   </tr>
</table>
