## Process this file with automake to produce Makefile.in 
# echo -e "\n***  Compiling iRRAM with MPFR multiple precision package as backend ***\n"

AM_CPPFLAGS=-I$(top_srcdir)/include @INCLUDES@

## DEFS = @DEFS@

srcdir = @srcdir@
VPATH = ../../src                                                           
     
##$(top_srcdir)/sourcefile.list defines $(main_sources)
include $(top_srcdir)/sourcefile.list

extra_sources = MPFR_ext.c mpfr_extension.cc  


lib_LTLIBRARIES          = libiRRAM.la
libiRRAM_la_LDFLAGS = -version-info @iRRAM_shared_version@
libiRRAM_la_SOURCES = $(main_sources) $(extra_sources)

distclean:	
	rm -f *.o @iRRAM_src@ Makefile
