# bcfs

基于区块链的学习认证平台.
@charset "utf-8";
/* CSS Document */
header{
	height:330px;
	background: url no-repeat;
	text-align:center;
	width:990px;
}
.header{
    height: 120px;
    width: 990px;
    margin: 0 auto;
}
.header_left{
    float: left;
    line-height: 120px;

}
.header_left img{
    width: 500px;
    height: 100px;
}
.header_right{
    float: right;
    height: 120px;
    position: relative;
}
.header_right>div{
    position: absolute;
    top: 0;
    right: 0;

}
.header_right ul{
    margin-top: 88px;

}
.header_right ul a li{
    border-right: 1px solid #000000;
    height: 13px;
    font-size: 15px;
    padding: 0 25px;
    font-weight: bold;
    color: #666;

}
.header_right ul a{
    float: left;
    line-height: 13px;

}
.header_right ul a li:hover{
    color: #000000;
}
.header_right ul a:last-child li{/*去掉最后的边框*/
    border: none;
}
.show_list{
    position: relative;
}
.show_list .move_list{
    display: none;
    z-index: 103;
    position: absolute;
    top: -56px;
    left: 0;
    width: 100%;
    background: #333;
    text-align: center;
}
.show_list .move_list li{
    padding: 10px 0;
    width: 114px;
    color: #fff;
}
.header_right ul a .show_list{
    padding-bottom: 20px;
    border-right: none;
}
.show_list:hover .move_list{
    display: block;
}
.header_right ul a:nth-child(3){
    border-left: 1px solid #000;
}
.show_list .move_list li:hover{
    color: white;
    background: orange;
}
*{
    margin: 0;
    padding: 0
}
em,i {
    font-style: normal
}
li {
    list-style: none
}
a{
    font: 14px/24px Microsoft YaHei,Arial,\\5B8B\4F53,Arial Narrow;
    letter-spacing: 1.2px;
    color: #666;
    text-decoration: none
}
a:hover {
    color: #c81623 ;
}

img {
    border: 0;
    vertical-align: middle
}
input{
    outline: none;
}
button {
    cursor: pointer;
    border:none;
    outline: none;
}
footer{
	text-align:center;
	vertical-align:middle;
	width:1400px;
	height:70px;
	padding:7px 0;
	float:left;
	background-color:#E1E0DB;
}
body{
	background:#B1AAAA
}
