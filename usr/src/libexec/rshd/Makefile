#	@(#)Makefile	5.6 (Berkeley) 9/27/90

PROG=	rshd
NONSTDINC=$(INCOLDBSD)
SRCS=	rshd.c
MAN8=	rshd.0
DPADD=	${LIBUTIL}
LDADD=	-lutil
.PATH: ${.CURDIR}/../../usr.bin/rlogin

.include <bsd.prog.mk>
