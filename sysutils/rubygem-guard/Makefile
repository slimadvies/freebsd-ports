PORTNAME=	guard
PORTVERSION=	2.19.1
CATEGORIES=	sysutils rubygems
MASTER_SITES=	RG

MAINTAINER=	sunpoet@FreeBSD.org
COMMENT=	Command line tool to easily handle events on file system modifications
WWW=		https://github.com/guard/guard

LICENSE=	MIT
LICENSE_FILE=	${WRKSRC}/LICENSE

RUN_DEPENDS=	rubygem-formatador>=0.2.4:devel/rubygem-formatador \
		rubygem-listen>=2.7<4.0:devel/rubygem-listen \
		rubygem-logger>=1.6<2:devel/rubygem-logger \
		rubygem-lumberjack>=1.0.12<2.0:devel/rubygem-lumberjack \
		rubygem-nenv>=0.1<1:devel/rubygem-nenv \
		rubygem-notiffany>=0<1:devel/rubygem-notiffany \
		rubygem-ostruct>=0.6<1:devel/rubygem-ostruct \
		rubygem-pry>=0.13.0:devel/rubygem-pry \
		rubygem-shellany>=0<1:sysutils/rubygem-shellany \
		rubygem-thor>=0.18.1:devel/rubygem-thor

USES=		gem

NO_ARCH=	yes

PLIST_FILES=	bin/_guard-core bin/guard

.include <bsd.port.mk>
