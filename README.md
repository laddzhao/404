# 动画效果的404网页
![image](https://xn--btvv65f45f.site/404/img/404.gif)

```
<!-- 
//
//                       _oo0oo_
//                      o8888888o
//                      88" . "88
//                      (| -_- |)
//                      0\  =  /0
//                    ___/`---'\___
//                  .' \\|     |// '.
//                 / \\|||  :  |||// \
//                / _||||| -:- |||||- \
//               |   | \\\  - /// |   |
//               | \_|  ''\---/''  |_/ |
//               \  .-\__  '-'  ___/-. /
//             ___'. .'  /--.--\  `. .'___
//          ."" '<  `.___\_<|>_/___.' >' "".
//         | | :  `- \`.;`\ _ /`;.`/ - ` : | |
//         \  \ `_.   \_ __\ /__ _/   .-` /  /
//     =====`-.____`.___ \_____/___.-`___.-'=====
//                       `=---='
//
//
//     ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
//
//           佛祖保佑       永不宕机     永无BUG
//
//       佛曰:
//               写字楼里写字间，写字间里程序员；
//               程序人员写程序，又拿程序换酒钱。
//               酒醒只在网上坐，酒醉还来网下眠；
//               酒醉酒醒日复日，网上网下年复年。
//               但愿老死电脑间，不愿鞠躬老板前；
//               奔驰宝马贵者趣，公交自行程序员。
//               别人笑我忒疯癫，我笑自己命太贱；
//               不见满街漂亮妹，哪个归得程序员？
//
 -->
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<title></title>
		<style>
			body{
				background-color: #000;/* 网页背景颜色 */
			}
			/* 位置 */
			#box404{
				display: flex;
				flex-direction: row;
				
			}
			.box4{
				transform: translate(20px,40px);
				position: inherit;
				float: left;
			} 
			.box0{
				transform: translate(40px,40px);
				position: inherit;
				float: left;
			} 
			.box4-2{
				transform: translate(60px,40px);
				position: inherit;
				float: left;
			} 
			/* 位置结束 */
			
			/* 边框 */
			#box1{
				border-style: double;/* 边框样式 */
				width: 100px;/* 宽度 */
				height: 100px;/* 高度 */
				border-width: 0px 0px 10px 10px;/* 边框宽度（上右下左） */
				border-color: #55ff7f;/* 边框颜色 */
				float: left;/* 浮动（左） */
				border-radius: 5px;/* 圆角*/
			}
			#box2{
				border-style: double;
				width: 50px;
				height: 200px;
				border-width: 10px 10px 0px 0px;
				border-color: #55ff7f;
				border-radius: 5px;
			}
			#box3{
				border-style: double;
				width: 90px;
				height: 190px;
				border-width: 10px 10px 10px 10px;
				border-color: #55ff7f;
				border-radius: 5px;
			}
			#box4{
				border-style: double;
				width: 100px;
				height: 100px;
				border-width: 0px 0px 10px 10px;
				border-color: #55ff7f;
				float: left;
				border-radius: 5px;
			}
			#box5{
				border-style: double;
				width: 50px;
				height: 200px;
				border-width: 10px 10px 0px 0px;
				border-color: #55ff7f;
				border-radius: 5px;
			}
			/* 边框结束 */
			/* 动画4-左半部分 */
			@keyframes img1 {
				0%{
					top: 0px;
					left: 0px;
					height: 40px;
				}
				25%{
					top: 100px;
					left: 0px;
					height: 10px;
				}
				50%{
					top: 100px;
					left: 100px;
				}
				75%{
					top: 100px;
					left: 0px;
				}
				100%{
					top: 0px;
					left: 0px;
				}
			}
			/* 动画4右半部分 */
			@keyframes img1-1 {
				0%{
					top: 160px;
					left: 50px;
					height: 40px;
				}
				25%{
					top: 0px;
					left: 50px;	
					height: 10px;
				}
				50%{
					top: 0px;
					left: 0px;
				}
				75%{
					top: 0px;
					left: 50px;
				}
				100%{
					top: 200px;
					left: 50px;
				}
			}
			/* 动画0 */
			@keyframes img2 {
				0%{
					top: 0px;
					left: 0px;
					height: 40px;
					width: 10px;
				}
				25%{
					top: 200px;
					left: 0px;
					height: 10px;
					width: 10px;
				}
				50%{
					top: 200px;
					left: 100px;
					height: 10px;
					width: 10px;
				}
				75%{
					top: 0px;
					left: 100px;
					height: 10px;
					width: 10px;
					
				}
				100%{
					top: 0px;
					left: 0px;
					height: 10px;
					width: 40px;
				}
			}
			/* 右侧动画4-左半部分 */
			@keyframes img1 {
				0%{
					top: 100px;
					left: 60px;
					width: 40px;
				}
				25%{
					top: 100px;
					left: 0px;
					width: 10px;
				}
				50%{
					top: 0px;
					left: 0px;
				}
				75%{
					top: 100px;
					left: 0px;
				}
				100%{
					top: 100px;
					left: 100px;
				}
			}
			/* 右侧右侧动画4右半部分 */
			@keyframes img1-1 {
				0%{
					top: 0px;
					left: 0px;
					width: 40px;
				}
				25%{
					top: 0px;
					left: 50px;	
					width: 10px;
				}
				50%{
					top: 200px;
					left: 50px;
				}
				75%{
					top: 0px;
					left: 50px;
				}
				100%{
					top: 0px;
					left: 0px;
				}
			}
			/* 运动的图形 */
			#box1-img1{
				animation: img1 4s infinite;/* 动画定义（把上面设置的动画加载进来）4秒 */
				width: 10px;/* 宽度 */
				height: 10px;/* 高度 */
				background-color: #ffffff;/* 颜色 */
				position: absolute;/* 定位方式 */
				z-index: 1;/* 最顶层 */
				border-radius: 10px;/* 圆角 */
			}
			#box2-img1{
				animation: img1-1 4s infinite;
				width: 10px;
				height: 10px;
				background-color: #ffffff;
				position: absolute;
				z-index: 1;
				border-radius: 10px;
			}
			#box3-img1{
				animation: img2 4s infinite;
				width: 10px;
				height: 10px;
				background-color: #ffffff;
				position: absolute;
				z-index: 1;
				border-radius: 10px;
			}
			#box4-img1{
				animation: img1 4s infinite;
				width: 10px;
				height: 10px;
				background-color: #ffffff;
				position: absolute;
				z-index: 1;
				border-radius: 10px;
			}
			#box5-img1{
				animation: img1-1 4s infinite;
				width: 10px;
				height: 10px;
				background-color: #ffffff;
				position: absolute;
				z-index: 1;
				border-radius: 10px;
			}
			/* 运动的图形结束 */
			
		</style>
	</head>
	<body>
		<div id="box404">
		<!-- 4 -->
		<div class="box4">
		<div id="box1"></div>
		<div id="box1-img1"></div>
		<div id="box2"></div>
		<div id="box2-img1"></div>
		</div>
		<!-- 4结束 -->
		<!-- 0 -->
		<div class="box0">
		<div id="box3"></div>
		<div id="box3-img1"></div>
		</div>
		<!-- 0结束 -->
		<!-- 第二个4 -->
		<div class="box4-2">
		<div id="box4"></div>
		<div id="box4-img1"></div>
		<div id="box5"></div>
		<div id="box5-img1"></div>
		</div>
		<!-- 第二个4结束 -->
		</div>
	</body>
</html>
```
