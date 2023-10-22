#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.71])
AC_INIT([soap_calc], [1.0.0], [lee88823@naver.com])
AM_INIT_AUTOMAKE
AC_CONFIG_SRCDIR([calc.h])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC

# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([arpa/inet.h fcntl.h inttypes.h netdb.h netinet/in.h stdint.h strings.h sys/ioctl.h sys/socket.h sys/time.h sys/timeb.h unistd.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_HEADER_STDBOOL
AC_C_INLINE
AC_TYPE_SIZE_T
AC_CHECK_TYPES([ptrdiff_t])

# Checks for library functions.
AC_FUNC_MALLOC
AC_FUNC_MKTIME
AC_FUNC_STRERROR_R
AC_FUNC_STRTOD
AC_CHECK_FUNCS([ftime gethostbyname gettimeofday localtime_r memset pow select socket strchr strerror strstr])

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
