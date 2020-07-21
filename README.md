<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
		<!--<link rel="stylesheet" href="css/swiper.css"/>-->
		<style type="text/css">
			*{
				margin: 0px;
				padding: 0px;
			}
			body{
				width: 100%;
				height: 100%;
				min-width: 400px;
				background-image: url(img/24_lbp_lf.jpg);
				background-size: 100%;
			}
			.tou{
				width: 100%;
				height: 100px;
				background: red;
				position: fixed;
				top: 0px;
				left: 0px;
				z-index: 10;
				min-width: 2000px;
			}
			.bg_top_lf{
				width: 100%;
				height: 440px;
				margin-top: 100px;
				background-image: url(img/25_lbp_lf.jpg);
				background-repeat: no-repeat;
			}
			/*轮播图盒子背景*/
			.lb_bg_lf{
				width: 100%;
				height: 580px;
				min-width: 2000px;
				/*min-height: 2000px;*/
				/*overflow: hidden;*/
				position: relative;
				background:white;
			}
			/*轮播图头上的字体*/
			.lb_bg_lf>p{
				font-size: 30px;
				/*display: inline-block;*/
				/*line-height: 120px;*/
				padding: 60px 0px 30px 0px;
				box-sizing: border-box;
				text-align: center;
				/*background: red;*/
			}
			/*轮播图*/
			.lb_bg_lf>.Rotation-chart_lf{
				width: 1070px;
				height: 288px;
				overflow: hidden;
				position: relative;
				background: white;
				margin: 35px auto;
				box-shadow: 0px 0px 23px 0px gray;
			}
			.lb_bg_lf>.Rotation-chart_lf>ul{
				width: 6420px;
				height: 288px;
				list-style: none;
				/*overflow: hidden;*/
				position: relative;
			}
			/*轮播图所有li*/
			.lb_bg_lf>.Rotation-chart_lf>ul>li{
				width: 1070px;
				height: 288px;
				float: left;
				background: white;
				/*border: 1px solid #000;*/
			}
			/*轮播图li*/
			.lb_bg_lf>.Rotation-chart_lf>ul>li>.img_left_lf{
				float: left;
				width: 480px;
				height: 288px;
			}
			.lb_bg_lf>.Rotation-chart_lf>ul>li>.img_right_lf{
				float: right;
				width: 516px;
				height: 35px;
				margin-top: 17px;
				margin-right: 31px;
				/*background: red;*/
			}
			.lb_bg_lf>.Rotation-chart_lf>ul>li>.img_right2_lf{
				float: right;
				width: 516px;
				height: 71px;
				padding: 24px 0px 29px 0px;
				box-sizing: border-box;
				margin-right: 31px;
				/*background: bisque;*/
			}
			.lb_bg_lf>.Rotation-chart_lf>ul>li>.img_right3_lf{
				float: right;
				width: 516px;
				height: 80px;
				/*background: goldenrod;*/
				margin-right: 31px;
				margin-bottom: 20px;
			}
			.lb_bg_lf>.Rotation-chart_lf>ul>li>.img_right4_lf{
				float: right;
				width: 516px;
				height: 20px;
				/*background: aquamarine;*/
				margin-right: 31px;
			}
			.lb_bg_lf>.Rotation-chart_lf>ul>li>.img_right4_lf>p>img{
				margin-left: 30px;
				margin-right: 15px;
			}
			.lb_bg_lf>.button_left_lf{
				width: 25px;
				height: 45px;
				display: inline-block;
				font-size: 40px;
				/*background: red;*/
				font-family: Simsun;
				color: #398AEF;
				position: absolute;
				top: 300px;
				left: 370px;
			}
			.lb_bg_lf>.button_right_lf{
				width: 25px;
				height: 45px;
				display: inline-block;
				font-size: 40px;
				/*background: red;*/
				font-family: Simsun;
				color: #398AEF;
				position: absolute;
				top: 300px;
				right: 370px;
			}
