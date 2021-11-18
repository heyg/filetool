# filetool
c; on windows or linux ; merge file、split file、md5sum file and so on
#
compile,

gcc -o filetool filetool.c md5.c
#
usage,

./filetool  merge|split|md5 file
	./filetool  remove
