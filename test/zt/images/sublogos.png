<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <meta http-equiv="refresh" content="8;url=http://wh.gz360.com">
    <link href="../Style/all.css" rel="stylesheet" type="text/css" />
    <link href="../Style/user.css" rel="stylesheet" type="text/css" />
    <script src="../Js/jquery.min.1.8.js"></script>
    <title>404_工长360_武汉装修网_装修省钱没烦恼!</title>    
</head>


<body>
    <!--主导航-->
    <div class="upper">
    <div class="upper-a">
		<div style="float:left;"><i class="city-i"> </i><div class="slogan-s-a nav-list" style="float:left"><div class="city">
                武汉<a style="color: #00ac26;" title="切换其它城市">[切换]</a>&nbsp;&nbsp;
            </div>
            <div class="select-city" id="downmenu">
                <a href="http://wh.gz360.com?city=wh" title="武汉">武汉</a> <a href="http://yt.gz360.com?city=yt" title="烟台">烟台</a>
            </div></div>
				</div>
        <div class="upper-b" id="upper-b">
            </div>
        <div class="upper-c">
            <ul><li>
                    <div class="upper-c4">
                        咨询：17092611888</div>
                </li>
                <li>
                    <div class="upper-c5">
                        <a onClick="AddFavorite(location.href,document.title)" style="cursor:pointer;">加入收藏</a></div>
                </li>
                <li class="nav-list">
                    <div class="upper-c6">
                        <a title="网站导航">网站导航</a></div>
                    <div class="navigation" id="downmenu1">
                        <ul>
                            <li>
                                <a target="_blank" href="http://www.gz360.com/ask/" title="问答中心" class="downmenu-bj">问答中心</a>
                                <a target="_blank" href="http://www.gz360.com/ask/list1-1-0-0.html	" title="家装设计" class="downmenu-no">家装设计</a>
                                <a target="_blank" href="http://www.gz360.com/ask/list1-2-0-0.html" title="装修流程" class="downmenu-no">装修流程</a>
                                <a target="_blank" href="http://www.gz360.com/ask/list1-3-0-0.html" title="家居产品" class="downmenu-no">家居产品</a>
                                <a target="_blank" href="http://www.gz360.com/ask/list1-4-0-0.html" title="装饰材料" class="downmenu-no"> 装饰材料</a>
                                <a target="_blank" href="http://www.gz360.com/ask/list1-5-0-0.html" title="工装设计" class="downmenu-no">工装设计</a>
                                <a target="_blank" href="http://www.gz360.com/ask/list1-6-0-0.html" title="房产知识" class="downmenu-no">房产知识</a>
                            </li>
                            <li>
                                <a target="_blank" href="http://www.gz360.com/news/" title="新闻中心" class="downmenu-bj">新闻中心</a>
                                <a target="_blank" href="http://www.gz360.com/news/list1-1.html" title="行业报道" class="downmenu-no">行业报道</a>
                                <a target="_blank" href="http://www.gz360.com/news/list1-3.html" title="家装攻略" class="downmenu-no">家装攻略</a>
                                <a target="_blank" href="http://www.gz360.com/news/list1-5.html" title="最新签约" class="downmenu-no">最新签约</a>
                                <a target="_blank" href="http://www.gz360.com/news/list1-6.html" title="装修知识" class="downmenu-no">装修知识</a>
                                <a target="_blank" href="http://www.gz360.com/news/list1-7.html" title="最新签约" class="downmenu-no">装修风水</a>
                                <a target="_blank" href="http://www.gz360.com/news/list1-8.html" title="装修建材" class="downmenu-no">装修建材</a>
                            </li>                        
                        </ul>
                    </div>
                </li>
            </ul>
        </div>
    </div>
