<?php
    function makeBold($inputText)       
    {
        $boldedText = "<B>";
        $boldedText .= $inputText;
        $boldedText .= "</B>";
        return($boldedText);        
    }
    print("这行没有加重！！！<BR>\n"); 
    print(makeBold("这行被加重了！！！") . "<BR>\n");
    print("这行没有加重！！！<BR>\n");  
?>
