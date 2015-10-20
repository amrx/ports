# $FreeBSD$

PORTNAME=            cackey
PORTVERSION=         0.7.5
CATEGORIES=          devel
MASTER_SITES=        https://software.forge.mil/sf/projects/community_cac
RESTRICTED=	     yes

MAINTAINER=     spam@amrx.net
COMMENT=        Common Access Card Driver

GNU_CONFIGURE=  yes
CONFIGURE_ENV=  LDFLAGS="-L /usr/local/lib"
CONFIGURE_ARGS= --with-pcsc-headers=/usr/local/include/PCSC --with-pcsc-libs=-lpcsclite

.include <bsd.port.mk>
