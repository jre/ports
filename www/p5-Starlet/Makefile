# $OpenBSD: Makefile,v 1.5 2018/09/07 20:47:49 bluhm Exp $

COMMENT=	simple, high-performance PSGI/Plack HTTP server

MODULES=	cpan
PKG_ARCH=	*
DISTNAME=	Starlet-0.31
CATEGORIES=	www

CPAN_AUTHOR=	KAZUHO

# Perl
PERMIT_PACKAGE_CDROM=	Yes

RUN_DEPENDS =		devel/p5-Parallel-Prefork>=0.17 \
			devel/p5-Try-Tiny \
			net/p5-Server-Starter>=0.06 \
			www/p5-Plack>=0.992
TEST_DEPENDS =		net/p5-Test-TCP>=2.1 \
			www/p5-HTTP-Message \
			www/p5-libwww>=5.8

.include <bsd.port.mk>
