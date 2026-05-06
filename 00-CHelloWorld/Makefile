#objetivo: requisitos
#(<TAB>acciones)*
all: hello

Hola: hello.c
	gcc hello.c -o Hola

run: Hola
	Hola > output.txt


clean:
	del /f /q Hola.exe output.txt 2>nul || exit 0