</div>
<script src="/Js/jquery.cookie.js" type="text/javascript"></script>
<script type="text/javascript">
    var SetHtml = function (name, id, username, usertype) {
        
        if (id == '') {
            $("#upper-b").html("<div style=\"float:left;\">欢迎您访问工长360！</div><div style=\"float:right;\"><a href=\"/Member/login.aspx\" title=\"请登录\">请登录</a><a style=\"color:#999; font-weight:normal;\">|</a><a href=\"/Member/join.aspx\" title=\"免费注册\">免费注册</a></div>");
            //$("#exit").hide();
        } else {

            var typestr = "亲爱的 <span style=\"color: #00a567;\">" + (name.length > 0 ? name : username) + "</span> 欢迎您访问工长360！<a style=\"color: #00a567;\" href=\"/member/\">进入中心</a><a  style=\"cursor:pointer;color: #00a567;\" onclick=\"$.cookie('user', null, { path: '/' });SetHtml('', '', '', '');\">退出登陆</a>"; 
            $("#upper-b").html(typestr);
            //$("#downmenu").append("<a id=\"exit\" style=\"cursor:pointer\" onclick=\"$.cookie('user', null, { path: '/' });SetHtml('', '', '', '');\" title=\"退出登录\" class=\"downmenu-no\">退出登录</a>");


        }
    };
    $("#upper-b").ready(function () {
        var s = $.cookie("user");
        var qdnum = getCookie(decodeURIComponent(s), "name");
        if (qdnum.length > 0) {
            $("#qdnum").html(getCookie(decodeURIComponent(s), "qdnum"));
        }
        
        if (s != null) SetHtml(getCookie(decodeURIComponent(s), "name"), getCookie(decodeURIComponent(s), "id"), getCookie(decodeURIComponent(s), "username"), getCookie(decodeURIComponent(s), "usertype"));
        else SetHtml('', '', '', '');

    });
    function getCookie(cookstr, name) {//获取指定名称的cookie的值
        var str = "";
        var arrStr = cookstr.split("&");
        for (var i = 0; i < arrStr.length; i++) {
            var start = arrStr[i].indexOf("=") + 1;
            var end = arrStr[i].length;
            if (arrStr[i].indexOf(name) > -1) {
                if (arrStr[i].indexOf("=") > -1) {
                    str = arrStr[i].substr(start, end);
                }
            }
        }
        return str;
    }
function AddFavorite(sURL, sTitle) {
                              try { //IE
                                  window.external.addFavorite(sURL, sTitle);
                              } catch (e) {
                                  try { //Firefox
								  obj.setAttribute("rel", "sidebar"), obj.title = title, obj.href = url;
                                      //window.sidebar.addPanel(sTitle, sURL, "");
                                  } catch (e) {
                                      try {//Chrome无法自动收藏，用创建快应用程序的捷方式来替代。
                                          createShortcut();
                                      } catch (e) {
                                          alert("收藏失败！请使用Ctrl+D进行添加。");
                                      }
                                  }
                              }
                          }
	</script>


    <!--404-->
    <style type="text/css">
        /*404表样式*/
        .a1-404 {
            background: #f4f3ef;
            text-align: center;
        }

        .a2-404 img {
            background: #f4f2ef;
            text-align: center;
            margin-top: 40px;
        }

        .a3-404 {
            height: 130px;
        }

            .a3-404 a {
                color: #01a569;
            }

                .a3-404 a:hover {
                    color: #01a569;
                    text-decoration: underline;
                }
    </style>
    <div class="a1-404">
        <ul>
            <li class="a2-404">
                <img src="../Images/404.jpg" />
            </li>
            <li class="a3-404">
                <a href="http://wh.gz360.com" title="返回【工长360】首页">返回首页&gt;&gt;</a>
            </li>
        </ul>
    </div>


   <!--尾部-->
    <div class="bottom-nav mt30">
    <a target="_blank" href="/about/connect.html" rel="nofollow" >联系我们</a>| <a title="关于我们"
        href="/about/about.html" rel="nofollow">关于我们</a>| <a target="_blank" href="/about/link.html" rel="nofollow">
            友情链接</a>| <a target="_blank" href="/about/help.html" rel="nofollow">帮助中心</a>|
    <a target="_blank" href="/about/jobs.html" rel="nofollow">高薪诚聘</a>| <a target="_blank"
        href="/about/falv.html" rel="nofollow">法律申明</a>| <a target="_blank" href="/about/sitemap.html"
            rel="nofollow">网站地图</a>| <a target="_blank" href="http://m.gz360.com/wh"
            rel="nofollow">手机版</a>
</div>
<div class="copyright">
    © 2017 gz360.com 版权：武汉工长三六零电子商务有限公司<br /> 工长360 汉阳国博店:汉阳区四新南路文举路国博新城一期a区2楼211门店
    备案号：鄂ICP备17019434号-1
    <script type="text/javascript">        var cnzz_protocol = (("https:" == document.location.protocol) ? " https://" : " http://"); document.write(unescape("%3Cspan id='cnzz_stat_icon_1253376399'%3E%3C/span%3E%3Cscript src='" + cnzz_protocol + "w.cnzz.com/q_stat.php%3Fid%3D1253376399%26l%3D2' type='text/javascript'%3E%3C/script%3E"));</script>
			 	<a target="_blank" href="http://www.beian.gov.cn/portal/registerSystemInfo?recordcode=42011102000329" style="display:inline-block;text-decoration:none;height:20px;line-height:20px;"><img src="/beian.png" style="float:left;"/></a>
		 
    <script>
        var _hmt = _hmt || [];
        (function () {
            var hm = document.createElement("script");
            hm.src = "//hm.baidu.com/hm.js?1a49dfe219178bbc406d995aa7b09728";
            var s = document.getElementsByTagName("script")[0];
            s.parentNode.insertBefore(hm, s);
        })();
    </script>
    <br />
    <!--<a  key ="54c89b2ec274e71c5265cc12"  logo_size="83x30"  logo_type="realname"  href="http://www.anquan.org" ><script src="http://static.anquan.org/static/outer/js/aq_auth.js"></script></a>-->
