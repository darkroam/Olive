all: boot

boot:
	nasm boot.asm -o boot.bin
	dd if=boot.bin of=boot.img bs=512 count=1

pmtest1:
	nasm pmtest1.asm -o pmtest1.bin
	dd if=pmtest1.bin of=pmtest1.img bs=512 count=1

clean:
	rm -rf boot.img boot.bin
	rm -rf pmtest1.img pmtest1.bin

