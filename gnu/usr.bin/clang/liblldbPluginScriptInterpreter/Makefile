# $OpenBSD: Makefile,v 1.2 2020/08/03 14:45:30 patrick Exp $

LIB=	lldbPluginScriptInterpreter
NOPIC=
NOPROFILE=

.include <bsd.own.mk>
SRCS=	ScriptInterpreterNone.cpp

.PATH:	${.CURDIR}/../../../llvm/lldb/source/Plugins/ScriptInterpreter/None

install:
	@# Nothing here so far ...

.include <bsd.lib.mk>

CPPFLAGS+=	${LLDB_INCLUDES}
CPPFLAGS+=	${CLANG_INCLUDES}
