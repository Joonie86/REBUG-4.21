clean:
	rm -f *.elf *.bin *.cex *.dex *.cexr *.dexr *.bak stage2/*.elf stage2/*.o stage2/*.map *.map lv2/src/*.o lv1/src/*.o debug/src/*.o

all:
	make -f stage2/Makefile clean
	make -f stage2/Makefile_st2Cr
	rm -f *.bin *.elf stage2/*.o stage2/*.map lv2/src/*.o lv1/src/*.o debug/src/*.o
	make -f stage2/Makefile_st2Cd
	rm -f *.bin *.elf stage2/*.o stage2/*.map lv2/src/*.o lv1/src/*.o debug/src/*.o
	make -f stage2/Makefile_st2Dr
	rm -f *.bin *.elf stage2/*.o stage2/*.map lv2/src/*.o lv1/src/*.o debug/src/*.o
	make -f stage2/Makefile_st2Dd
	rm -f *.bin *.elf stage2/*.o stage2/*.map lv2/src/*.o lv1/src/*.o debug/src/*.o
