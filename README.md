# show local path of ios simulator in Xcode
	po NSHomeDirectory()

# the way opening each text editors in terminal<br/>sublime text, visual studio
	ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/sb
	ln -s "/Applications/Visual Studio Code.app/Contents/MacOS/Electron" /usr/local/bin/vb
	usage > $ vb text.file

# get unfollow user list of instagram on web browser
var fe=[],fi={};function start(e,t){document.getElementsByClassName("g47SY")[t].click(),setTimeout(function(){var t=document.getElementsByClassName("isgrP")[0].scrollHeight,n=0,o=setInterval(function(){if(n>=t)return clearInterval(o),void e();n+=100,document.getElementsByClassName("isgrP")[0].scrollTop=n},200)},1e3)}function fef(){document.querySelectorAll(".enpQJ").forEach(function(e){fe.push(e.getElementsByClassName("FPmhX")[0].textContent)}),document.getElementsByClassName("glyphsSpriteX__outline__24__grey_9 u-__7")[0].click(),setTimeout(function(){start(fif,2)},500)}function fif(){document.querySelectorAll(".enpQJ").forEach(function(e){fi[e.getElementsByClassName("FPmhX")[0].textContent]=e.getElementsByClassName("wFPL8")[0].textContent}),document.getElementsByClassName("glyphsSpriteX__outline__24__grey_9 u-__7")[0].click();var e="",t=0;Object.keys(fi).forEach(function(n){-1===fe.indexOf(n)&&(t++,e+="[ID:"+n+"] [NAME:"+fi[n]+"] \n",console.log("[ID:"+n+"] [NAME:"+fi[n]+"]"))}),d("================================================================\nfollower "+fe.length+" following "+Object.keys(fi).length+" unfollower "+t+"\n================================================================\n\n"+e,"unfollowers.txt","text")}function d(e,t,n){var o=new Blob([e],{type:n});if(window.navigator.msSaveOrOpenBlob)window.navigator.msSaveOrOpenBlob(o,t);else{var l=document.createElement("a"),i=URL.createObjectURL(o);l.href=i,l.download=t,document.body.appendChild(l),l.click(),setTimeout(function(){document.body.removeChild(l),window.URL.revokeObjectURL(i)},0)}}start(fef,1);
