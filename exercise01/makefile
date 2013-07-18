all: boot

boot:
	nasm boot.asm -o boot.bin
	dd if=boot.bin of=boot.img bs=512 count=1

clean:
	rm -rf boot.img boot.bin

