# supertidy
PHP Super Tidy

Please feel free to modify this as you wish.

Just include supertidy.php and implement as follows:

$html = "<YOUR HTML>";

$Tidy = new SuperTidy($html);
$Tidy->SetIndentSize(4);
$Tidy->SetOffset(0);
echo $Tidy->BeautifiedHTML();
