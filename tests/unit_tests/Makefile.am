noinst_PROGRAMS += unit_tests

unit_tests_sources = %D%/unit_tests.cxx
unit_tests_SOURCES = $(unit_tests_sources)

unit_tests_LDADD = $(liblog4cplus_la_file)

if BUILD_WITH_WCHAR_T_SUPPORT
noinst_PROGRAMS += unit_testsU
unit_testsU_CPPFLAGS = $(AM_CPPFLAGS) -DUNICODE=1
unit_testsU_SOURCES = $(unit_tests_sources)
unit_testsU_LDADD = $(liblog4cplusU_la_file)
endif
