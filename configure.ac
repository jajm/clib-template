AC_PREREQ([2.67])
LT_PREREQ([2.2])

AC_INIT([clib-template], [0.0.1], [mail@example.com])
LT_INIT()

AC_SUBST(LIBTOOL_CURRENT, 0)
AC_SUBST(LIBTOOL_REVISION, 0)
AC_SUBST(LIBTOOL_AGE, 0)

AC_PROG_CC
AC_CHECK_HEADERS([stdlib.h stdio.h string.h])

AC_CONFIG_FILES([
	Makefile
	src/Makefile
	include/Makefile
	t/Makefile
	config.mk
	clib-template.pc
])

AC_OUTPUT
