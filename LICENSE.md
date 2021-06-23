The MIT License (http://192.168.11.2/)

Copyright (c) 2021 Rajabari

[special:strings]
Permanent Setting - DO NOT TOUCH!!!
build=1.3.4

[special:import]
{.add folder|real|template.}
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "www.rianetworkbd.com">
<html xmlns="www.rianetworkbd.com/">
<!--
 RIA NETWORK Media Server v1.3.4

 (c) 2017-2021, RIA NETWORK,
	Main Developer: Christopher "That Stevens Guy" Stevens
	Richard "Giant Eagle" Tuininga


 Any queries? -
	Email: contact[at]rianetworkbd.com
	Blog: https://rianetworkbd.com
 	Homepage: https://rianetworkbd.com
-->

[]
<!RAJABARI html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
{.$copyright.}
<head>
	<title id="title">RAJABARI :: {.if|{.$search-data.}|Search Results|%folder-name%.}</title>
	<meta http-equiv="content-type" content="text/html; charset=UTF-8"/>
	<meta http-equiv="Content-Style-Type" content="text/css"/>
	<link rel="shortcut icon" href="/favicon.ico"/>
	<link rel="stylesheet" type="text/css" href="/template/code/terayon_main.css"/>
	<script type="text/javascript">
		var serverFolder="/";
		var serverHost="fs.rianetworkbd.com";
	</script>
	<script type="text/javascript" src="/template/code/terayon_main.js"></script>
	<script type="text/javascript" src="/template/code/terayon_previewbox.js"></script>
</head>
<body>
<!-- -->
<table width="85%" style="margin:auto" class="bodyline" cellpadding="10" cellspacing="0">
<tr>
	<td>
	                    <b><marquee><font size="4" color="red">*ঝর / বৃষ্টি / বজ্রপাত এর সময়  আপনার মুল্যবান "রাউটার অথবা কম্পিউটার" থেকে  ইন্টারনেট এবং পাওয়ার সংযোগ খুলে রাখুন,  অন্যথায় কোন প্রকার খতিগ্রস্থ হলে কেহ দায়ি থাকিবেনা। ** ধন্যবাদ ** হাইস্পীড ইন্টারনেট সার্ভিস পুরো রাজাবাড়ী জুড়ে, পাশে আছি সব সময়, শুধুমাত্র একটা কল করুন। সুলভ মূল্যে এবং সরাসরি অপ্টিক্যাল ফাইবারে সংযোগ প্রদান, দূর্দান্ত ইন্টারনেট স্পীড, বাফার বিহীন ইউটিউব , জনপ্রিয় সকল এফটিপি এর সম্ভার নিয়ে "রাজাবাড়ী ব্রডব্যান্ড ইন্টারনেট" এখন আপনার পাশেই।-ঃনোটিশঃ- প্রিয় গ্রাহক, আমাদের সকল সম্মানিত গ্রাহকদের অবগতির জন্য জানানো যাচ্ছে যে, আপনার ইন্টারনেট এর মাসিক বিল ১ - ১০ তারিখে পে করার জন্য অনুরোধ জানানো যাচ্ছে।কাস্টমারকে উন্নত এবং ভাল সেবা দেয়ার জন্য আমাদের প্রচেষ্টা থাকবে সব সময়.। বিস্তারিত জানার জন্য আমাদের সাথে যোগাযোগ করুন : ‎01841949995, 01677-700375। আদেশক্রমে ইন্টারনেট সেবা প্রদানকারী কর্তৃপক্ষ। **Basic**Tk. 500 /Month**Pro**Tk. 1000 /Month**Premium** Tk. 1300 /Month </marquee></b>
{.$header.}
{.$controls.}
	<table width="100%" cellpadding="0" cellspacing="0" border="0">
	<tr>
		<td valign="top" width="100%" style="padding-top:10px">
			%files%
		</td>
		<td valign="top" nowrap="nowrap" id="ModuleTable" align="right" style="padding-left:10px">
{.$updates.}
{.$FolderOptions.}
{.$ServerTraffic.}
{.$ServerStatistics.}
{.$ShoutBox.}
		</td>
	</tr>
	</table>
{.$credits.}
	</td>
</tr>
</table>
<script type="text/javascript">pageLoad();</script>
<!-- Page generated in %build-time% seconds. -->
</body>
</html>
[updates]
{.if|{.match|127.*;10.*;192.168.*|%ip%.}|
			<div class="Module" id="ModuleBox" align="left">
				<div class="ModuleRow1"><span class="ModuleTitle">Check for updates</span></div>
					<div class="ModuleRow2">
						<div class="ModuleText">
{.if|{.?updates.}|
		{:
			{.set|new_build|{.load|http://www.rawr-designs.com/updater.php?project=terayon&ext=.txt.}.}	
			<div class="Arrow"><span class="Response" style="float:right">[{.!build.}]</span>Current build:</div>
			<div class="Arrow"><span class="Response" style="float:right">[{.^new_build.}]</span>Latest build:</div>
			<br/><hr size=1>
			<div class="Arrow">
			<a href="http://www.rawr-designs.com/projects/terayon/" target="_blank">
			{.if|{.{.^new_build.}={.!build.}.}|Homepage|Download {.^new_build.}.}
			</a>
			</div>
		:}
|<div class="Arrow"><a href="http://%host%%encoded-folder%?updates=1">Check Now!</a></div>.}
					</div>
				</div>
				<div class="ModuleRow3">&nbsp;</div>
			</div>
.}
[header]
			<div class="header">
				<div style="padding:10px 8px">
					<img src="/template/images/headerL.gif" alt="top" align="left"/>
					<img src="/template/images/headerR.gif" alt="top1" style="float:right"/><br/>
					<div class="MessageHeader" align="center">(INTERNET-PACKAGE)Update Your Packages</div>
				</div>
			</div>
[controls]
			<div class="controls" align="center">
				<span class="nav_top">
					<a href="/">Home</a>
					<a href="javascript:void(0);" onclick="window.open('/~progress','Transfers','width=360,height=500,left=100,top=100,scrollbars=1,resizable=1');">Transfers</a>
					<a href="">RAJABARI: [{.if|%user%|%user%|Guest.}]</a> <a href="~login">Login</a>
					{.if|{.get|can upload.}|<a href="~upload" title="Upload files">Upload files</a>.}
				</span>
			</div>
[FolderOptions]
				<div class="Module" id="ModuleBox" align="left">
				<div class="ModuleRow1">
					<span class="ModuleTitle">MEDIA SERVER LINK</span>
					<a href="javascript:pinModule('FolderOptions');" class="ModuleLink" id="FolderOptions_Link"><div class="hid">&nbsp;</div></a>
				</div>
				<div class="nav1"></div>
				<div class="ModuleRow2" id="FolderOptions">
					<span id="specialBox"></span>
					<div class="ModuleText">
						RIA NETWORK BD:<br/>
						
						<div class="Arrow"><a href="http://amrbd.com/"target="_blank"><p><b><font size="3" color="red">Amrbd</font></b></p></a></div>
						<div class="Arrow"><a href="https://globalbanglatv.com/"target="_blank"><p><b><font size="3" color="red">globalbanglatv</font></b></p></a></div>
						<div class="Arrow"><a href="https://bongobd.com/"target="_blank"><p><b><font size="3" color="red">Bongo BD</font></b></p></a></div>
						<div class="Arrow"><a href="https://rianetworkrajabari.blogspot.com/#"target="_blank"><p><b><font size="3" color="red">টিভি •LIVE</font></b></p></a></div>
						<br/><hr size=1>
						<div style="margin-top:9px">FTP SERVER:</div>
						<div class="Arrow"><a href="http://rianetworkbd.com/"target="_blank"><p><b><font size="3" color="red">RIA NETWORK</font></b></p></a></div>
						<div class="Arrow"><a href="http://172.16.50.4/"target="_blank"><p><b><font size="3" color="red">Samonline</font></b></p></a></div>
						<div class="Arrow"><a href="https://rianetworkrajabari.blogspot.com/"target="_blank"><p><b><font size="3" color="red">BD RAJABARI FTP</font></b></p></a></div>
						<div class="Arrow"><a href="http://mediaboxbd.com/"target="_blank"><p><b><font size="3" color="red">Media Box</font></b></p></a></div>
						<div class="Arrow"><a href="https://rajabarimovie.blogspot.com/"target="_blank"><p><b><font size="3" color="red">MOVIE SERVER</font></b></p></a></div>
						<div class="Arrow"><a href="http://bcnbd.net/"target="_blank"><p><b><font size="3" color="red">BCNMOVIE
</font></b></p></a></div>
						<br/><hr size=1>
						<div style="margin-top:9px">Torrent Server:</div>
						<div class="Arrow"><a href="https://www.chd4.com/index.php?page=login"target="_blank"><p><b><font size="3" color="red">CrazyHD</font></b></p></a></div>
						<div class="Arrow"><a href="https://1337x.to/home/"target="_blank"><p><b><font size="3" color="red">1337x.to</font></b></p></a></div>
						<div class="Arrow"><a href="https://yts.mx/"target="_blank"><p><b><font size="3" color="red">YTS.MX</font></b></p></a></div>
						<div class="Arrow"><a href="http://202.83.124.242:32400/web/index.html#"target="_blank"><p><b><font size="3" color="red">PLEX SERVER</font></b></p></a></div>
						<br/><hr size=1>
						<form action="/" method="get" style="padding:5px 0px 0px;margin:0px" name="simpleSearch"><input type="text" name="search" value="{.$search-data.}" onclick="this.value=''" style="width:100px"/> <input type="submit" value="Search"/></form>
						<div class="Arrow" style="margin-top:3px"><a href="javascript:initBox('specialBox','search');" class="Response">Advanced search</a></div>
					</div>
				</div>
				<div class="ModuleRow3">&nbsp;</div>
			</div>
[ServerTraffic]
			<span id="ProgressBox"></span>
			<div class="Module" id="ModuleBox" align="left">
				<div class="ModuleRow1">
					<span class="ModuleTitle">Server traffic</span>
					<a href="javascript:pinModule('ServerTraffic');" class="ModuleLink" id="ServerTraffic_Link"><div class="hid">&nbsp;</div></a>
				</div>
				<div class="ModuleRow2" id="ServerTraffic">
					<div class="ModuleText">
						Inbound:<br/>
						<div class="Arrow"><span class="Response">[%total-uploads%]</span> Files uploaded</div>
						<div class="Arrow">Total size: <span class="Response">[%total-in%]</span></div>
						<div class="Arrow">Incoming: <span class="Response">[%speed-in% KB/s]</span></div>
						<div class="Arrow">Connections: <span class="Response">[%connections%]</span></div>
						<br/><hr size=1>
						<div style="margin-top:9px">Outbound:</div>
						<div class="Arrow"><span class="Response">[%total-downloads%]</span> Files downloaded</div>
						<div class="Arrow">Total size: <span class="Response">[%total-out%]</span></div>
						<div class="Arrow">Outgoing: <span class="Response">[%speed-out% KB/s]</span></div>
						<div class="Arrow">Total hits: <span class="Response">[%total-hits%]</span></div>
					</div>
				</div>
				<div class="ModuleRow3">&nbsp;</div>
			</div>
[ServerStatistics]
				<div class="Module" id="ModuleBox" align="left">
				<div class="ModuleRow1">
					<span class="ModuleTitle">Server statistics</span>
					<a href="javascript:pinModule('ServerStatistics');" class="ModuleLink" id="ServerStatistics_Link"><div class="hid">&nbsp;</div></a>
				</div>
				<div class="ModuleRow2" id="ServerStatistics">
					<div class="ModuleText">
					Server time and date:<br/>
					<div class="Arrow">Time: <span class="Response">[%time%]</span></div>
					<div class="Arrow">Date: <span class="Response">[%date%]</span></div><br/>
					Server has been online for:<br/>
					<div class="Arrow"><span class="Response">[%uptime%]</span></div><br/>
					Your IP:<br/>
					<div class="Arrow"><span class="Response">[%ip%]</span></div>
					</div>
				</div>
				<div class="ModuleRow3">&nbsp;</div>
			</div>
[ShoutBox]
			<div class="Module" id="ModuleBox" align="left">
				<div class="ModuleRow1">
					<span class="ModuleTitle">Shoutbox</span>
					<a href="javascript:pinModule('ShoutBox');" class="ModuleLink" id="ShoutBox_Link"><div class="hid">&nbsp;</div></a>
					</div>
					<div class="ModuleRow2" id="ShoutBox">
					<iframe src="/template/shoutbox/display_posts/?sort=t&rev=1" height="240" width="196" frameborder="0"></iframe>
				</div>
				<div class="ModuleRow3">&nbsp;</div>
			</div>
[credits]
			<table width="100%" cellpadding="3" cellspacing="1" border="0" class="forumline" align="center" style="margin-top:10px">
			<tr>
				<td align="right" class="copyright" height="28">
					<a href="rofiqulislam.business.site" target="_blank">Rofiqul Islam v{.!build.}</a>, +8801677700375 <a href="http://www.rianetworkbd.com/" target="_blank">রিয়া নেটওয়ার্ক </a><br/>
					<a href="https://rianetworkbd.blogspot.com/" target="_blank">MoviE DawonloD ZonE - v%version% (Build #%build%)</a>, &copy; 2017-2021 <a href="https://rajabarimovie.blogspot.com/" target="_blank">100/3, RAJABARI</a><br/>
				</td>
			</tr>
			</table>
[stats.html|no log]
<div class="ModuleText">
	Inbound:<br/>
	<div class="Arrow"><span class="Response">[%total-uploads%]</span> Files uploaded</div>
	<div class="Arrow">Total size: <span class="Response">[%total-in%]</span></div>
	<div class="Arrow">Incoming: <span class="Response">[%speed-in% KB/s]</span></div>
	<div class="Arrow">Connections: <span class="Response">[%connections%]</span></div>
	<br/><hr size=1>
	<div style="margin-top:9px">Outbound:</div>
	<div class="Arrow"><span class="Response">[%total-downloads%]</span> Files downloaded</div>
	<div class="Arrow">Total size: <span class="Response">[%total-out%]</span></div>
	<div class="Arrow">Outgoing: <span class="Response">[%speed-out% KB/s]</span></div>
	<div class="Arrow">Total hits: <span class="Response">[%total-hits%]</span></div>
</div>
[nofiles]
	<table width="100%" cellpadding="2" cellspacing="1" border="0" class="forumline" id="FileListTable">
		<tr>
			<td class="catLeft" height="28" width="100%" style="border-right:0px" colspan="3">
				<span class="ModuleTitle cattitle">
					Directory :: {.breadcrumbs|{:<a href="%bread-url%"> {.or|%bread-name%|Home.}<img src="/template/images/arrow.gif" alt="/" style="border:0"></a>:}.}
					{.if|{.$search-data.}|<a href="">Search Results<img src="/template/images/arrow.gif" alt="/" style="border:0"></a>.}
				</span>
				<a href="javascript:pinModule('ModuleTable');" class="ModuleLink" id="ModuleTable_Link" style="margin-right:2px" title="Hide the module list"><div class="hid">&nbsp;</div></a>
			</td>
		</tr>
		<tr><td class="nav1" colspan="3">&nbsp;</td>%folder-comment%</tr>
		<tr>
			<td class="row1" align="center" valign="middle" width="64"><img src="/template/icons/nofile.gif" class="noIcon" alt=""/></td>
			<td width="100%"><div class="forumlink fileLink">
				<i id="message">{.if|{.$search-data.}|Your search for&nbsp;<i>{.$search-data.}</i>&nbsp;returned no results!|There are no files in this folder...}</i></div>
				<span class="genmed" style="width:85%">
					<div class="commentStyle1"><div></div></div>
					<div class="commentStyle2" id="message2">{.if|{.$search-data.}|Please try again with a different query.|If you have upload rights, start filling the folder!.}</div>
				</span>
				<div class="minHeight"></div>
				{.if|{.$search-data.}||<div class="gensmall fileStats"><span style="width:125px;float:left"><b>File Type:</b> <i>None</i></span></div>.}
			</td>
			<td nowrap="nowrap" class="qrow">
				<div class="quicklinks">
					<div class=q1><div class="emp">&nbsp;</div></div>
					<div class=q2><div class="emp">&nbsp;</div></div>
				</div>
			</td>
		</tr>
		<tr><td class="v2" height="18" colspan="3"></td></tr>
</table>
[search-data]
{.?search.}{.cut|2|-1|{.?filter.}{.if not|{.?files-filter=\ .}|{.?files-filter.}.}{.if not|{.?folders-filter=\ .}|{.?folders-filter.}.}.}
[files]
<table width="100%" cellpadding="2" cellspacing="1" border="0" class="forumline" id="FileListTable">
<tr>
	<td class="catLeft" height="28" width="100%" style="border-right:0px" colspan="3">
		<span class="ModuleTitle cattitle">
			Directory :: {.breadcrumbs|{:<a href="%bread-url%"> {.or|%bread-name%|Home.}<img src="/template/images/arrow.gif" alt="/" style="border:0"></a>:}.}
			{.if|{.$search-data.}|<a href="">Search Results<img src="/template/images/arrow.gif" alt="/" style="border:0"></a>.}
		</span>
		<a href="javascript:pinModule('ModuleTable');" class="ModuleLink" id="ModuleTable_Link" style="margin-right:2px" title="Hide the module list"><div class="hid">&nbsp;</div></a>
	</td>
</tr>
<tr><td class="nav1" colspan="3">&nbsp;</td></tr>
%folder-comment%
%list%
<tr><td class="v2" height="18" colspan="3"></td></tr>
</table>
[file.aiff = file.bat = file.css = file.doc = file.exe = file.file = file.gif = file.gzip = file.ini = file.m3u = file.mov = file.mpeg = file.mpg = file.ogg = file.pdf = file.ppt = file.rar = file.sit = file.sitx = file.tar = file.tgz = file.wav = file.xls = file.zip]
<tr>
	<td class="row1" align="center" valign="middle" width="64">
		<a href="%item-url%" class="messageimagelink"><img src="/template/icons/{.if|{.%item-ext%=mpg.}|mpeg|{.if|{.%item-ext%=divx.}|avi|%item-ext%|%item-ext%.}.}.gif" class="noIcon" alt=""/></a>
	</td>
	<td width="100%" class="{.if not|{.get|can access.}|P.} {.inc|rows|1.}{.if|{.mod|{.^rows.}|2.}|altRow1|altRow2.}">
		<div class="forumlink fileLink">
			<a href="%item-url%">%item-name%</a>{.if|{.get|is new.}|<span style="font-size:7pt;font-weight:normal"> - <span class="Response"><b>NEW</b></span></span>.}
		</div>
		<span class="genmed" style="width:85%">%comment%</span>
		<div class="minHeight">
		</div>
		<div class="gensmall fileStats">
			<span style="width:125px;float:left"><b>File Size:</b> %item-size%</span>
			<span style="width:65px;float:left"><b>Hits:</b> %item-dl-count%</span>
			<span style="width:200px;float:left"><b>Date:</b> %item-modified%</span>
		</div>
	</td>
	<td nowrap="nowrap" class="qrow {.if|{.mod|{.^rows.}|2.}|altRow1|altRow2.}">
		<div class="quicklinks">
			<div class=q1><a href="%item-url%" title="Download this file"><div class="{.if not|{.get|can access.}|dow|dow-a.}">&nbsp;</div></a></div>
			<div class=q2><div class="emp">&nbsp;</div></div>
		</div>
	</td>
</tr>
[file.txt = file.html = file.htm]
<tr> 
	<td class="row1" align="center" valign="middle" width="64">
		<a href="%item-url%" class="messageimagelink"><img src="/template/icons/{.if|{.%item-ext%=htm.}|html|%item-ext%.}.gif" class="noIcon" alt=""/></a>
	</td>
	<td width="100%" class="{.if not|{.get|can access.}|P.} {.inc|rows|1.}{.if|{.mod|{.^rows.}|2.}|altRow1|altRow2.}">
		<div class="forumlink fileLink">
			<a href="%item-url%">%item-name%</a>{.if|{.get|is new.}|<span style="font-size:7pt;font-weight:normal"> - <span class="Response"><b>NEW</b></span></span>.}
		</div>
		<span class="genmed" style="width:85%">%comment%</span>
		<div class="minHeight"></div>
		<div class="gensmall fileStats">
			<span style="width:125px;float:left"><b>File Size:</b> %item-size%</span>
			<span style="width:65px;float:left"><b>Hits:</b> %item-dl-count%</span>
			<span style="width:200px;float:left"><b>Date:</b> %item-modified%</span>
		</div>
	</td>
	<td nowrap="nowrap" class="qrow {.if|{.mod|{.^rows.}|2.}|altRow1|altRow2.}">
		<div class="quicklinks">
			<div class=q1><a href="%item-url%" title="Open this file"><div class="{.if not|{.get|can access.}|bro|bro-a.}">&nbsp;</div></a></div>
			<div class=q2><div class="emp">&nbsp;</div></div>
		</div>
	</td>
</tr>
[file.mp4 = file.m4a = file.aac = file.mov = file.3gp = file.mp3 = file.flv = file.swf = file.avi = file.divx = file.wma = file.wmv = file.mkv]
<tr>
	{.if|{.filesize|/template/icons/%item-ext%.gif.}
	|	
	<td class="row1" align="center" valign="middle" width="64">
		<a href="%encoded-folder%%item-url%" class="messageimagelink"><img src="/template/icons/%item-ext%.gif" class="noIcon" alt=""/></a>
	</td>
	|		
	<td class="background" height="64">
		<a href="%item-url%" class="messageimagelink">
			<div class="noIcon">
				<div style="background:url('/~img_file') no-repeat center bottom;width:64px;height:50px">
					<div style="color:#dedede;font:bold 9px verdana;padding-top:5px;padding-left:15px">%item-ext%</div>
				</div>
			</div>
		</a>
	</td>
	.}
	<td width="100%" class="{.if not|{.get|can access.}|P.} {.inc|rows|1.}{.if|{.mod|{.^rows.}|2.}|altRow1|altRow2.}">
		<div class="forumlink fileLink">
			<a href="%folder%%item-url%">%item-name%</a>{.if|{.get|is new.}|<span style="font-size:7pt;font-weight:normal"> - <span class="Response"><b>NEW</b></span></span>.}
		</div>
		<span class="genmed" style="width:85%">%comment%</span>
		<div class="minHeight"></div>
		<div class="gensmall fileStats">
			<span style="width:125px;float:left"><b>File Size:</b> %item-size%</span>
			<span style="width:65px;float:left"><b>Hits:</b> %item-dl-count%</span>
			<span style="width:200px;float:left"><b>Date:</b> %item-modified%</span>
		</div>
	</td>
	<td nowrap="nowrap" class="qrow {.if|{.mod|{.^rows.}|2.}|altRow1|altRow2.}">
		<div class="quicklinks">
			<div class=q1><a href="%item-url%" title="Download this file."><div class="{.if not|{.get|can access.}|dow|dow-a.}">&nbsp;</div></a></div>
			<div class=q2 {.switch|%item-ext%|,|mp3,flv,mp3,flv,mp4,m4a,mov,3gp,aac|name="mediaFile"|.}><a href="javascript:void(0);" onClick="initBox('Box-'+(%sequential%+1),this.name);" name="%item-full-url%" title="Open this file in a preview box"><div class="fla">&nbsp;</div></a><span id="Box-%sequential%"></span></div>
		</div>
	</td>
</tr>
[file.bmp = file.jpg = file.png]
<tr>
	<td class="row1" align="center" valign="middle" width="64">
		<a href="%item-url%" class="messageimagelink"><img {.if|{.filesize|%folder-resource%\previews_and_thumbnails\thumb-%item-name%.jpg.}|src="previews_and_thumbnails/thumb-%item-name%.jpg"|src="/template/icons/%item-ext%.gif".} class="noIcon" alt=""/></a>
	</td>
	<td width="100%" class="{.if not|{.get|can access.}|P.} {.inc|rows|1.}{.if|{.mod|{.^rows.}|2.}|altRow1|altRow2.}">
		<div class="forumlink fileLink">
			<a href="%item-url%">%item-name%</a>
		</div>
		<span class="genmed" style="width:85%">%comment%</span>
		<div class="minHeight"></div>
		<div class="gensmall fileStats">
			<span style="width:125px;float:left"><b>File Size:</b> %item-size%</span>
			<span style="width:65px;float:left"><b>Hits:</b> %item-dl-count%</span>
			<span style="width:200px;float:left"><b>Date:</b> %item-modified%</span>
		</div>
	</td>
	<td nowrap="nowrap" class="qrow {.if|{.mod|{.^rows.}|2.}|altRow1|altRow2.}">
		<div class="quicklinks">
			<div class=q1><a href="%item-url%" title="View this image in a new page" target="_blank"><div class="{.if not|{.get|can access.}|dow|dow-a.}">&nbsp;</div></a></div>
			{.if|{.filesize|%folder-resource%\previews_and_thumbnails\prev-%item-name%.jpg.}|
			<div class=q2><a href="javascript:void(0);" onClick="initBox('Box-'+(%sequential% + 1),this.name);" name="%item-name%" title="Preview this image"><div class="mag">&nbsp;</div></a></div>
			|<div class=q2><div class="mag" style="filter:alpha(opacity=25);opacity:0.25">&nbsp;</div></div>.}<span id="Box-%sequential%"></span></div>
		</div>
	</td>
</tr>
[file]
<tr>
	<td class="background" height="64">
		<a href="%item-url%" class="messageimagelink">
			<div class="noIcon">
				<div style="background:url('/~img_file') no-repeat center bottom;width:64px;height:50px">
					<div style="color:#dedede;font:bold 9px verdana;padding-top:5px;padding-left:15px">%item-ext%</div>
				</div>
			</div>
		</a>
	</td>
	<td width="100%" class="{.if not|{.get|can access.}|P.} {.inc|rows|1.}{.if|{.mod|{.^rows.}|2.}|altRow1|altRow2.}">
		<div class="forumlink fileLink">
			<a href="%item-url%">%item-name%</a>{.if|{.get|is new.}|<span style="font-size:7pt;font-weight:normal"> - <span class="Response"><b>NEW</b></span></span>.}
		</div>
		<span class="genmed" style="width:85%">%comment%</span>
		<div class="minHeight"></div>
		<div class="gensmall fileStats">
			<span style="width:125px;float:left"><b>File Size:</b> %item-size%</span>
			<span style="width:65px;float:left"><b>Hits:</b> %item-dl-count%</span>
			<span style="width:200px;float:left"><b>Date:</b> %item-modified%</span>
		</div>
	</td>
	<td nowrap="nowrap" class="qrow {.if|{.mod|{.^rows.}|2.}|altRow1|altRow2.}">
		<div class="quicklinks">
			<div class=q1><a href="%item-url%" title="Download this file"><div class="{.if not|{.get|can access.}|dow|dow-a.}">&nbsp;</div></a></div>
			<div class=q2><div class="emp">&nbsp;</div></div>
		</div>
	</td>
</tr>
[folder]
<tr>
	<td class="row1" align="center" valign="middle" width="64">
		<a href="%item-url%" class="messageimagelink"><img src="/template/icons/folder.gif" class="noIcon" alt=""/></a>
	</td>
	<td width="100%" class="{.if not|{.get|can access.}|P.} {.inc|rows|1.}{.if|{.mod|{.^rows.}|2.}|altRow1|altRow2.}">
		<div class="forumlink fileLink">
			<a href="%item-url%">%item-name%</a>{.if|{.get|is new.}|<span style="font-size:7pt;font-weight:normal"> - <span class="Response"><b>NEW</b></span></span>.}
		</div>
		<span class="genmed" style="width:85%">%comment%</span>
		<div class="minHeight"></div>
		<div class="gensmall fileStats">
			<span style="width:190px;float:left"><b>File Type:</b> <i>Folder</i></span>
			<span style="width:200px;float:left"><b>Date:</b> %item-modified%</span>
		</div>
	</td>
	<td nowrap="nowrap" class="qrow {.if|{.mod|{.^rows.}|2.}|altRow1|altRow2.}">
	<div class="quicklinks">
		<div class=q1 title="Browse this folder">
			<a href="%item-url%"><div class="{.if not|{.get|can access.}|bro|bro-a.}"></div></a>
		</div>
		<div class=q2>			
			{.if|{.get|can archive.}|
			<div class="dow-a" title="Archive download enabled">
			<a href="%item-url%~folder.tar{.if|{.get|can recur.}|?recursive.}">
				<div style="width:28px;height:28px">&nbsp;</div>
			</a>
			</div>
			|
			<div class="dow" title="Archive download disabled">
				<div style="width:28px;height:28px">&nbsp;</div>
			</div>
			.}
		</div>
	</div>
</td>
</tr>
[link]
<tr>
	<td class="row1" align="center" valign="middle" width="64">
		<a href="%item-url%" class="messageimagelink"><img src="/template/icons/html.gif" class="noIcon" alt=""/></a>
	</td>
	<td width="100%" class="{.if not|{.get|can access.}|P.} {.inc|rows|1.}{.if|{.mod|{.^rows.}|2.}|altRow1|altRow2.}">
		<div class="forumlink fileLink">
			<a href="%item-url%">%item-name%</a>{.if|{.get|is new.}|<span style="font-size:7pt;font-weight:normal"> - <span class="Response"><b>NEW</b></span></span>.}
		</div>
		<span class="genmed" style="width:85%">%comment%</span>
		<div class="minHeight"></div>
		<div class="gensmall fileStats">
			<span style="width:190px;float:left"><b>File Type:</b> <i>Link</i></span>
			<span style="width:200px;float:left"><b>Date:</b> %item-modified%</span>
		</div>
	</td>
	<td nowrap="nowrap" class="qrow {.if|{.mod|{.^rows.}|2.}|altRow1|altRow2.}">
		<div class="quicklinks">
			<div class=q1><a href="%item-url%" title="Open this link"><div class="{.if not|{.get|can access.}|dbro|bro-a.}">&nbsp;</div></a></div>
			<div class=q2><div class="emp">&nbsp;</div></div>
		</div>
	</td>
</tr>
[comment]
<div class="commentStyle1"><div></div></div><div class="commentStyle2">%item-comment%</div>
[folder-comment]
<tr id="FolderComment">
	<td width="100%" colspan="3" style="padding:10px 10px 13px 0px"><div class="gensmall fileStats"><i>Folder comment:</i></div>
	<div style="margin-left:50px" class="MessageText">%item-comment%</div>
</tr>
[error-page]
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
{.$copyright.}
<head>
	<title id="title">Error!</title>
	<link rel="shortcut icon" href="/favicon.ico"/>
	<meta http-equiv="content-type" content="text/html; charset=UTF-8"/>
	<meta http-equiv="Content-Style-Type" content="text/css"/>
	<link rel="stylesheet" type="text/css" href="/template/code/terayon_main.css"/>
	<script type="text/javascript" src="/template/code/terayon_main.js"></script>
	<script type="text/javascript" src="/template/code/terayon_previewbox.js"></script>
</head>
<body>
<table width="85%" class="bodyline" style="margin:auto" cellpadding="10" cellspacing="0">
<tr>
	<td>
{.$header.}
{.$controls.}
	<table width="100%" cellpadding="0" cellspacing="0" border="0">
	<tr>
		<td valign="top" width="100%" style="padding-top:10px">
%content%
		</td>
		<td valign="top" nowrap="nowrap" id="ModuleTable" align="right" style="padding-left:10px">
{.$ServerTraffic.}
{.$ServerStatistics.}
		</td>
	</tr>
	</table>
{.$credits.}
	</td>
</tr>
</table>
<script type="text/javascript">pageLoad();</script>
</body>
</html>
[not found]
			<table class="forumline" width="100%" cellspacing="1" cellpadding="4" border="0">
			<tr>
				<td class="catLeft" height="28">
					<span class="ModuleTitle cattitle">Error :: <a href="../">Home</a> <img alt="" src="/template/images/arrow.gif"/> Not found! <img alt="" src="/template/images/arrow.gif"/></span>
					<a href="javascript:pinModule('ModuleTable');" class="ModuleLink" id="ModuleTable_Link" style="margin-right:2px" title="Hide the module list"><div class="hid">&nbsp;</div></a>
				</td>
			</tr>
			<tr>
				<td class="nav1">
					<span class="nav_top">&nbsp;</span>
				</td>
			</tr>
			<tr>
				<td class="row4" height="208" valign="top">
					<div class="ErrorHeader">
						<div class="q1"><div class="not">&nbsp;</div></div><div class="q3"> <i>Not found!</i></div></div><span class="ErrorCode">Error code: [404]</span><br/><br/>
						<div class="ErrorText" style="line-height: normal">The requested page could not be found or it is no longer available.
						<br/><br/>
						Please re-check the address or try again at a later time.
						<br/><br/><br/>
						<img src="/~img14" height="15" alt=""/><a href="../" class="MessageText"> Back to previous page..</a>
					</div>
				</td>
			</tr>
			<tr>
				<td class="v2" height="18"></td>
			</tr>
			</table>
[overload]
			<table class="forumline" width="100%" cellspacing="1" cellpadding="4" border="0">
			<tr>
				<td class="catLeft" height="28">
					<span class="ModuleTitle cattitle">Error :: <a href="../">Home</a> <img alt="" src="/template/images/arrow.gif"/> Server too busy! <img alt="" src="/template/images/arrow.gif"/></span>
					<a href="javascript:pinModule('ModuleTable');" class="ModuleLink" id="ModuleTable_Link" style="margin-right:2px" title="Hide the module list"><div class="hid">&nbsp;</div></a>
				</td>
			</tr>
			<tr>
			<td class="nav1">
					<span class="nav_top">&nbsp;</span>
			</td>
			</tr>
			<tr>
				<td class="row4" height="208" valign="top">
					<div class="ErrorHeader">
						<div class="q1"><div class="den">&nbsp;</div></div><div class="q3"> <i>Server too busy!</i></div></div><span class="ErrorCode">Error code: [503]</span><br/><br/>
						<div class="ErrorText" style="line-height: normal">The server is handling too many requests at the moment.
						<br/><br/>
						Please try again in a few moments.
						<br/><br/><br/>
						<img src="/~img14" height="15" alt=""/><a href="../" class="MessageText"> Back to previous page..</a>
					</div>
				</td>
			</tr>
			<tr>
				<td class="v2" height="18"></td>
			</tr>
			</table>
[max contemp downloads]
			<table class="forumline" width="100%" cellspacing="1" cellpadding="4" border="0">
			<tr>
				<td class="catLeft" height="28">
					<span class="ModuleTitle cattitle">Error :: <a href="../">Home</a> <img alt="" src="/template/images/arrow.gif"/> Server too busy! <img alt="" src="/template/images/arrow.gif"/></span>
					<a href="javascript:pinModule('ModuleTable');" class="ModuleLink" id="ModuleTable_Link" style="margin-right:2px" title="Hide the module list"><div class="hid">&nbsp;</div></a>
				</td>
			</tr>
			<tr>
				<td class="nav1">
					<span class="nav_top">&nbsp;</span>
				</td>
			</tr>
			<tr>
				<td class="row4" height="208" valign="top">
					<div class="ErrorHeader">
						<div class="q1"><div class="den">&nbsp;</div></div><div class="q3"> <i>Server too busy!</i></div></div><span class="ErrorCode">Error code: [503]</span><br/><br/>
						<div class="ErrorText" style="line-height: normal">The server has a download limit enabled; this limit has been reached.
						<br/><br/>
						Please try again in a few moments.
						<br/><br/><br/>
						<img src="/~img14" height="15" alt=""/><a href="../" class="MessageText"> Back to previous page..</a>
					</div>
				</td>
			</tr>
			<tr>
				<td class="v2" height="18"></td>
			</tr>
			</table>
[unauthorized]
			<table class="forumline" width="100%" cellspacing="1" cellpadding="4" border="0">
			<tr>
				<td class="catLeft" height="28">
					<span class="ModuleTitle cattitle">Error :: <a href="../">Home</a> <img alt="" src="/template/images/arrow.gif"/> Unauthorized! <img alt="" src="/template/images/arrow.gif"/></span>
					<a href="javascript:pinModule('ModuleTable');" class="ModuleLink" id="ModuleTable_Link" style="margin-right:2px" title="Hide the module list"><div class="hid">&nbsp;</div></a>
				</td>
			</tr>
			<tr>
				<td class="nav1">
					<span class="nav_top">&nbsp;</span>
				</td>
			</tr>
			<tr>
				<td class="row4" height="208" valign="top">
					<div class="ErrorHeader">
						<div class="q1"><div class="una">&nbsp;</div></div><div class="q3"> <i>Unauthorized!</i></div></div><span class="ErrorCode">Error code: [401]</span><br/><br/>
						<div class="ErrorText" style="line-height: normal">You are not allowed to access the requested page.
						<br/><br/>
						 Please try again after logging in.
						<br/><br/><br/>
						<img src="/~img14" height="15" alt=""/><a href="../" class="MessageText"> Back to previous page..</a>
					</div>
				</td>
			</tr>
			<tr>
				<td class="v2" height="18"></td>
			</tr>
			</table>
[deny]
			<table class="forumline" width="100%" cellspacing="1" cellpadding="4" border="0">
			<tr>
				<td class="catLeft" height="28">
					<span class="ModuleTitle cattitle">Error :: <a href="../">Home</a> <img alt="" src="/template/images/arrow.gif"/> Access denied! <img alt="" src="/template/images/arrow.gif"/></span>
					<a href="javascript:pinModule('ModuleTable');" class="ModuleLink" id="ModuleTable_Link" style="margin-right:2px" title="Hide the module list"><div class="hid">&nbsp;</div></a>
				</td>
			</tr>
			<tr>
				<td class="nav1">
					<span class="nav_top">&nbsp;</span>
				</td>
			</tr>
			<tr>
				<td class="row4" height="208" valign="top">
					<div class="ErrorHeader">
						<div class="q1"><div class="den">&nbsp;</div></div><div class="q3"> <i>Access denied!</i></div></div><span class="ErrorCode">Error code: [403]</span><br/><br/>
						<div class="ErrorText" style="line-height: normal">You do not have permission to access the requested page or file.
						<br/><br/><br/>
						<img src="/~img14" height="15" alt=""/><a href="../" class="MessageText"> Back to previous page..</a>
					</div>
				</td>
			</tr>
			<tr>
				<td class="v2" height="18"></td>
			</tr>
			</table>
[ban]
			<table class="forumline" width="100%" cellspacing="1" cellpadding="4" border="0">
			<tr>
				<td class="catLeft" height="28">
					<span class="ModuleTitle cattitle">Error :: <a href="../">Home</a> <img alt="" src="/template/images/arrow.gif"/> Banned!</span>
					<a href="javascript:pinModule('ModuleTable');" class="ModuleLink" id="ModuleTable_Link" style="margin-right:2px" title="Hide the module list"><div class="hid">&nbsp;</div></a>
				</td>
			</tr>
			<tr>
				<td class="nav1">
					<span class="nav_top">&nbsp;</span>
				</td>
			</tr>
			<tr>
			<td class="row4" height="208" valign="top">
				<div class="ErrorHeader">
					<div class="q1"><div class="una">&nbsp;</div></div><div class="q3"> <i>You have been banned!!!1! lolz</i></div></div><span class="ErrorCode">Error code: [403]</span><br/><br/>
					<div class="ErrorText" style="line-height: normal">You are not allowed to access this page or file, because your account (or IP) has been banned.
					<br/><br/>
					%reason%
					<br/><br/><br/>
					<img src="/~img14" height="15" alt=""/><a href="../" class="MessageText"> Back to previous page..</a>
				</div>
			</td>
			</tr>
			<tr>
				<td class="v2" height="18"></td>
			</tr>
			</table>
[upload]
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
{.$copyright.}
<head>
	<title id="title">Upload a file</title>
	<link rel="shortcut icon" href="/favicon.ico"/>
	<meta http-equiv="content-type" content="text/html; charset=UTF-8"/>
	<meta http-equiv="Content-Style-Type" content="text/css"/>
	<link rel="stylesheet" type="text/css" href="/template/code/terayon_main.css"/>
	<script type="text/javascript" src="/template/code/terayon_main.js"></script>
	<script type="text/javascript" src="/template/code/terayon_previewbox.js"></script>
</head>
<body>
<table width="85%" class="bodyline" style="margin:auto" cellpadding="10" cellspacing="0">
<tr>
	<td>
{.$header.}
{.$controls.}
	<table width="100%" cellpadding="0" cellspacing="0" border="0">
	<tr>
		<td valign="top" width="100%" style="padding-top:10px">
			<table width="100%" cellpadding="2" cellspacing="1" border="0" class="forumline" id="FileListTable">
			<tr>
				<td class="catLeft" height="28" width="100%" style="border-right:0px">
					<span class="cattitle">Directory :: {.breadcrumbs|{:<a href="%bread-url%"> {.or|%bread-name%|Home.}<img src="/template/images/arrow.gif" alt="/" style="border:0"></a>:}.}</span>
				</td>
			</tr>
			<tr>
				<td class="nav1">&nbsp;</td>
			</tr>
			<tr height="200">
				<td width="100%" style="padding:15px 50px">
					<span class="MessageHeader"><i>Upload a file</i></span><br/><br/>
					<span class="MessageText">To upload a file, simply click 'browse' next to an input field and select the file you want to upload. If all the files you want to upload are selected, hit the 'submit' button.<br/><br/>If you require more upload fields, simply click the 'more' button.</span><br/><br/>
					<form name=frm action="." target=_parent method=post enctype="multipart/form-data" onSubmit="frm.upbtn.disabled=true;frm.cancelbtn.disabled=false;return true">
						<div style="height:25px"><input name=fileupload1 size=75 type=file></div>
						<div style="height:25px"><input name=fileupload2 size=75 type=file></div>
						<div style="height:25px"><input name=fileupload3 size=75 type=file></div><span id="more"></span><br/>
						<div style="margin-left:10px;float:left"><input name=upbtn type=submit value="Submit" onclick="boxOpenCache=boxOpen;boxOpen=null;initBox('ProgressBox', 'Progress', boxOpenCache);"></div><div style="margin-left:10px;float:left"><input name=morebtn onclick="if(k <= 20) gEBI('more').innerHTML+='<div style=\'height:25px\'><input name=fileupload'+ k +' size=75 type=file></div>',k==20?this.disabled=true:k++" type=button value="More"></div><div style="margin-left:10px;float:left"><input name=cancelbtn type=button onclick=window.location="." enabled=false value="Cancel upload"></div>
					</form>
				</td>
			</tr>
			<tr><td class="v2"><span class="cattitle" align="right">&nbsp;</span></td></tr>
			</table>
		</td>
		<td valign="top" nowrap="nowrap" id="ModuleTable" style="padding-left:10px">
{.$ServerTraffic.}
{.$ServerStatistics.}
		</td>
	</tr>
	</table>
{.$credits.}
	</td>
</tr>
</table>
<script type="text/javascript">var k=4; document.frm.cancelbtn.disabled=true; pageLoad();</script>
</body>
</html>
[upload-results]
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
{.$copyright.}
<head>
	<title id="title">Upload results</title>
	<link rel="shortcut icon" href="/favicon.ico"/>
	<meta http-equiv="content-type" content="text/html; charset=UTF-8"/>
	<meta http-equiv="Content-Style-Type" content="text/css"/>
	<link rel="stylesheet" type="text/css" href="/template/code/terayon_main.css"/>
	<script type="text/javascript" src="/template/code/terayon_main.js"></script>
	<script type="text/javascript" src="/template/code/terayon_previewbox.js"></script>
</head>
<body>
<table width="85%" class="bodyline" style="margin:auto" cellpadding="10" cellspacing="0">
<tr>
	<td>
{.$header.}
{.$controls.}
		<table width="100%" cellpadding="0" cellspacing="0" border="0">
		<tr>
			<td valign="top" width="100%" style="padding-top:10px">
				<table width="100%" cellpadding="2" cellspacing="1" border="0" class="forumline" id="FileListTable">
				<tr>
					<td class="catLeft" height="28" width="100%" style="border-right: 0px" colspan="3">
						<span class="cattitle">Directory :: {.breadcrumbs|{:<a href="%bread-url%"> {.or|%bread-name%|Home.}<img src="/template/images/arrow.gif" alt="/" style="border:0"></a>:}.}</span>
					</td>
				</tr>
				<tr><td class="nav1" colspan="3">&nbsp;</td></tr>
				%uploaded-files%
				<tr><td class="v2" colspan="3"><span class="cattitle" align="right">&nbsp;</span></td></tr>
				</table>
			</td>
			<td valign="top" nowrap="nowrap" id="ModuleTable" style="padding-left:10px">
{.$ServerTraffic.}
{.$ServerStatistics.}
			</td>
		</tr>
	</table>
{.$credits.}
	</td>
</tr>
</table>
<script type="text/javascript">pageLoad();</script>
</body>
</html>
[upload-success]
<tr>
	<td class="row1" align="center" valign="middle" width="64"><img src="/template/icons/file.gif" class="noIcon" alt=""/></td>
	<td width="100%">
		<div class="forumlink fileLink">%item-name%</div>
		<span class="genmed" style="width:85%"><div class="commentStyle1"><div></div></div><div class="commentStyle2">File has been uploaded succesfully</div></span>
		<div class="minHeight"></div>
			<div class="gensmall fileStats">
			<span style="width:175px;float:left"><b>Upload status:</b> <i style="color:#77FF77">Succesfull</i></span>
			<span style="width:150px;float:left"><b>File Size:</b> %item-size%</span>
			<span style="width:175px;float:left"><b>Avarage speed:</b> %speed% KB/s</span>
		</div>
	</td>
	<td nowrap="nowrap" class="qrow">
		<div class="quicklinks">
			<div class=q1><div class="emp">&nbsp;</div></div>
			<div class=q2><div class="emp">&nbsp;</div></div>
		</div>
	</td>
</tr>
[upload-failed]
<tr>
	<td class="row1" align="center" valign="middle" width="64"><img src="/template/icons/file.gif" class="noIcon" alt=""/></td>
	<td width="100%">
		<div class="forumlink fileLink">%item-name%</div>
		<span class="genmed" style="width:85%"><div class="commentStyle1"><div></div></div><div class="commentStyle2">File has failed to upload<br/>Reason: %reason%</div></span>
		<div class="minHeight"></div>
		<div class="gensmall fileStats">
			<span style="width:175px;float:left"><b>Upload status:</b> <i style="color:#FF7777">Failed</i></span>
			<span style="width:150px;float:left"><b>File Size:</b> %item-size%</span>
			<span style="width:175px;float:left"><b>Avarage speed:</b> %speed% KB/s</span>
		</div>
	</td>
	<td nowrap="nowrap" class="qrow">
		<div class="quicklinks">
			<div class=q1><div class="emp">&nbsp;</div></div>
			<div class=q2><div class="emp">&nbsp;</div></div>
		</div>
	</td>
</tr>
[progress]
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
{.$copyright.}
<head>
	<title id="title">Transfers</title>
	<link rel="shortcut icon" href="/favicon.ico"/>
	<meta http-equiv="Refresh" content="3; URL=/~progress">
	<meta http-equiv="content-type" content="text/html; charset=UTF-8"/>
	<meta http-equiv="Content-Style-Type" content="text/css"/>
	<link rel="stylesheet" type="text/css" href="/template/code/terayon_main.css"/>
</head>
<body>
<table width="85%" class="bodyline" style="margin:auto" cellpadding="10" cellspacing="0">
<tr>
	<td>
		<table width="100%" cellpadding="0" cellspacing="0" border="0">
		<tr>
			<td valign="top" width="100%">
				<table width="100%" cellpadding="2" cellspacing="1" border="0" class="forumline" id="FileListTable">
				<tr>
					<td class="catLeft" height="28" width="100%" style="border-right:0px">
						<span class="cattitle"><center style="font-size:14px;font-weight:bold;">Transfers</center></span>
					</td>
				</tr>
				<tr><td class="nav1"><center style="color:#FFF;font-size:10px;">Auto-Refresh: 3 secs</center></td></tr>
				<tr><td><center style="background:url('/~img_graph500x50xxA5A9AFx004480') left top no-repeat;height:50px;">&nbsp;</center></td></tr>
				<tr><td class="nav1">&nbsp;</td></tr>
				<tr height="200">
					<td width="100%" style="padding:15px 50px;font-size:12px;">
						<center>%progress-files%</center>
					</td>
				</tr>
				<tr><td class="v2"><span class="cattitle" align="right">&nbsp;</span></td></tr>
				</table>
			</td>
		</tr>
	</table>
	</td>
</tr>
</table>
</body>
</html>
[progress-nofiles]
<b>No Transfers</b>
[progress-upload-file]
<div class="p"><b><u>Upstream:</u><br/>%filename%</b><br/>%done-bytes% / %total-bytes% bytes<br/>Current upload speed:<br/>%speed-kb% KB/s<br/>Percentage complete: %perc%%<br/><div class="pOut"><div class="pIn" style="width:%perc%%"></div></div></div>
[progress-download-file]
<div class="p"><b><u>Downstream:</u><br/>%filename%</b><br/>%done-bytes% / %total-bytes% bytes<br/>Current download speed:<br/>%speed-kb% KB/s<br/>Percentage complete: %perc%%<br/><div class="pOut"><div class="pIn" style="width:%perc%%"></div></div></div>
