Command untuk mengcompile file main-c dan main-e:

FILE main-c
gcc -o main-c ahuff.c main-c.c errhand.c bitio.c

FILE main-e
gcc -o main-e ahuff.o main-e.c errhand.c bitio.c

Cara menggunakan .exe file:

KOMPRESI
main-c <nama file yang akan dikompresi> <nama file hasil kompresi>

DEKOMPRESI
main-e <nama file yang akan di dekompresi> <nama file hasil dekompresi>
