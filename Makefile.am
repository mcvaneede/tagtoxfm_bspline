AUTOMAKE_OPTIONS = check-news
ACLOCAL_AMFLAGS = -I m4

bin_PROGRAMS = tagtoxfm_bspline

EXTRA_DIST = $(m4_files) tagtoxfm_bspline.h TBSpline.h


m4_files = m4/mni_REQUIRE_LIB.m4 m4/mni_REQUIRE_MNILIBS.m4	 \
    m4/mni_REQUIRE_OPENINVENTOR.m4  \
    m4/mni_cxx_have_koenig_lookup.m4 m4/smr_CGAL_MAKEFILE.m4 \
	m4/smr_OPTIONAL_LIB.m4 m4/smr_REQUIRED_LIB.m4		 \
	m4/smr_WITH_BUILD_PATH.m4

tagtoxfm_bspline_SOURCES = tagtoxfm_bspline.cc TBSpline.cc