</div>
<div style="right: 106px;" class="scroll">
    <a onclick="window.open('http://p.qiao.baidu.com/cps/chatIndex?reqParam=%7B%22from%22%3A0%2C%22sid%22%3A%22-100%22%2C%22tid%22%3A%22-1%22%2C%22ttype%22%3A1%2C%22siteId%22%3A%225902476%22%2C%22userId%22%3A%228017321%22%7D','_blank','width=800,height=500,left=250, top=100,toolbar=no, status=no, menubar=no, resizable=yes, scrollbars=no');return false">
        <div class="ts">
        </div>
    </a><a onclick="window.open('http://p.qiao.baidu.com/cps/chatIndex?reqParam=%7B%22from%22%3A0%2C%22sid%22%3A%22-100%22%2C%22tid%22%3A%22-1%22%2C%22ttype%22%3A1%2C%22siteId%22%3A%225902476%22%2C%22userId%22%3A%228017321%22%7D','_blank','width=800,height=500,left=250, top=100,toolbar=no, status=no, menubar=no, resizable=yes, scrollbars=no');return false">
        <div class="ts-1">
            汉口咨询</div>
    </a><a onclick="window.open('http://p.qiao.baidu.com/cps/chatIndex?reqParam=%7B%22from%22%3A0%2C%22sid%22%3A%22-100%22%2C%22tid%22%3A%22-1%22%2C%22ttype%22%3A1%2C%22siteId%22%3A%225902476%22%2C%22userId%22%3A%228017321%22%7D','_blank','width=800,height=500,left=250, top=100,toolbar=no, status=no, menubar=no, resizable=yes, scrollbars=no');return false">
        <div class="gzjm">
            武昌咨询</div>
    </a><a onclick="window.open('http://p.qiao.baidu.com/cps/chatIndex?reqParam=%7B%22from%22%3A0%2C%22sid%22%3A%22-100%22%2C%22tid%22%3A%22-1%22%2C%22ttype%22%3A1%2C%22siteId%22%3A%225902476%22%2C%22userId%22%3A%228017321%22%7D','_blank','width=800,height=500,left=250, top=100,toolbar=no, status=no, menubar=no, resizable=yes, scrollbars=no');return false">
        <div class="sjsjm">
            汉阳咨询</div>
    </a><a target="_blank" rel="nofollow" href="http://wh.gz360.com/Member/msglogin.aspx">
        <div class="fzjm">
            查看报价</div>
        </a><a target="_blank" rel="nofollow" href="http://wh.gz360.com/Member/msgloginforcom.aspx">
        <div class="qzzp">
            评价工长</div>
    </a>
    <div class="gt">
    </div>
</div>
<!--导航-->
<style>
    .scroll
    {
        top: 217px;
        cursor: pointer;
        height: 150px;
        width: 106px;
        color: #333333;
        position: fixed;
        _position: absolute; /*兼容IE6*/
        _top: expression(eval(document.documentElement.scrollTop)+500); /*700为图片距离顶部的设定距离，可以修改。不加700则图片紧贴在顶部滚动*/
    }
    .scroll a
    {
        text-decoration: none;
    }
    .ts
    {
        background: url(/images/topss.png) no-repeat 0 0 transparent;
        height: 111px;
    }
    .ts-1
    {
        background: url(/images/topss.png) no-repeat 0 -111px transparent;
        height: 43px;
        line-height: 48px;
        padding-left: 30px;
        font-size: 14px;
        color: #109566;
    }
    .ts-1:hover
    {
        background: url(/images/topss.png) no-repeat -106px -111px transparent;
        color: #fff;
    }
    .gzjm
    {
        background: url(/images/topss.png) no-repeat 0 -154px transparent;
        height: 43px;
        line-height: 43px;
        color: #109566;
        padding-left: 30px;
        font-size: 14px;
    }
    .gzjm:hover
    {
        background: url(/images/topss.png) no-repeat -106px -154px transparent;
        color: #fff;
    }
    .sjsjm
    {
        background: url(/images/topss.png) no-repeat 0 -197px transparent;
        height: 43px;
        line-height: 43px;
        padding-left: 30px;
        font-size: 14px;
        color: #109566;
    }
    .sjsjm:hover
    {
        background: url(/images/topss.png) no-repeat -106px -197px transparent;
        color: #fff;
    }
    .fzjm
    {
        background: url(/images/topss.png) no-repeat 0 -240px transparent;
        height: 43px;
        line-height: 43px;
        padding-left: 30px;
        font-size: 14px;
        color: #109566;
    }
    .fzjm:hover
    {
        background: url(/images/topss.png) no-repeat -106px -240px transparent;
        color: #fff;
    }
    .qzzp
    {
        background: url(/images/topss.png) no-repeat -106px -283px transparent;
        height: 43px;
        line-height: 43px;
        padding-left: 30px;
        font-size: 14px;
        color: #fff;
    }
    .qzzp:hover
    {
        background: url(/images/topss.png) no-repeat -106px -283px transparent;
        color: #fff;
    }
    
    html
    {
        _text-overflow: ellipsis;
    }
    html
    {
        _text-overflow: ellipsis;
    }
    /*解决IE6下图片抖动*/
