#Simple makefile for libusb application

CC=gcc
INC=/usr/include/libusb-1.0/
OBJ=USB70xx_GPIO.o

USB70xx_GPIO: $(OBJ)
	$(CC) $(OBJ) -lusb-1.0 -o USB70xx_GPIO

USB70xx_GPIO.o: USB70xx_GPIO.c
	$(CC) -c USB70xx_GPIO.c -I$(INC)

clean :
	-rm *.o $(objects) *.exe USB70xx_GPIO
