CC	=	gcc
CCOPTS	=	-g
PTHREAD	=	-pthread

TARGETS	=	tcpclient			

all	:	$(TARGETS) 		
    
tcpclient	:	tcpclient.c
	$(CC)	$(PTHREAD) $(CCOPTS) $^	-o	$@	
	
clean	:	
	rm	-f	$(TARGETS)	*.o 
    