Örnek Kullanım :


$sms = new SendSMS;
$sms->username = "kullanıcı adınız";
$sms->password = "şifreniz";
$sms->header = "sms başlığınız";
$sms->message = "sms içeriği";
$sms->phone = "gönderilecek telefon numarası";
$sms->send();
