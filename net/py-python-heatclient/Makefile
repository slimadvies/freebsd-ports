PORTNAME=	python-heatclient
PORTVERSION=	4.1.0
CATEGORIES=	net python
MASTER_SITES=	PYPI
PKGNAMEPREFIX=	${PYTHON_PKGNAMEPREFIX}

MAINTAINER=	sunpoet@FreeBSD.org
COMMENT=	OpenStack Orchestration API Client Library
WWW=		https://docs.openstack.org/python-heatclient/latest/ \
		https://github.com/openstack/python-heatclient

LICENSE=	APACHE20
LICENSE_FILE=	${WRKSRC}/LICENSE

BUILD_DEPENDS=	${PYTHON_PKGNAMEPREFIX}pbr>=2.0.0:devel/py-pbr@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}setuptools>=0:devel/py-setuptools@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}wheel>=0:devel/py-wheel@${PY_FLAVOR}
RUN_DEPENDS=	${PYTHON_PKGNAMEPREFIX}cliff>=2.8.0:devel/py-cliff@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}iso8601>=0.1.11:devel/py-iso8601@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}keystoneauth1>=3.8.0:devel/py-keystoneauth1@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}osc-lib>=1.14.0:devel/py-osc-lib@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}oslo.i18n>=3.15.3:devel/py-oslo.i18n@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}oslo.serialization>=1.18.0:devel/py-oslo.serialization@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}oslo.utils>=3.33.0:devel/py-oslo.utils@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}pbr>=2.0.0:devel/py-pbr@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}prettytable>=0.7.2:devel/py-prettytable@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}python-swiftclient>=3.2.0:databases/py-python-swiftclient@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}pyyaml>=3.13:devel/py-pyyaml@${PY_FLAVOR} \
		${PYTHON_PKGNAMEPREFIX}requests>=2.14.2:www/py-requests@${PY_FLAVOR}

USES=		python:3.9+
USE_PYTHON=	autoplist concurrent pep517

NO_ARCH=	yes

.include <bsd.port.mk>
