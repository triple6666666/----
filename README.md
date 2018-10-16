# 招新页面
<html>

<head>

<meta http-equiv="Content-Type" content="text/html; charset=gb2312">

<title>清泽心雨招新</title>

</head>

<body>

姓名

<input type="text" name="name" value="请输入你的姓名">

<br><br>

<form action="save.php" method="post">

<label>男</label>

<input type="radio" value="1" name="g" />

<label>女</label>

<input type="radio" value="2" name="g" />

</form>

<br>

专业

<input type="text" name="major">

<br><br>

电话号码

<input type="text" name="tel">

<br><br>

电子邮箱

<input type="text" name="email">

<br><br>

<form action="save.php" method="post">

<label>意向部门：</label>

<select>

<option value="1" selected="selected">综合办公室</option>

<option value="2">公关策划部</option>

<option value="3">网络安全部</option>

<option value="4">视觉设计部</option>

<option value="5">技术开发部</option>

<option value="6">综合媒体集团</option>

<option value="7">新闻集团</option>

<option value="8">视频集团</option>

</select>

</form>

<br>

<input type="submit" value="提交" name="submit"/>

</body>

</html>
