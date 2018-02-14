# php-xml2srt

## INTRODUCTION

XML2SRT is a PHP Script which converts subtitle caption files in XML format into 
SRT format.

## DOCUMENTATION
Change in the file **xml2srt.php**: `myxmlfiletoSRT.xml` by the location of the XML, and `theSRTnamefileiwant.srt` by the name of the .srt you want:
```
$xmlFile = file_get_contents('myxmlfiletoSRT.xml');
$myFile = "theSRTnamefileiwant.srt";
```
