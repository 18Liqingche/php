<?php
  print("<b>距离星期一还有几天？</b>\n");
  print("<ol>\n");
  for($currentdate=date("u");       
  date("1",$currentdate)!="monday";
  $currrentdate+=(60*60*24))
  {
  print("<li>".date("1",$currentdate)."\n");
  }
  print("</ol>\n");
?>

<?php
function printbold($inputtext)
{
 print("<B>" . $inputText . "</B>");

}
  print("这行没有加重！<br>\n");
  printbold("这行加重了!!!");
  print("<br>\n");
  print("这行没有加重!<br>\n");
?>
