---
layout: false
---
{% raw %}
<!DOCTYPE html>
<html>
<head>
	<title>IPFS图床</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width,initial-scale=1.0,maximum-scale=1.0,minmum-scale=1.0,user-scalable=no">
  <link rel="stylesheet" href="./static/style.css">
	 <link rel="shortcut icon" href="../imgs/favicon.ico">
	<link href="./static/buttons.css" rel="stylesheet">
	<script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.min.js"></script>
	<script src="./static/file.js"></script>
</head>
<body>
	<input id="file" type="file" multiple="multiple" style="display: none;">
	<div class="container">
		<div class="upload">
			<div class="content" id="dragbox">
				<img src="https://cf-ipfs.com/ipfs/QmTUV6gN39gYyoZKCVcxN7sr3fdDck4Nyah58KXyz8nuuM" width="100px" height="100px"/>
				<br>
				<p class="desc">点击上传 / 粘贴上传 / 拖拽上传</p>
				<p class="desc">永久的去中心化保存和共享图片</p>
				<p class="desc">#只支持上传图片其他的加载不出来#</p>
			</div>
		</div>
		<div class="filelist">
			<div class="title">上传列表
			    <div class="copyall" style="display:none">
					<button onclick="sel(this);" name="icu" id="_url">URL</button>
					<button onclick="sel(this);" name="icu" id="_html">HTML</button>
					<button onclick="sel(this);" name="icu" id="_Ubb">UBB</button>
					<button onclick="sel(this);" name="icu" id="_markdown">MD</button>
                </div>
            </div>
			<div class="list"></div>
		</div>
	</div>
	<div id="footer" style="position:fixed; width:auto; text-align:center; bottom:0px; display:block;">
		<div style="height: 80px">
		<a href="https://kyui.icu/" class="button button-pill button-raised button-primary">Check Kyui.icu!</a>
	</div>
</body>
</html>
{% endraw %}
