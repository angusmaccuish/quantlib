 
swap_out_CPPFLAGS = -I${top_srcdir}
swap_out_LDADD = ../../qlo/libQuantLibAddin.la ../../Addins/Cpp/libQuantLibAddinCpp.la
swap_out_LDFLAGS = -lObjectHandler -lQuantLib -lboost_filesystem -lboost_serialization -lboost_system -lboost_regex

EXTRA_DIST = \
    ClientCppSwapOut_vc8.vcproj \
    ClientCppSwapOut_vc9.vcproj \
    ClientCppSwapOut_vc10.vcxproj \
    ClientCppSwapOut_vc11.vcxproj \
    ClientCppSwapOut_vc12.vcxproj

swap_out_SOURCES = swap_out.cpp

if BUILD_CPP
noinst_PROGRAMS = swap_out
else
EXTRA_PROGRAMS = swap_out
endif