/*商品布局__________________________________________________________*/
			/*上部文字*/
			section{
				width: 60%;
				height: 100%px;
				/*background: lightblue;*/
				margin: 0px auto;
			}
			section>.section_typeface_lf{
				width: 800px;
				height: 175px;
				/*border: 1px solid #000;*/
				margin: 0px auto;
				padding-top: 40px;
				box-sizing: border-box;
			}
			section>.section_typeface_lf>h1{
				font-size: 27px;
				font-weight: 500;
				text-align: center;
			}
			section>.section_typeface_lf>p{
				font-size: 13px;
				line-height: 45px;
				/*border: 1px solid #000;*/
				text-align: center;
			}
			/*布局内容*/
			section>.lf_centent>ul{
				list-style: none;
			}
			
			section>.lf_centent>ul>.lf_centent_li{
				width: 540px;
				height: 450px;
				margin-right: 30px;
				margin-bottom: 30px;
				padding: 0px;
				background: white;
				box-shadow: 0px 0px 13px 0px;
				position: relative;
				top: 0px;
				left: 0px;
				overflow: hidden;
				/*border: 1px solid #000;*/
			}
			section>.lf_centent>ul>.lf_centent_li>.content_lf_li_div{
				width: 260px;
				height: 30px;
				font-size: 28px;
				margin:30px 0px 20px 20px
				/*background: hotpink;*/
			}
			section>.lf_centent>ul>.lf_centent_li>.content_lf_li_div2>img{
				margin-left: 20px;
				margin-right: 10px;
			}
			section>.lf_centent>ul>.lf_centent_li>.content_lf_li_div2{
				width: 500px;
				height: 30px;
				font-size: 13px;
				margin-left: 20px;
				margin-bottom: 20px;
				/*background: antiquewhite;*/
			}
			section>.lf_centent>ul>.lf_centent_li>.content_lf_li_div3{
				width: 540px;
				height: 178px;
				padding: 40px 20px 50px 20px;
				box-sizing: border-box;
				background: #096FFF;
				position: absolute;
				bottom: -179px;
				left: 0px;
				color: white;
				transition: all 0.5s;
				/*overflow: hidden;*/
			}
			section>.lf_centent>ul>.lf_centent_li:hover>.content_lf_li_div3{
				bottom: 0px;
			}
			section>.lf_bottom_2{
				/*width: 300px;*/
				position: relative;
				height: 200px;
				/*background: red;*/
			}
			section>.lf_bottom_2>.lf_bottom_2_1{
				width: 230px;
				height: 50px;
				background: #FFC231;
				line-height: 50px;
				color: white;
				position: absolute;
				top: 32%;
				left: 28%;
				text-align: center;
				cursor: pointer;
				border-radius: 30px;
			}
			section>.lf_bottom_2>.lf_bottom_2_2{
				width: 230px;
				height: 50px;
				background: #3091FF;
				line-height: 50px;
				color: white;
				position: absolute;
				top: 32%;
				left: 52%;
				text-align: center;
				cursor: pointer;
				border-radius: 30px;
			}
