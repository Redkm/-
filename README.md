能量雨
var id = setInterval(function(){
    press(198,704,7)
    press(358,697,7)
    press(541,718,7)
    press(766,696,7)
    press(945,702,7)
}, 0);

//16秒跳出循环
setTimeout(function(){
    toast('能量雨结束');
    clearInterval(id)
}, 16000);

联通
while(true){
    swipe(487,1565,498,462,50)
    sleep(500)
    click(973,1298)
}
