ACLOCAL_AMFLAGS = -I m4

CPPFLAGS = -I$(top_srcdir)/test/gtest/googletest/include
ldadd = $(top_builddir)/test/libfollytestmain.la

libgtest_la_SOURCES = gtest/googletest/src/gtest-all.cc

check_PROGRAMS = \
	histogram_test

TESTS = $(check_PROGRAMS)

histogram_test_SOURCES = HistogramTest.cpp
histogram_test_LDADD = $(ldadd)