</style>
<script type="text/javascript">    $(document).ready(function () {
        
        var isMobile = {
            Android: function () {
                return navigator.userAgent.match(/Android/i) ? true : false;
            },
            BlackBerry: function () {
                return navigator.userAgent.match(/BlackBerry/i) ? true : false;
            },
            iOS: function () {
                return navigator.userAgent.match(/iPhone|iPad|iPod/i) ? true : false;
            },
            Windows: function () {
                return navigator.userAgent.match(/IEMobile/i) ? true : false;
            },
            any: function () {
                return (isMobile.Android() || isMobile.BlackBerry() || isMobile.iOS() || isMobile.Windows());
            }
        };
        var swidth = 110;
        var fhtml = "<a href=\"http://webim.qiao.baidu.com//im/index?ucid=8017321&siteid=6916457&bid=e112e33c639e77466e327d19\"><div class=\"ts\"></div></a><a href=\"http://webim.qiao.baidu.com//im/index?ucid=8017321&siteid=6916457&bid=e112e33c639e77466e327d19\"><div class=\"ts-1\">汉口咨询</div></a><a href=\"http://webim.qiao.baidu.com//im/index?ucid=8017321&siteid=6916457&bid=e112e33c639e77466e327d19\"><div class=\"gzjm\">武昌咨询</div></a><a href=\"http://webim.qiao.baidu.com//im/index?ucid=8017321&siteid=6916457&bid=e112e33c639e77466e327d19\"><div class=\"sjsjm\">汉阳咨询</div></a><a target=\"_blank\" rel=\"nofollow\" href=\"http://wh.gz360.com/Member/msglogin.aspx\"><div class=\"fzjm\">查看报价</div></a><a target=\"_blank\" rel=\"nofollow\" href=\"http://wh.gz360.com/Member/msgloginforcom.aspx\"><div class=\"qzzp\">评价工长</div></a><div class=\"gt\"></div>";
        if (isMobile.any()) {
            $(".scroll").attr("style", "right:0px");
            swidth = 0;
            $(".scroll").html(fhtml);
        }
        var show_delay;
        var scroll_left = parseInt((document.body.offsetWidth - 1000) / 2) - swidth; //960为页面宽度
        $(".gt").click(function () {
            $("html,body").animate({ scrollTop: 0 }, 200);
            //document.documentElement.scrollTop = 0;
            //document.body.scrollTop = 0;
        });
        $(window).resize(function () {
            scroll_left = parseInt((document.body.offsetWidth - 1000) / 2) - swidth;
            $(".scroll").css("right", scroll_left);
        });
        reshow(scroll_left, show_delay);
    });
    function reshow(marign_l, show_d) {
        $(".scroll").css("right", marign_l);
        if ((document.documentElement.scrollTop + document.body.scrollTop) != 0) {
            //$(".scroll").css("display", "block");
        }
        else {
            //$(".scroll").css("display", "none");
        }
        //if (show_d) window.clearTimeout(show_d);
        //show_d = setTimeout("reshow()", 500);
    }

    $(document).ready(function () {
        
    }); 
    </script>
	<script>
(function(){
    var bp = document.createElement('script');
    bp.src = '//push.zhanzhang.baidu.com/push.js';
    var s = document.getElementsByTagName("script")[0];
    s.parentNode.insertBefore(bp, s);
})();
</script>

</body>
</html>
