# supertidy
PHP Super Tidy
Just include supertidy.php and implement as follows

$html = "<YOUR HTML>";

$Tidy = new SuperTidy($html);
$Tidy->SetIndentSize(4);
$Tidy->SetOffset(0);
echo $Tidy->BeautifiedHTML();
