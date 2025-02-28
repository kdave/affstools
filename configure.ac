AC_PREREQ([2.72])
AC_INIT([affstools], [0.1b])
AM_INIT_AUTOMAKE
AC_CONFIG_SRCDIR([buffer.c])
AC_CONFIG_HEADERS([config.h])

dnl Checks for programs.
AC_PROG_CC
AC_PROG_AWK
AC_PROG_INSTALL
AC_PROG_LN_S

dnl Checks for libraries.

dnl Checks for header files.
AC_CHECK_HEADERS([argp.h byteswap.h fcntl.h unistd.h])
AC_CHECK_HEADERS([fcntl.h stdint.h sys/ioctl.h unistd.h])

dnl Checks for typedefs, structures, and compiler characteristics.
AC_C_INLINE
AC_TYPE_OFF_T

dnl Checks for library functions.
AC_FUNC_STRFTIME
AC_FUNC_VPRINTF
AC_FUNC_MALLOC
AC_CHECK_FUNCS([strerror])
AC_CHECK_FUNCS([memset strerror])

AC_C_BIGENDIAN
AC_CHECK_SIZEOF([unsigned char])
AC_CHECK_SIZEOF([signed char])
AC_CHECK_SIZEOF([unsigned short])
AC_CHECK_SIZEOF([signed short])
AC_CHECK_SIZEOF([unsigned int])
AC_CHECK_SIZEOF([signed int])
AC_CHECK_SIZEOF([unsigned long])
AC_CHECK_SIZEOF([signed long])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
