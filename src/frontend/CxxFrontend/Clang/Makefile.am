include $(top_srcdir)/config/Makefile.for.ROSE.includes.and.libs

INCLUDES = $(ROSE_INCLUDES)

if ROSE_USE_CLANG_FRONTEND

noinst_LTLIBRARIES = libroseClangFrontend.la

libroseClangFrontend_la_DEPENDENCIES =
libroseClangFrontend_la_SOURCES      = ClangFrontend.C
libroseClangFrontend_la_LDFLAGS      = $(CLANG_LDFLAGS)
libroseClangFrontend_la_CXXFLAGS     = $(CLANG_CXXFLAGS)

dist_include_HEADERS = ClangFrontend.h ClangFrontend-private.h

include_HEADERS =

endif

EXTRA_DIST = \
  clang-builtin-c.h \
  clang-builtin-cpp.hpp \
  clang-builtin-cuda.hpp \
  clang-builtin-opencl.h

