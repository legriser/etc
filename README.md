# show local path of ios simulator in Xcode
	po NSHomeDirectory()

# the way opening each text editors in terminal<br/>sublime text, visual studio
	ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/sb
	ln -s "/Applications/Visual Studio Code.app/Contents/MacOS/Electron" /usr/local/bin/vb
	usage > $ vb text.file

# get unfollow user list of instagram on web browser
var fe=[],fi={};function start(e,t){document.getElementsByClassName("g47SY")[t].click(),setTimeout(function(){var t=document.getElementsByClassName("isgrP")[0].scrollHeight,n=0,o=setInterval(function(){if(n>=t)return clearInterval(o),void e();n+=100,document.getElementsByClassName("isgrP")[0].scrollTop=n},200)},1e3)}function fef(){document.querySelectorAll(".enpQJ").forEach(function(e){fe.push(e.getElementsByClassName("FPmhX")[0].textContent)}),document.getElementsByClassName("glyphsSpriteX__outline__24__grey_9 u-__7")[0].click(),setTimeout(function(){start(fif,2)},500)}function fif(){document.querySelectorAll(".enpQJ").forEach(function(e){fi[e.getElementsByClassName("FPmhX")[0].textContent]=e.getElementsByClassName("wFPL8")[0].textContent}),document.getElementsByClassName("glyphsSpriteX__outline__24__grey_9 u-__7")[0].click();var e="";Object.keys(fi).forEach(function(t){-1===fe.indexOf(t)&&(e+="[ID:"+t+"] [NAME:"+fi[t]+"] \n",console.log("[ID:"+t+"] [NAME:"+fi[t]+"]"))}),d(e,"unfollowers.txt","text")}function d(e,t,n){var o=new Blob([e],{type:n});if(window.navigator.msSaveOrOpenBlob)window.navigator.msSaveOrOpenBlob(o,t);else{var l=document.createElement("a"),s=URL.createObjectURL(o);l.href=s,l.download=t,document.body.appendChild(l),l.click(),setTimeout(function(){document.body.removeChild(l),window.URL.revokeObjectURL(s)},0)}}start(fef,1);
