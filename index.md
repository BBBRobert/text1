<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
 <head>
  <title> New Document </title>
  <meta name="Generator" content="vsCode">
  <meta name="Author" content="x">
  <meta name="Keywords" content="">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0">
  <meta http-equiv="X-UA-Compatible" content="IE=edge chrome=1">
  <!--IE8浏览器的显示方式：IE=edge以IE最高版本显示 Chrome=1以谷歌浏览器模式渲染-->
  <meta name="referrer" content="never">
  <!--告诉浏览器链接的来源（可以计算链接的访问量）-->
  <meta name="format-detection" content="telephone=no,email=no,address=no">
  <!--格式检测（数字，邮箱，地址）no 不识别为电话号码，邮箱，地址-->
  <meta name="renderer" content="webkit">
  <meta name="Description" content="">

  <style type="text/css">
	*{
		margin: 0;
		padding: 0;
		}
	ul,li{
		list-style:none;
		}
	a{
		text-decoration:none;
		}
	input{
		outline-style:none;
		border: 0px;
	}
	#form1{
		
		margin-top:20px;
		width:100%;
		margin:2px auto;
	}
	#form1 form span{
		color:black;
	}
	.row { 
		margin-top: 25px;
		height: 25px;
		line-height: 8px;
		border-bottom: 1px solid #c7c6c6;
		width:100%; 
	}
	.row1 {
		margin-top: 25px;
		height:100px;
		line-height: 26px;
		border-bottom: 1px solid #c7c6c6;
		width:100%; 
		
	}
	.input { 
		position: relative;
		width: 100%;
		height: 26px; 
	}
	.input input { 
		display: block;
		width: 100%;
		height: 26px;
		border:none;
		background: none;
		outline:none; 
	}
	.input label { 
		position: absolute;
		top:0;
		left:0;
		height: 26px;
		line-height: 26px;
		font-size: 14px;
		color: #999; 
	}
	.select select{
		display:block;
		width:100%;
		border:none;
		outline:none;
	}
	input[type=date]::-webkit-inner-spin-button { visibility: hidden; }
	.button{
		width:100%;
		height:40px;
		background: #ff961e;
		outline: none;
		margin:20px 0 30px 0;
	}
	

	.title{
		
	}
  </style>
 </head>

 <body>
	  <div id="div1" style="background-color: white;width: 100%;padding: 10px; height: 30px;position: fixed;top: 0rem;border: 1px solid #c7c6c6; z-index: 3;">
		  <ul>
		  <li style="display: inline-block;color: grey;padding-left: 38px;"><a href="#tb" style="color: grey;">表单信息</a></li>
		  <li style="display: inline-block;color: grey;padding-left: 38px;"><a href="#dibu" style="color: grey;">审批意见</a></li>
		  <li style="display: inline-block;color: grey;padding-left: 38px;">流程进度</li>
		  </ul>
		  
	  </div>
	  <div style="width: 100%;height: 80px;">
		  
	  </div>
	  
	 <div class='title' style="text-align: center;">
		 
		<p id="tb">疫情防控期间本科生临时出入校园(请/销假)申请</p>
		 </div>
	<div style="width: 100%;  height: 10px; background-color: gainsboro "
		
		</div>
    <div id="form1">
        <form action="" method="post" onsubmit="return checkForm(this)">
            <br>
            <div class="row ">
                <div class="input">
                    <span>&#8195;学院：</span><span style="float: right;color: gray;">针推学院&#8195;</span>
                    <input id="p_cardid" type="text" name="p_cardid">
                    <i class="CardNo"><b></b></i>
                </div>
            </div>
			<div class="row ">
			    <div class="input">
			        <span>&#8195;班级：</span><span style="float: right;color: gray;">针推201&#8195;</span><br>
			        <input type="text" name=""/><br>
			    </div>
             </div>
			<div class="row ">
			    <div class="input" >
			        <span>&#8195;姓名：</span><span style="float: right;color: gray;">张三&#8195;</span><br>
			        <input type="text" name=""/><br>
			    </div>
			</div>
			<div class="row ">
			    <div class="input" >
			        <span>&#8195;学号：</span><span style="float: right;color:#488AC7;">12345678&#8195;</span><br>
			        <input type="text" name=""/><br>
			    </div>
			</div>
			<div class="row ">
			    <div class="input" >
			        <span style="color: red;">* </span><span>宿管站：</span><span style="float: right;color: gray;">仙林1号站&#8195;</span><br>
			        <input type="text" name=""/>
			    </div>
			</div>
			<div class="row ">
			    <div class="input" >
			        <span style="color: red;">* </span><span>宿舍号：</span><span style="float: right;color: gray;">C66-6666&#8195;</span><br><br>
			        <input type="text" name=""/><br>
			    </div>
			</div>
			<div class="row ">
			    <div class="input" >
			         <span style="color: red;">* </span><span style="color: blue;">是否港澳台侨学生：</span><span style="float: right;color: gray;">否&#8195;</span><br><br>
			        <input type="text" name=""/><br>
			    </div>
			</div>
            <div class="row">
                <div class="select">
                    <span style="color: red;">* </span><span>联系电话：</span><br>
                    
                </div>
            </div>
			<div class="row ">
			    <div class="input" >
			        <span style="color: red;">* </span><span>请假区间：</span><span style="float: right;color: gray;">2021-10-11至2021-10-11&#8195;</span><br><br>
			        <input type="text" name=""/><br>
			    </div>
			</div>
			<div class="row ">
			    <div class="input" >
			        <span style="color: blue;">&#8195;请假天数：</span><span style="float: right;color: gray;">1&#8195;</span><br><br>
			        <input type="text" name=""/><br>
			    </div>
			</div>
			<div class="row ">
			    <div class="input" >
			       <span style="color: red;">* </span><span>外出事由：</span><span style="float: right;color: gray;">实习&#8195;</span><br><br>
			        <input type="text" name=""/><br>
			    </div>
			</div>
			<div class="row ">
			    <div class="input" >
			       <span style="color: red;">* </span><span>家长是否知情：</span><br>
			        <input type="text" name=""/><br>
			    </div>
			</div>
			<div class="row ">
			    <div class="input" >
			       <span style="color: red;">* </span><span>紧急联系人姓名：</span><br>
			        <input type="text" name=""/><br>
			    </div>
			</div>
			<div class="row ">
			    <div class="input" >
			        <span style="color: red;">* </span><span>紧急联系人电话：</span><span style="float: right; color: grey;">李四&#8195;</span><br>
			        
			    </div>
			</div>
			<div class="row ">
			    <div class="input" >
			        <span style="color: red;">* </span><span style="color: blue;">详细目的地：</span><span style="float: right; color: grey;">江苏省&#8195;
			        
			    </div>
			</div>
			<div class="row ">
			    <div class="input" >
			        <span>&#8195;南京市</span><span style="float: right; color: grey;" >鼓楼区汉中路136号江苏省口腔医院&#8195;</span><br>
			        
			    </div>
			</div>
            <div class="row">
                <div class="input">
                     <Aspan style="color: red;">* </span><span>出校校区：</span><span style="float: right;color: gray;">仙林校区&#8195;</span><br><br>
                    <input id="p_tel" type="text" name="p_tel"/><br>
                    <i class="Phone"><b></b></i>
                </div>
            </div>
            <div class="row">
                <div class="input">
                     <span style="color: red;">* </span><span>进校校区：</span><span style="float: right;color: gray;">仙林校区&#8195;</span><br><br>
                    <input type="text" name=""/><br>
                </div>
            </div>
            
            
            
            <div class="row1">
                <div class="input">
                    <span>&#8195;&#8195;辅导员意见：</span><br><p style="color: gray;">&#8195;&#8195;&#8195;&#8195;&#8195;同意请假申请,学生回校后进入销假环节</p><br>
					<span style="float: right;color: grey;">一 一&#8195;诸葛健2021-10-09 20.06&#8195;</span><br>
                    <input type="text" name="name"/><br>
                </div>
            </div>
			
            
            <div class="row">
                <span>&#8195;流程进度</span><span style="color: blue; float: right;">查看&#8195;&#8195;</span>
            </div>
			<ul>
				<li id="dibu"></li>
			</ul>
         </form>
		
		 	
		 
		 
    </div>
	<div style="width: 100%; height: 0.5px;color:grey ;">
		
	</div>
	<script type="text/javascript">
		

		function checkForm(){ 
		var phone = document.getElementById('p_tel').value;
		var cardid=document.getElementById('p_cardid').value;
		if(phone==""&&cardid==""){
			alert("请输入手机号和身份证号！");return false; 
			}else if(phone==""){
				alert("请输入手机号！");return false; 
				}else{
					if(!(/^1(3|4|5|7|8)\d{9}$/.test(phone))){ 
					alert("手机号码有误，请重新输入"); 
					return false; 
					} 
		if(cardid==""){
			alert("请输入身份证号！");return false; 
			}
		}
		if(!(/^[1-9]{1}[0-9]{14}$|^[1-9]{1}[0-9]{16}([0-9]|[xX])$/.test(cardid))){
			alert("身份证号有误，请重新输入");return false; 
		}
	}

	function aaa(){
		var value=document.getElementById("tableType").value;
		var ojobs=document.getElementById("jobs");

		if(value=='0'){
			ojobs.innerHTML="<option>校学生会111</option><option>校学生会222</option><option>校学生会333</option>"
		}else if(value=='1'){
			ojobs.innerHTML="<option>校青志联111</option><option>校青志联222</option><option>校青志联333</option>"
			}else if(value=='2'){
				ojobs.innerHTML="<option>校社联111</option><option>校社联222</option><option>校社联333</option>"
				}else if(value=='3'){
					ojobs.innerHTML="<option>国旗护卫队111</option><option>国旗护卫队222</option><option>国旗护卫队333</option>"
					}else if(value=='4'){
						ojobs.innerHTML="<option>圣兵爱心社111</option><option>圣兵爱心社222</option><option>圣兵爱心社333</option>"
						}

    
	}
	</script>
 </body>
</html>

