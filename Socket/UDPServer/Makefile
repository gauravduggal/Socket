PROGRAMS = main
#CC = /home/gaurav/Desktop/Cyclone5/dizzy/poky/build/tmp/sysroots/x86_64-linux/usr/bin/arm-poky-linux-gnueabi/arm-poky-linux-gnueabi-gcc
CC = gcc
all:	
	#export DEBUG_COM=1
	$(CC) -I ../include *.c -o server -Wall
	#scp main root@192.168.1.6:~/cooled_pipe
#-march=armv5te -marm -mthumb-interwork 


clean:
	@rm -f $(PROGRAMS) *~ *.o core
        