/*底部__________________________________________________*/
			.ending_top_lf{
				width: 100%;
				height: 210px;
				background: lightpink;
				/*border: 1px solid rgba(0,0,0,0);*/
				position: relative;
				background-image: url(img/37_lbp_lf.png);
				background-repeat: no-repeat;
				background-size: 100% 101%;
			}
			.ending_top_lf>.ending_top_lf_1{
				width: 100%;
				height: 70px;
				position: absolute;
				top: 29px;
				left: 0px;
			}
			.ending_top_lf>.ending_top_lf_1>p{
				font-size: 32px;
				color: white;
				text-align: center;
				line-height: 70px;
			}
			.ending_top_lf>.ending_bottom_lf_2{
				width: 216px;
				height: 50px;
				border: 1px solid white;
				border-radius: 10px;
				color: white;
				font-size: 24px;
				text-align: center;
				line-height: 45px;
				cursor: pointer;
				position: absolute;
				top: 120px;
				left: 44%;
			}
			.ending_bottom_lf{
				width: 100%;
				height: 360px;
				background: black;
				
			}
		</style>
	</head>
	<body>
		<div class="tou"></div>
		<div class="bg_top_lf"></div>
		<div class="lb_bg_lf">
			<p>部分典型案例</p>
			<h5 style="text-align: center;">10年行业沉淀、30000多家高端客户见证，商联达为您提供最优质的产品和高质量的服务</h5>
			<div class="Rotation-chart_lf">
				<ul>
					<li>
						<div class="img_left_lf"><img src="img/1_lbp_lf.jpg"/></div>
						<div class="img_right_lf"><img src="img/30_lbp_lf.jpg" alt="" style="width: 85px; height: 35px; margin-right: 20px;"/><b style="color: gray;">君乐宝</b></div>
						<div class="img_right2_lf"><b style="color: gray; font-size: 13px;">乳制品行业龙头企业</b></div>
						<div class="img_right3_lf"><p style="color: gray; font-size: 12px;">客户介绍：君乐宝乳业集团成立于1995年，是农业产业化国家重点龙头企业、国家高新技术企业、国家乳品研发技术分中心，公司现有员工10000余人，在河北、河南、江苏、吉林等地建有16个生产工厂，9个现代化大型牧场。业务范围包括婴幼儿奶粉、低温酸奶、常温液态奶、牧业等四大板块，经过多轮筛选最终选用商联达为其搭建官方商城平台。</p></div>
						<div class="img_right4_lf"><p style="color: gray; font-size: 12px;">电商模式：<img src="img/32_lbp_lf.png" alt="" />pc端<img src="img/35_lbp_lf.png" alt="" />Wap端<img src="img/36_lbp_lf.png" alt="" />微信端<img src="img/23_lbp_lf.png" alt="" />APP端</p></div>
					</li>
					<li>
						<div class="img_left_lf"><img src="img/18_lbp_lf.jpg"/></div>
						<div class="img_right_lf"><img src="img/27_lbp_lf.jpg" alt="" style="width: 85px; height: 35px; margin-right: 20px;"/><b style="color: gray;">斐讯</b></div>
						<div class="img_right2_lf"><b style="color: gray; font-size: 13px;">电子信息100强公司</b></div>
						<div class="img_right3_lf"><p style="color: gray; font-size: 12px;">客户介绍：斐讯数据通信技术有限公司成立于2009年，其全球双总部位于中国上海和成都，在美国和德国设有区域总部，核心产品是K系列路由器+智能健康系列科技产品+家庭健康系列+区块链应用产品等科技产品。商联达为其搭建推啥0元购全返商城平台。</p></div>
						<div class="img_right4_lf"><p style="color: gray; font-size: 12px;">电商模式：<img src="img/32_lbp_lf.png" alt="" />pc端<img src="img/35_lbp_lf.png" alt="" />Wap端<img src="img/36_lbp_lf.png" alt="" />微信端<img src="img/23_lbp_lf.png" alt="" />APP端</p></div>
					</li>
					<li>
						<div class="img_left_lf"><img src="img/19_lbp_lf.jpg"/></div>
						<div class="img_right_lf"><img src="img/29_lbp_lf.jpg" alt="" style="width: 85px; height: 35px; margin-right: 20px;"/><b style="color: gray;">京卫药业集团</b></div>
						<div class="img_right2_lf"><b style="color: gray; font-size: 13px;">网上O2O药店</b></div>
						<div class="img_right3_lf"><p style="color: gray; font-size: 12px;">客户介绍：京卫药业创立于1998年，经过多年发展目前已形成了带有京卫特色的医药研发、医药生产、药品分销、药品零售的属科工贸一体化的企业集团，目前年销售额已超过100亿元，企业总资产已达180亿元。</p></div>
						<div class="img_right4_lf"><p style="color: gray; font-size: 12px;">电商模式：<img src="img/32_lbp_lf.png" alt="" />pc端<img src="img/35_lbp_lf.png" alt="" />Wap端<img src="img/36_lbp_lf.png" alt="" />微信端<img src="img/23_lbp_lf.png" alt="" />APP端</p></div>
					</li>
					<li>
						<div class="img_left_lf"><img src="img/20_lbp_lf.jpg"/></div>
						<div class="img_right_lf"><img src="img/31_lbp_lf.jpg" alt="" style="width: 85px; height: 35px; margin-right: 20px;"/><b style="color: gray;">缅甸 Wanlida</b></div>
						<div class="img_right2_lf"><b style="color: gray; font-size: 13px;">缅甸新零售</b></div>
						<div class="img_right3_lf"><p style="color: gray; font-size: 12px;">客户介绍：零售行业的主要竞争点分为市场拓展与销售渠道两个方面，若在线上进行市场推广来扩大份额，要砸不少的资金，所以Wanlida Trading希望在早期可以打通线下销售渠道，形成比较高的壁垒，让同类公司难以突围。商联达为其提供缅语及英文版新零售多用户商城系统，助其开拓缅甸电商市场。</p></div>
						<div class="img_right4_lf"><p style="color: gray; font-size: 12px;">电商模式：<img src="img/32_lbp_lf.png" alt="" />pc端<img src="img/35_lbp_lf.png" alt="" />Wap端<img src="img/36_lbp_lf.png" alt="" />微信端<img src="img/23_lbp_lf.png" alt="" />APP端</p></div>
					</li>
					<li>
						<div class="img_left_lf"><img src="img/21_lbp_lf.jpg"/></div>
						<div class="img_right_lf"><img src="img/34_lbp_lf.jpg" alt="" style="width: 85px; height: 35px; margin-right: 20px;"/><b style="color: gray;">万达集团</b></div>
						<div class="img_right2_lf"><b style="color: gray; font-size: 13px;">国有控股</b></div>
						<div class="img_right3_lf"><p style="color: gray; font-size: 12px;">客户介绍：“易企享”是万达财富集团旗下五大战略业务中的重要组成部分。是一家新型互联网电子商务平台。平台专注于服务中小微企业，以“信用”为核心，以“共享、共存、共创、共赢”为理念，助力中小微企业解决发展过程中所面临的“融资难”、“宣传差”、“销路窄”等核心问题。</p></div>
						<div class="img_right4_lf"><p style="color: gray; font-size: 12px;">电商模式：<img src="img/32_lbp_lf.png" alt="" />pc端<img src="img/35_lbp_lf.png" alt="" />Wap端<img src="img/36_lbp_lf.png" alt="" />微信端<img src="img/23_lbp_lf.png" alt="" />APP端</p></div>
					</li>
					<li>
						<div class="img_left_lf"><img src="img/22_lbp_lf.jpg"/></div>
						<div class="img_right_lf"><img src="img/28_lbp_lf.png" alt="" style="width: 85px; height: 35px; margin-right: 20px;"/><b style="color: gray;">凯德集团</b></div>
						<div class="img_right2_lf"><b style="color: gray; font-size: 13px;">世界三大地产集团之一</b></div>
						<div class="img_right3_lf"><p style="color: gray; font-size: 12px;">客户介绍：斐讯数据通信技术有限公司成立于2009年，其全球双总部位于中国上海和成都，在美国和德国设有区域总部，核心产品是K系列路由器+智能健康系列科技产品+家庭健康系列+区块链应用产品等科技产品。商联达为其搭建推啥0元购全返商城平台。</p></div>
						<div class="img_right4_lf"><p style="color: gray; font-size: 12px;">电商模式：<img src="img/32_lbp_lf.png" alt="" />pc端<img src="img/35_lbp_lf.png" alt="" />Wap端<img src="img/36_lbp_lf.png" alt="" />微信端<img src="img/23_lbp_lf.png" alt="" />APP端</p></div>
					</li>
				</ul>
				
			</div>
			<span class="button_left_lf"><</span>
			<span class="button_right_lf">></span>
		</div>
		<!--轮播图JQ-->
		<script src="Jq/jquery-3.5.1.js"></script>
		<script></script>
		<!--商品布局-->
		<link rel="stylesheet" type="text/css" href="css/bootstrap.css"/>
		<section>
			<div class="section_typeface_lf">
				<h1>更多推荐案例</h1>
				<p>我们有着非常多的项目及运营经验，深刻明白产品的每一个优化对企业的升级转型都至关重要</p>
			</div>
			<div class="container lf_centent">
				<ul>
					<li class="col-lg-6 lf_centent_li">
						<img class="lf_img" src="img/2_lbp_lf.jpg"/>
						<div class="content_lf_li_div"><b>中国铁路</b></div>
						<div class="content_lf_li_div2">电商模式：<img src="img/32_lbp_lf.png" alt="" />PC端<img src="img/36_lbp_lf.png" alt="" />微信端<img src="img/14_lbp_lf.png" alt="" />小程序端</div>
						<div class="content_lf_li_div2">关键词：&nbsp;&nbsp;O2O</div>
						<div class="content_lf_li_div3">国家铁路局由中华人民共和国交通运输部管理，属国务院部委管理的国家局，行政级别为副部级，由商联达联合打造的列车超市主要针对国内高铁动车的旅客，旅客可以乘坐列车的时候扫码在线下单，系统会自动定位到车厢及座位号，由列车员配货...</div>
					</li>
					<li class="col-lg-6 lf_centent_li">
						<img src="img/3_lbp_lf.jpg"/>
						<div class="content_lf_li_div"><h2>中国石油</h2></div>
						<div class="content_lf_li_div2">电商模式：<img src="img/32_lbp_lf.png" alt="" />PC端<img src="img/36_lbp_lf.png" alt="" />微信端</div>
						<div class="content_lf_li_div2">关键词：&nbsp;&nbsp;B2C</div>
						<div class="content_lf_li_div3">中国石油是由中央直接管理的国有特大型央企，作为中国境内最大的原油、天然气生产、供应商，中国石油集团业务涉及石油天然气勘探开发、炼油化工、管道运输、油气炼化产品销售、石油工程技术服务等多项业务。经过多轮筛选最终选择商联达为其搭建新零售商城平台...</div>
					</li>
					<li class="col-lg-6 lf_centent_li">
						<img src="img/35_lbp_lf.jpg"/>
						<div class="content_lf_li_div"><h2>碧桂园</h2></div>
						<div class="content_lf_li_div2">电商模式：<img src="img/32_lbp_lf.png" alt="" />PC端<img src="img/36_lbp_lf.png" alt="" />微信端</div>
						<div class="content_lf_li_div2">关键词：&nbsp;&nbsp;家具商城</div>
						<div class="content_lf_li_div3">碧桂园集团，即碧桂园控股有限公司（股份代号：2007.HK），总部位于广东佛山顺德，是中国最大的新型城镇化住宅开发商。采用集中及标准化的运营模式，业务包含物业发展、建安、装修、物业管理、物业投资、酒店开发和管理...</div>
					</li>
					<li class="col-lg-6 lf_centent_li">
						<img src="img/9_lbp_lf.jpg"/>
						<div class="content_lf_li_div"><h2>澳兰斯</h2></div>
						<div class="content_lf_li_div2">电商模式：<img src="img/32_lbp_lf.png" alt="" />PC端<img src="img/36_lbp_lf.png" alt="" />微信端</div>
						<div class="content_lf_li_div2">关键词：&nbsp;&nbsp;B2C</div>
						<div class="content_lf_li_div3">澳兰斯--广州澳兰斯水处理设备有限公司是一家集研发、生产和销售健康家电为一体的国家高新技术企业。公司拥有净水器、空气净化器、富氢水研发能力，获得多项自主专利和证书...</div>
					</li>
					<li class="col-lg-6 lf_centent_li">
						<img src="img/4_lbp_lf.jpg"/>
						<div class="content_lf_li_div"><h2>雷允上</h2></div>
						<div class="content_lf_li_div2">电商模式：<img src="img/32_lbp_lf.png" alt="" />PC端<img src="img/36_lbp_lf.png" alt="" />微信端<img src="img/23_lbp_lf.png" alt="" />APP</div>
						<div class="content_lf_li_div2">关键词：&nbsp;&nbsp;药业</div>
						<div class="content_lf_li_div3">雷允上药业集团是四大药堂之一，国家首批中华老字号，国家绝密项目及国家非物质文化遗产拥有者。雷允上始创于1734年，至今已近300年，其创始人雷大升（字允上，号南山，1696-1779）为清吴门名医，是“吴门医派”的集大成者...</div>
					</li>
					<li class="col-lg-6 lf_centent_li">
						<img src="img/5_lbp_lf.jpg"/>
						<div class="content_lf_li_div"><h2>大光明眼睛</h2></div>
						<div class="content_lf_li_div2">电商模式：<img src="img/32_lbp_lf.png" alt="" />PC端<img src="img/14_lbp_lf.png" alt="" />小程序<img src="img/36_lbp_lf.png" alt="" />微信端</div>
						<div class="content_lf_li_div2">关键词：&nbsp;&nbsp;O2O</div>
						<div class="content_lf_li_div3">雷允上药业集团是四大药堂之一，国家首批中华老字号，国家绝密项目及国家非物质文化遗产拥有者。雷允上始创于1734年，至今已近300年，其创始人雷大升（字允上，号南山，1696-1779）为清吴门名医，是“吴门医派”的集大成者...</div>
					</li>
					<li class="col-lg-6 lf_centent_li">
						<img src="img/6_lbp_lf.jpg"/>
						<div class="content_lf_li_div"><h2>垦丰集团</h2></div>
						<div class="content_lf_li_div2">电商模式：<img src="img/32_lbp_lf.png" alt="" />PC端<img src="img/14_lbp_lf.png" alt="" />小程序<img src="img/36_lbp_lf.png" alt="" />微信端<img src="img/23_lbp_lf.png" alt="" />APP</div>
						<div class="content_lf_li_div2">关键词：&nbsp;&nbsp;O2O</div>
						<div class="content_lf_li_div3">雷允上药业集团是四大药堂之一，国家首批中华老字号，国家绝密项目及国家非物质文化遗产拥有者。雷允上始创于1734年，至今已近300年，其创始人雷大升（字允上，号南山，1696-1779）为清吴门名医，是“吴门医派”的集大成者...</div>
					</li>
					<li class="col-lg-6 lf_centent_li">
						<img src="img/7_lbp_lf.jpg"/>
						<div class="content_lf_li_div"><h2>好机严选</h2></div>
						<div class="content_lf_li_div2">电商模式：<img src="img/32_lbp_lf.png" alt="" />PC端<img src="img/14_lbp_lf.png" alt="" />小程序<img src="img/36_lbp_lf.png" alt="" />微信端<img src="img/23_lbp_lf.png" alt="" />APP</div>
						<div class="content_lf_li_div2">关键词：&nbsp;&nbsp;分销</div>
						<div class="content_lf_li_div3">好机严选是广州芯享家科技有限公司旗下品牌，是国内专业的二手手机交易平台，主营苹果、华为、oppo，vivo，小米等9成新及以上的原装正品手机...</div>
					</li>
					<li class="col-lg-6 lf_centent_li">
						<img src="img/8_lbp_lf.jpg"/>
						<div class="content_lf_li_div"><h2>华冠教育</h2></div>
						<div class="content_lf_li_div2">电商模式：<img src="img/36_lbp_lf.png" alt="" />微信端<img src="img/23_lbp_lf.png" alt="" />APP</div>
						<div class="content_lf_li_div2">关键词：&nbsp;&nbsp;教育直播</div>
						<div class="content_lf_li_div3">华冠教育的业务格局是以商业营销和商学教育为主题的培训基地，公司主要业务涉及企业内部培训、个人成长学习方案制定、品牌营销策划、销售解决方案、高端资源整合平台等多个领域范围。产品被广泛应用于教育科研、政府、企业、个人等众多行业，得到用户广泛赞誉...</div>
					</li>
					<li class="col-lg-6 lf_centent_li">
						<img src="img/10_lbp_lf.jpg"/>
						<div class="content_lf_li_div"><h2>郴州日报</h2></div>
						<div class="content_lf_li_div2">电商模式：<img src="img/32_lbp_lf.png" alt="" />PC端<img src="img/36_lbp_lf.png" alt="" />微信端<img src="img/23_lbp_lf.png" alt="" />APP</div>
						<div class="content_lf_li_div2">关键词：&nbsp;&nbsp;教育直播</div>
						<div class="content_lf_li_div3">《郴州日报》是中共郴州市委机关报，1950年发刊，郴州地区最重要、最权威的新闻媒体，联合商联达打造郴州日报电子扶贫商城...</div>
					</li>
					<li class="col-lg-6 lf_centent_li">
						<img src="img/12_lbp_lf.jpg"/>
						<div class="content_lf_li_div"><h2>二十冶</h2></div>
						<div class="content_lf_li_div2">电商模式：<img src="img/32_lbp_lf.png" alt="" />PC端<img src="img/36_lbp_lf.png" alt="" />微信端<img src="img/23_lbp_lf.png" alt="" />APP</div>
						<div class="content_lf_li_div2">关键词：&nbsp;&nbsp;内部采购</div>
						<div class="content_lf_li_div3">中国二十冶集团有限公司成立于1973年6月1日，是世界500强企业——中国冶金科工集团有限公司旗下重要骨干子企业。目前拥有建筑工程、冶金工程、市政公用工程等施工总承包特级资质3项，冶金行业、建筑行业（建筑工程、人防工程）、市政行业甲级设计资质4项...</div>
					</li>
					<li class="col-lg-6 lf_centent_li">
						<img src="img/13_lbp_lf.jpg"/>
						<div class="content_lf_li_div"><h2>奥特莱斯</h2></div>
						<div class="content_lf_li_div2">电商模式：<img src="img/32_lbp_lf.png" alt="" />PC端<img src="img/36_lbp_lf.png" alt="" />微信端</div>
						<div class="content_lf_li_div2">关键词：&nbsp;&nbsp;O2O</div>
						<div class="content_lf_li_div3">斯普瑞斯奥特莱斯是全国最大的奢侈品购物公园。经过多轮筛选最终选择商联达为其搭建官方商城平台，商联达在电商商城搭建方面的丰富经验及在新零售解决方案方面的专业产品与落地的能力是“斯普瑞斯奥特莱斯”选择商联达的重要原因...</div>
					</li>
					<li class="col-lg-6 lf_centent_li">
						<img src="img/14_lbp_lf.jpg"/>
						<div class="content_lf_li_div"><h2>贝蒂斯</h2></div>
						<div class="content_lf_li_div2">电商模式：<img src="img/32_lbp_lf.png" alt="" />PC端<img src="img/36_lbp_lf.png" alt="" />微信端</div>
						<div class="content_lf_li_div2">关键词：&nbsp;&nbsp;积分商城</div>
						<div class="content_lf_li_div3">贝蒂斯橄榄油始于1914年，由西班牙Torres Y Ribelles,S.A.生产。Torres Y Ribelles,S.A.是西班牙橄榄油出口商协会ASOLIVA会员。1924年，Torres Y Ribelles,S.A.凭借贝蒂斯橄榄油的卓越品质，被西班牙国王阿方索十三世授为西班牙皇室用油供应商...</div>
					</li>
					<li class="col-lg-6 lf_centent_li">
						<img src="img/17-24.jpg"/>
						<div class="content_lf_li_div"><h2>中港星</h2></div>
						<div class="content_lf_li_div2">电商模式：<img src="img/32_lbp_lf.png" alt="" />PC端<img src="img/36_lbp_lf.png" alt="" />微信端<img src="img/23_lbp_lf.png" alt="" />APP</div>
						<div class="content_lf_li_div2">关键词：&nbsp;&nbsp;工商服务</div>
						<div class="content_lf_li_div3">中港星集团成立于2005年，在深圳和香港两地建有运营总部，为海内外企业提供专业、便捷的服务。发展至今，中港星集团组建了超1000人的专业团队，布局了“一个研究院，两大中心，四个事务所，六个专业子公司”的组织架构...</div>
					</li>
				</ul>
			</div>
			<div class="lf_bottom_2">
				<div class="lf_bottom_2_1">更多案列点这里</div>
				<div class="lf_bottom_2_2">立即免费体验</div>
			</div>
		</section>
		<div class="ending_top_lf">
			<div class="ending_top_lf_1"><p>马上开启自己的电商业务</p></div>
			<div class="ending_bottom_lf_2">立即体验</div>
		</div>
		<div class="ending_bottom_lf"></div>
	</body>
</html>
