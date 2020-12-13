# nodejscreateCipherToPhp
php对应解密nodejs加密方法createCipher
example

$plain_text = '这是一个秘密,需要加密';
$password   = "123456";
$enc_text = (new Crypto())->encrypt($plain_text,$password,'',true);

$pla_text = (new Crypto())->decrypt($enc_text,$password,'',true);
