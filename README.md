# Adres
#include &lt;StringConstants.au3> Local $sMail  =    "Adres: Statenkanaal 11 1234KD Maastricht"  &amp; @CRLF &amp; _                         "Telefoon: 004999999966673"  &amp; @CRLF &amp; _                         "Geboortedatum: 21-7-2001"  &amp; @CRLF &amp; _                         " OrderID: 5102"  &amp; @CRLF &amp; _                         ""  &amp; @CRLF &amp; _                         "Datum: 20-2-2022 14:56:39"  $sMailAddress = StringRegExp($sMail, "(?i)Adres:(.*?)\n", $STR_REGEXPARRAYMATCH , 1) MsgBox($MB_SYSTEMMODAL, "", $sMailAddress[0]) 
