<?php
    function printcolored($text,$color="black")
	{
		print("<font color=\"$color\">$text</font");
	}
	printcolored("这是黑颜色的字!");
	print("<br><br>\n");
	printcolored("这是蓝颜色的字!","blue");
	print("<br>\n");
?>
