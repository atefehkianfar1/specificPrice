# specificPrice

$price=320548520000;
$priceCount=strlent(320548520000);
$this->holePrice($price,$priceCount);
استفاده از این کد بسیار ساده است. مثلا یک قیمت دارید بصورت 320548520000 و میخواهید بصورت 320 میلیارد و 548 میلیون و 520 هزارتومان نمایش داده شود. برای این کار باید خود قیمت ، تعداد اعداد قیمت  را به متد holePrice پاس بدهید به این صورت : 
$this->holePrice($price , $priceCount)
خروجی دقیقا مقداری است که در بالا ذکر شد 

It's really easy to use. For Example we have a number like 320548520000 and we want to show it like 320 billion and 548 million and 520 thousand Toman (or dollar et...).To using this method you should pass the method 2 parameters : 1.price 2.pric number count , It's simple like this :

$price=320548520000;
$priceCount=strlent(320548520000);
echo ($this->holePrice($price,$priceCount));

