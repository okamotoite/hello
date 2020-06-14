SHELL=	/bin/sh
PROG=	hello
CFLAGS=	-DHELLO

all:	${PROG}

${PROG}:	${PROG}.o
	${CC} ${CFLAGS} -o ${PROG} ${PROG}.o 

clean:
	-rm -f *.o ${PROG}
