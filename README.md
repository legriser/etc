# showing local path of ios simulator in Xcode
	po NSHomeDirectory()

# the way opening each text editors simply in terminal [Sublime Text, Visual Studio]
	ln -s "/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl" /usr/local/bin/sb
	ln -s "/Applications/Visual Studio Code.app/Contents/MacOS/Electron" /usr/local/bin/vb
	usage > $ vb text.file
