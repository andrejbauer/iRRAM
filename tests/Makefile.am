AM_CPPFLAGS= -I$(top_srcdir)/include @INCLUDES@ -std=c++11

DEFS = @DEFS@

LDADD=../obj/MPFR/libiRRAM.la @LDADD@

check_PROGRAMS = t_DYADIC t_INTEGER t_RATIONAL t_double_conv t_size t_string_conv t_FUNCTION

TESTS = $(check_PROGRAMS)

t_DYADIC_SOURCES = t_DYADIC.cc
t_FUNCTION_SOURCES = t_FUNCTION.cc
t_INTEGER_SOURCES = t_INTEGER.cc
t_RATIONAL_SOURCES = t_RATIONAL.cc
t_double_conv_SOURCES = t_double_conv.cc
t_size_SOURCES = t_size.cc
t_string_conv_SOURCES = t_string_conv.cc
