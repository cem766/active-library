active-library
==============

facebook app

<?php

?>
<!DOCTYPE html>
<html lang="en-US">
<head>
<title>WEBBHABER</title>
<meta http-equiv="content-type" content="text/html charset=utf-8"/>
<meta name="content-language" content="tr-TR"/>
<meta name="language" content="Turkish"/>
<meta name="content-type" content="text/html charset=utf-8"/>
<meta name="title" content="webbhaber"/>
<link rel="stylesheet" type="text/css" href="style.css">
<style type="text/css">
body { 
background-color:EEEEEE;
}
a {
text-decoration:none;
color:brown;
}
a:hover{
background-color:gray;
color:black;
type:bold;
}
.baslik {
background-color:red;
color:white;
top:center;
}
.baslik:hover{
background-color:gold;
color:black;
}
</style>
</head>
<body>
<a href="https://plus.google.com/114947500894411409982" rel="publisher"><img src="google/google_small_logo.png" width="51" height="15"></a>
<script>
  window.fbAsyncInit = function() {
    FB.init({
      appId      : '366011160224780',
      xfbml      : true,
      version    : 'v2.2'
    });

    // ADD ADDITIONAL FACEBOOK CODE HERE
  };

  (function(d, s, id){
     var js, fjs = d.getElementsByTagName(s)[0];
     if (d.getElementById(id)) {return;}
     js = d.createElement(s); js.id = id;
     js.src = "//connect.facebook.net/en_US/sdk.js";
     fjs.parentNode.insertBefore(js, fjs);
   }(document, 'script', 'facebook-jssdk'));
</script>




<table width="300px" border="0" align="top">
	  <tr height="50px">
	    <td bgcolor="red" class="baslik">
			<center><font face="arialblack" size="6" align="middle" hspace="2" vspace="2"><strong>YAZARLAR</strong></font></center>
		</td>
      </tr>
 <tr bgcolor="#DDDDDD">
      	<td>
        <br /><br /><br /><br />
			<hr>
        	<a href="activelibrary/index.php" target="_self"><img src="activelibrary/img/logo.png" width="80px" height="50px" align="left" hspace="3" vspace="3" style="text-decoration:none">Facebook Active Library</a>
<br><br>
<fb:like href="<%= @canonical_url %>" send="" layout="button_count"></fb:like> <div id="fb-root">
<div class="ara">
<form action="https://www.facebook.com/groups/tr.developers/search" method="get"> Sözcük <br /><input type="text" value="" maxlength="230" size="36" name="q" /> <input type="submit" value="Ara" /><br /><br />
<p><u>Aramanızı Özelleştirin</u></p>
<p>Facebook'ta arama yapmak istediğiniz sayfa-grup adını seçin</p>
<select>
		<option value="" maxlength="230" size="36"></option>	
		<option>PHP_TR</option>
		<option>meraklı bilişimci</option>
		<option>Yazılımcılar Klubü</option>
		<option>Patlamış Mısır</option>
		<option>e-kitap</option>
		<option>php-tr</option>
		<option>Html-Css</option>
		<option>Webetto</option>
		<option>Etikent Tasarım</option>
		<option>Webbhaber</option>
		<option>International HABER</option>
		<option>Sırdan Düşler</option>
	</select>
<br />

</form>
</div> </div> 
<script> 
// facebook recommend button 
window.fbAsyncInit = function() { 
FB.init({appId: 'myappid', status: true, cookie: true, xfbml: true}); 
};
 (function() { 
// delay to simulate slow loading of Facebook library - remove this 
setTimeout!! var t = setTimeout(function() { 
var e = document.createElement('script'); 
e.async = true; 
e.src = document.location.protocol + '//connect.facebook.net/<%= locale_og_tag %>/all.js';
 document.getElementById('fb-root').appendChild(e);
  }, 0); 
  }()); 
</script> </div>

<br><br><br>
            

</td>
</tr>
</table>
</body>
</html>
