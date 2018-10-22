#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([FULL-PACKAGE-NAME], [VERSION], [BUG-REPORT-ADDRESS])
AC_CONFIG_AUX_DIR([build-aux])

# Checks for programs.
AC_PROG_INSTALL
AC_PROG_MKDIR_P
AC_PROG_SED
AC_PATH_PROG([GIT], [git], [AC_MSG_ERROR(git required)])
AC_PATH_PROG([BASENAME], [basename], [AC_MSG_ERROR(basename required)])
AC_PATH_PROG([DIRNAME], [dirname], [AC_MSG_ERROR(dirname required)])
AC_SUBST(INSTALL)
AC_SUBST(MKDIR_P)
AC_SUBST(SED)
AC_SUBST(GIT)
AC_SUBST(BASENAME)
AC_SUBST(DIRNAME)

# Checks for libraries.

# Checks for header files.

# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_OUTPUT([Makefile])
