# Makefile.in generated by automake 1.15 from Makefile.am.
# doc/info/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2014 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.



# $Id$ $Revision$


am__is_gnu_make = { \
  if test -z '$(MAKELEVEL)'; then \
    false; \
  elif test -n '$(MAKE_HOST)'; then \
    true; \
  elif test -n '$(MAKE_VERSION)' && test -n '$(CURDIR)'; then \
    true; \
  else \
    false; \
  fi; \
}
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/graphviz
pkgincludedir = $(includedir)/graphviz
pkglibdir = $(libdir)/graphviz
pkglibexecdir = $(libexecdir)/graphviz
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = x86_64-apple-darwin13.4.0
host_triplet = x86_64-apple-darwin13.4.0
subdir = doc/info
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/m4/libtool.m4 \
	$(top_srcdir)/m4/ltargz.m4 $(top_srcdir)/m4/ltdl.m4 \
	$(top_srcdir)/m4/ltoptions.m4 $(top_srcdir)/m4/ltsugar.m4 \
	$(top_srcdir)/m4/ltversion.m4 $(top_srcdir)/m4/lt~obsolete.m4 \
	$(top_srcdir)/./version.m4 $(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
DIST_COMMON = $(srcdir)/Makefile.am $(am__DIST_COMMON)
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
SOURCES =
DIST_SOURCES =
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
am__uninstall_files_from_dir = { \
  test -z "$$files" \
    || { test ! -d "$$dir" && test ! -f "$$dir" && test ! -r "$$dir"; } \
    || { echo " ( cd '$$dir' && rm -f" $$files ")"; \
         $(am__cd) "$$dir" && rm -f $$files; }; \
  }
am__installdirs = "$(DESTDIR)$(htmldir)"
DATA = $(html_DATA)
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
am__DIST_COMMON = $(srcdir)/Makefile.in
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /Users/erg/gviz/config/missing aclocal-1.15
AMTAR = $${TAR-tar}
AM_DEFAULT_VERBOSITY = 0
ANN_CFLAGS = -I/usr/local/include
ANN_LIBS = -L/usr/local/lib -lANN
AR = ar
AUTOCONF = ${SHELL} /Users/erg/gviz/config/missing autoconf
AUTOHEADER = ${SHELL} /Users/erg/gviz/config/missing autoheader
AUTOMAKE = ${SHELL} /Users/erg/gviz/config/missing automake-1.15
AWK = gawk
CC = gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -g -I/usr/local/include -Wall -Wextra -Wmissing-include-dirs -Wswitch-default -Wfloat-equal -Wundef -Wshadow -Wpointer-arith -Wbad-function-cast -Wcast-qual -Wconversion -Wstrict-prototypes -Wmissing-prototypes -Wnested-externs -fno-common -Wall
CPP = gcc -E
CPPFLAGS =  -I/Users/erg/include
CXX = g++
CXXCPP = g++ -E
CXXDEPMODE = depmode=gcc3
CXXFLAGS = -g -I/usr/local/include
CYGPATH_W = echo
CYGWIN = no
DARWIN = yes
DARWIN9 = no
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DEVIL_INCLUDES = 
DEVIL_LIBS = 
DLLTOOL = false
DSYMUTIL = dsymutil
DUMPBIN = 
ECHO_C = \c
ECHO_N = 
ECHO_T = 
EGREP = /usr/bin/grep -E
EXEEXT = 
EXPAT_CONFIG = 
EXPAT_INCLUDES = 
EXPAT_LIBS =  -lexpat
EXTRA_SMYRNA_LDFLAGS = 
FGREP = /usr/bin/grep -F
FONTCONFIG_CFLAGS = -I/opt/X11/include -I/opt/X11/include/freetype2
FONTCONFIG_CONFIG = 
FONTCONFIG_LIBS = -L/opt/X11/lib -lfontconfig -lfreetype
FREETYPE2_CFLAGS = -I/opt/X11/include/freetype2
FREETYPE2_LIBS = -L/opt/X11/lib -lfreetype
FREETYPE_CONFIG = 
GDIPLUS_CFLAGS = 
GDIPLUS_HEADS = 
GDIPLUS_LIBS = 
GDK_CFLAGS = -D_REENTRANT -I/opt/X11/include/cairo -I/opt/X11/include/pixman-1 -I/opt/X11/include -I/opt/X11/include/freetype2 -I/opt/X11/include/libpng16 -I/opt/X11/include -I/opt/X11/include/libpng16 -I/usr/local/Cellar/gtk+/2.24.28/include/gtk-2.0 -I/usr/local/Cellar/gtk+/2.24.28/lib/gtk-2.0/include -I/usr/local/Cellar/pango/1.36.8/include/pango-1.0 -I/usr/local/Cellar/gdk-pixbuf/2.30.8/include/gdk-pixbuf-2.0 -I/usr/local/Cellar/glib/2.44.1/include/glib-2.0 -I/usr/local/Cellar/glib/2.44.1/lib/glib-2.0/include -I/usr/local/opt/gettext/include
GDK_LIBS = -L/opt/X11/lib -L/usr/local/Cellar/gtk+/2.24.28/lib -L/usr/local/Cellar/pango/1.36.8/lib -L/usr/local/Cellar/gdk-pixbuf/2.30.8/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/opt/gettext/lib -lgdk-x11-2.0 -lpangocairo-1.0 -lpango-1.0 -lcairo -lgdk_pixbuf-2.0 -lgobject-2.0 -lglib-2.0 -lintl
GDK_PIXBUF_CFLAGS = -D_REENTRANT -I/opt/X11/include/libpng16 -I/usr/local/Cellar/gdk-pixbuf/2.30.8/include/gdk-pixbuf-2.0 -I/usr/local/Cellar/glib/2.44.1/include/glib-2.0 -I/usr/local/Cellar/glib/2.44.1/lib/glib-2.0/include -I/usr/local/opt/gettext/include
GDK_PIXBUF_LIBS = -L/usr/local/Cellar/gdk-pixbuf/2.30.8/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/opt/gettext/lib -lgdk_pixbuf-2.0 -lgobject-2.0 -lglib-2.0 -lintl
GDLIB_CFLAGS = 
GDLIB_CONFIG = 
GDLIB_LIBS =  -lgd 
GLADE_CFLAGS = -D_REENTRANT -I/opt/X11/include/cairo -I/opt/X11/include/pixman-1 -I/opt/X11/include/libpng16 -I/opt/X11/include -I/opt/X11/include/libpng16 -I/opt/X11/include -I/opt/X11/include/freetype2 -I/usr/local/Cellar/libglade/2.6.4/include/libglade-2.0 -I/usr/local/Cellar/gtk+/2.24.28/include/gtk-2.0 -I/usr/local/Cellar/gtk+/2.24.28/lib/gtk-2.0/include -I/usr/local/Cellar/pango/1.36.8/include/pango-1.0 -I/usr/local/Cellar/atk/2.16.0/include/atk-1.0 -I/usr/local/Cellar/gdk-pixbuf/2.30.8/include/gdk-pixbuf-2.0 -I/usr/local/Cellar/pango/1.36.8/include/pango-1.0 -I/usr/local/Cellar/harfbuzz/0.9.40/include/harfbuzz -I/usr/local/Cellar/pango/1.36.8/include/pango-1.0 -I/usr/local/Cellar/glib/2.44.1/include/glib-2.0 -I/usr/local/Cellar/glib/2.44.1/lib/glib-2.0/include -I/usr/local/opt/gettext/include -I/usr/include/libxml2
GLADE_LIBS = -L/opt/X11/lib -L/usr/local/Cellar/libglade/2.6.4/lib -L/usr/local/Cellar/gtk+/2.24.28/lib -L/usr/local/Cellar/pango/1.36.8/lib -L/usr/local/Cellar/atk/2.16.0/lib -L/usr/local/Cellar/gdk-pixbuf/2.30.8/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/Cellar/pango/1.36.8/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/opt/gettext/lib -lglade-2.0 -lgtk-x11-2.0 -lgdk-x11-2.0 -lpangocairo-1.0 -latk-1.0 -lcairo -lgdk_pixbuf-2.0 -lgio-2.0 -lpangoft2-1.0 -lpango-1.0 -lgobject-2.0 -lglib-2.0 -lintl -lfontconfig -lfreetype -lxml2
GLITZ_CFLAGS = 
GLITZ_LIBS = 
GLUT_CFLAGS = 
GLUT_LIBS =  -lglut
GO = 
GO_INCLUDES = 
GO_LIBS = 
GRAPHVIZ_COLLECTION = development
GRAPHVIZ_SOURCES = graphviz/development/SOURCES
GRAPHVIZ_VERSION_BUILD = 0
GRAPHVIZ_VERSION_COMMIT = cc33ac0
GRAPHVIZ_VERSION_DATE = 20161126.1803
GRAPHVIZ_VERSION_MAJOR = 2
GRAPHVIZ_VERSION_MICRO = 20161126.1803
GRAPHVIZ_VERSION_MINOR = 39
GRAPHVIZ_VERSION_REVISION = 0
GREP = /usr/bin/grep
GROFF = groff
GS_CFLAGS = 
GS_LIBS = -lgs
GTKGLEXT_CFLAGS = -D_REENTRANT -I/opt/X11/include/cairo -I/opt/X11/include/pixman-1 -I/opt/X11/include/libpng16 -I/opt/X11/include -I/opt/X11/include/libpng16 -I/opt/X11/include -I/opt/X11/include/freetype2 -I/usr/local/Cellar/gtkglext/1.2.0/include/gtkglext-1.0 -I/usr/local/Cellar/gtkglext/1.2.0/lib/gtkglext-1.0/include -I/usr/local/Cellar/gtk+/2.24.28/include/gtk-2.0 -I/usr/local/Cellar/gtk+/2.24.28/lib/gtk-2.0/include -I/usr/local/Cellar/pangox-compat/0.0.2/include/pango-1.0 -I/usr/local/Cellar/gtk+/2.24.28/include/gtk-2.0 -I/usr/local/Cellar/gtk+/2.24.28/lib/gtk-2.0/include -I/usr/local/Cellar/pango/1.36.8/include/pango-1.0 -I/usr/local/Cellar/atk/2.16.0/include/atk-1.0 -I/usr/local/Cellar/gdk-pixbuf/2.30.8/include/gdk-pixbuf-2.0 -I/usr/local/Cellar/pango/1.36.8/include/pango-1.0 -I/usr/local/Cellar/harfbuzz/0.9.40/include/harfbuzz -I/usr/local/Cellar/pango/1.36.8/include/pango-1.0 -I/usr/local/Cellar/glib/2.44.1/include/glib-2.0 -I/usr/local/Cellar/glib/2.44.1/lib/glib-2.0/include -I/usr/local/opt/gettext/include
GTKGLEXT_LIBS = -L/opt/X11/lib -L/usr/local/Cellar/gtkglext/1.2.0/lib -L/usr/local/Cellar/gtk+/2.24.28/lib -L/usr/local/Cellar/pangox-compat/0.0.2/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/Cellar/gtk+/2.24.28/lib -L/usr/local/Cellar/pango/1.36.8/lib -L/usr/local/Cellar/atk/2.16.0/lib -L/usr/local/Cellar/gdk-pixbuf/2.30.8/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/Cellar/pango/1.36.8/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/opt/gettext/lib -lgtkglext-x11-1.0 -lgdkglext-x11-1.0 -lGLU -lGL -lXmu -lXt -lSM -lICE -lgdk-x11-2.0 -lpangox-1.0 -lX11 -lgmodule-2.0 -lgtk-x11-2.0 -lgdk-x11-2.0 -lpangocairo-1.0 -latk-1.0 -lcairo -lgdk_pixbuf-2.0 -lgio-2.0 -lpangoft2-1.0 -lpango-1.0 -lgobject-2.0 -lglib-2.0 -lintl -lfontconfig -lfreetype
GTKGL_CFLAGS = 
GTKGL_LIBS = 
GTK_CFLAGS = -D_REENTRANT -I/opt/X11/include/cairo -I/opt/X11/include/pixman-1 -I/opt/X11/include/libpng16 -I/opt/X11/include -I/opt/X11/include/libpng16 -I/opt/X11/include -I/opt/X11/include/freetype2 -I/usr/local/Cellar/gtk+/2.24.28/include/gtk-2.0 -I/usr/local/Cellar/gtk+/2.24.28/lib/gtk-2.0/include -I/usr/local/Cellar/pango/1.36.8/include/pango-1.0 -I/usr/local/Cellar/atk/2.16.0/include/atk-1.0 -I/usr/local/Cellar/gdk-pixbuf/2.30.8/include/gdk-pixbuf-2.0 -I/usr/local/Cellar/pango/1.36.8/include/pango-1.0 -I/usr/local/Cellar/harfbuzz/0.9.40/include/harfbuzz -I/usr/local/Cellar/pango/1.36.8/include/pango-1.0 -I/usr/local/Cellar/glib/2.44.1/include/glib-2.0 -I/usr/local/Cellar/glib/2.44.1/lib/glib-2.0/include -I/usr/local/opt/gettext/include
GTK_LIBS = -L/opt/X11/lib -L/usr/local/Cellar/gtk+/2.24.28/lib -L/usr/local/Cellar/pango/1.36.8/lib -L/usr/local/Cellar/atk/2.16.0/lib -L/usr/local/Cellar/gdk-pixbuf/2.30.8/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/Cellar/pango/1.36.8/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/opt/gettext/lib -lgtk-x11-2.0 -lgdk-x11-2.0 -lpangocairo-1.0 -latk-1.0 -lcairo -lgdk_pixbuf-2.0 -lgio-2.0 -lpangoft2-1.0 -lpango-1.0 -lgobject-2.0 -lglib-2.0 -lintl -lfontconfig -lfreetype
GTS_CFLAGS = -D_REENTRANT -I/usr/local/Cellar/gts/0.7.6/include -I/usr/local/Cellar/glib/2.44.1/include/glib-2.0 -I/usr/local/Cellar/glib/2.44.1/lib/glib-2.0/include -I/usr/local/opt/gettext/include
GTS_LIBS = -L/usr/local/Cellar/gts/0.7.6/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/opt/gettext/lib -lgts -lgthread-2.0 -lgmodule-2.0 -lglib-2.0 -lintl
GUILE = 
GUILE_CFLAGS = 
GUILE_INCLUDES = 
GUILE_LIBS = 
GVPLUGIN_CONFIG_FILE = config6
GVPLUGIN_VERSION = 6
GVPLUGIN_VERSION_INFO = 6:0:0
INCLTDL = 
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
INTGOSIZE = 32
IO = 
IO_INCLUDES = 
IO_LIBS = 
IPSEPCOLA_INCLUDES = -I$(top_srcdir)/lib/vpsc
IPSEPCOLA_LIBS = $(top_builddir)/lib/vpsc/libvpsc_C.la -lstdc++
JAVA = java
JAVA_INCLUDES =  -I/System/Library/Frameworks/JavaVM.framework/Headers
JAVA_LIBS = 
JNI_EXTRA_LDFLAGS = -shrext .jnilib
JSHEXT = jnilib
LASI_CFLAGS = -D_REENTRANT -I/opt/X11/include -I/opt/X11/include/freetype2 -I/usr/local/Cellar/lasi/1.1.2/include -I/usr/local/Cellar/pango/1.36.8/include/pango-1.0 -I/usr/local/Cellar/harfbuzz/0.9.40/include/harfbuzz -I/usr/local/Cellar/pango/1.36.8/include/pango-1.0 -I/usr/local/Cellar/glib/2.44.1/include/glib-2.0 -I/usr/local/Cellar/glib/2.44.1/lib/glib-2.0/include -I/usr/local/opt/gettext/include
LASI_LIBS = -L/opt/X11/lib -L/usr/local/Cellar/lasi/1.1.2/lib -L/usr/local/Cellar/pango/1.36.8/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/opt/gettext/lib -lLASi -lpangoft2-1.0 -lfontconfig -lpango-1.0 -lgobject-2.0 -lglib-2.0 -lintl -lfreetype
LD = /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/ld
LDFLAGS = -g -L/usr/local/lib -L/Users/erg/lib -Wl,-headerpad_max_install_names
LEX = flex
LEXLIB = -ll
LEX_OUTPUT_ROOT = lex.yy
LIBADD_DL =  
LIBADD_DLD_LINK = 
LIBADD_DLOPEN = 
LIBADD_SHL_LOAD = 
LIBGEN_LIBS = 
LIBLTDL = -lltdl
LIBLTDL_LDFLAGS = 
LIBOBJS = 
LIBPOSTFIX = 
LIBS = 
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIPO = lipo
LN_S = ln -s
LTDLDEPS = 
LTDLINCL = 
LTDLOPEN = libltdl
LTLIBOBJS = 
LT_ARGZ_H = lt__argz.h
LT_CONFIG_H = config.h
LT_DLLOADERS =  libltdl/dlopen.la
LT_DLPREOPEN = -dlpreopen libltdl/dlopen.la 
LT_SYS_LIBRARY_PATH = 
LUA = 
LUACONFIG = 
LUA_INCLUDES = 
LUA_INSTALL_DIR = 
LUA_LIBS = 
MAKEINFO = ${SHELL} /Users/erg/gviz/config/missing makeinfo
MANIFEST_TOOL = :
MATH_LIBS = -lm
MCS = 
MINGW32 = no
MING_CFLAGS = 
MING_LIBS = 
MKDIR_P = ../../config/install-sh -c -d
NM = /usr/bin/nm
NMEDIT = nmedit
OBJC = gcc
OBJCDEPMODE = depmode=gcc3
OBJCFLAGS = -g -O2
OBJDUMP = false
OBJEXT = o
OCAML = 
OCAML_INCLUDES = 
OCAML_LIBS = 
OCAML_OPT = 
OTOOL = otool
OTOOL64 = :
PACKAGE = graphviz
PACKAGE_BUGREPORT = http://www.graphviz.org/
PACKAGE_NAME = graphviz
PACKAGE_STRING = graphviz 2.39.20161126.1803
PACKAGE_TARNAME = graphviz
PACKAGE_URL = 
PACKAGE_VERSION = 2.39.20161126.1803
PANGOCAIRO_CFLAGS = -D_REENTRANT -I/opt/X11/include/cairo -I/opt/X11/include/pixman-1 -I/opt/X11/include -I/opt/X11/include/freetype2 -I/opt/X11/include/libpng16 -I/opt/X11/include -I/usr/local/Cellar/pango/1.36.8/include/pango-1.0 -I/usr/local/Cellar/glib/2.44.1/include/glib-2.0 -I/usr/local/Cellar/glib/2.44.1/lib/glib-2.0/include -I/usr/local/opt/gettext/include
PANGOCAIRO_LIBS = -L/opt/X11/lib -L/usr/local/Cellar/pango/1.36.8/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/opt/gettext/lib -lpangocairo-1.0 -lpango-1.0 -lgobject-2.0 -lglib-2.0 -lintl -lcairo
PANGOFT2_CFLAGS = -D_REENTRANT -I/opt/X11/include -I/opt/X11/include/freetype2 -I/usr/local/Cellar/pango/1.36.8/include/pango-1.0 -I/usr/local/Cellar/harfbuzz/0.9.40/include/harfbuzz -I/usr/local/Cellar/pango/1.36.8/include/pango-1.0 -I/usr/local/Cellar/glib/2.44.1/include/glib-2.0 -I/usr/local/Cellar/glib/2.44.1/lib/glib-2.0/include -I/usr/local/opt/gettext/include
PANGOFT2_LIBS = -L/opt/X11/lib -L/usr/local/Cellar/pango/1.36.8/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/opt/gettext/lib -lpangoft2-1.0 -lpango-1.0 -lgobject-2.0 -lglib-2.0 -lintl -lfontconfig -lfreetype
PATH_SEPARATOR = :
PERL = 
PERL_INCLUDES = 
PERL_INSTALL_DIR = 
PERL_LIBS = 
PHP = php
PHP_INCLUDES = -I/usr/include/php -I/usr/include/php/main -I/usr/include/php/TSRM -I/usr/include/php/Zend -I/usr/include/php/ext -I/usr/include/php/ext/date/lib
PHP_INSTALL_DATADIR = /usr/share/php
PHP_INSTALL_DIR = /usr/lib/php/modules
PHP_LIBS = 
PKGCONFIG = 
PKG_CONFIG = /usr/local/bin/pkg-config
PKG_CONFIG_LIBDIR = 
PKG_CONFIG_PATH = /Users/erg/lib/pkgconfig:/opt/X11/lib/pkgconfig:/usr/local/lib/pkgconfig
PLATFORMSDKINCLUDE = 
PLATFORMSDKINCLUDE_ESCAPED = 
PLATFORMSDKLIB = 
POPPLER_CFLAGS = 
POPPLER_LIBS = 
PS2PDF = ps2pdf
PYTHON = python
PYTHON23 = 
PYTHON23_INCLUDES = 
PYTHON23_INSTALL_DIR = 
PYTHON23_LIBS = 
PYTHON24 = 
PYTHON24_INCLUDES = 
PYTHON24_INSTALL_DIR = 
PYTHON24_LIBS = 
PYTHON25 = 
PYTHON25_INCLUDES = 
PYTHON25_INSTALL_DIR = 
PYTHON25_LIBS = 
PYTHON26 = 
PYTHON26_INCLUDES = 
PYTHON26_INSTALL_DIR = 
PYTHON26_LIBS = 
PYTHON27 = 
PYTHON27_INCLUDES = 
PYTHON27_INSTALL_DIR = 
PYTHON27_LIBS = 
PYTHON34 = 
PYTHON34_INCLUDES = 
PYTHON34_INSTALL_DIR = 
PYTHON34_LIBS = 
PYTHON_INCLUDES = -I/usr/local/Cellar/python/2.7.9/Frameworks/Python.framework/Versions/2.7/include/python2.7
PYTHON_INSTALL_DIR = /usr/local/Cellar/python/2.7.9/Frameworks/Python.framework/Versions/2.7/lib/python2.7/site-packages
PYTHON_LIBS = -undefined dynamic_lookup
QMAKE = qmake
QTCORE_CFLAGS = -DQT_SHARED -I/usr/local/Cellar/qt/4.8.6/include -I/usr/local/Cellar/qt/4.8.6/include/QtCore
QTCORE_LIBS = -F/usr/local/Cellar/qt/4.8.6/lib -framework QtCore
QTGUI_CFLAGS = -DQT_SHARED -I/usr/local/Cellar/qt/4.8.6/include -I/usr/local/Cellar/qt/4.8.6/include/QtGui -I/usr/local/Cellar/qt/4.8.6/include -I/usr/local/Cellar/qt/4.8.6/include/QtCore
QTGUI_LIBS = -F/usr/local/Cellar/qt/4.8.6/lib -framework QtGui -F/usr/local/Cellar/qt/4.8.6/lib -framework QtCore
QUARTZ_CFLAGS = 
QUARTZ_LIBS = -framework ApplicationServices
RANLIB = ranlib
RC = false
RSVG_CFLAGS = -D_REENTRANT -I/opt/X11/include/libpng16 -I/opt/X11/include/cairo -I/opt/X11/include/pixman-1 -I/opt/X11/include -I/opt/X11/include/freetype2 -I/opt/X11/include/libpng16 -I/opt/X11/include -I/usr/local/Cellar/librsvg/2.36.3_1/include/librsvg-2.0 -I/usr/local/Cellar/gdk-pixbuf/2.30.8/include/gdk-pixbuf-2.0 -I/usr/local/Cellar/glib/2.44.1/include/glib-2.0 -I/usr/local/Cellar/glib/2.44.1/lib/glib-2.0/include -I/usr/local/opt/gettext/include
RSVG_LIBS = -L/opt/X11/lib -L/usr/local/Cellar/librsvg/2.36.3_1/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/Cellar/gdk-pixbuf/2.30.8/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/opt/gettext/lib -lrsvg-2 -lm -lgio-2.0 -lgdk_pixbuf-2.0 -lgobject-2.0 -lglib-2.0 -lintl -lcairo
RUBY = 
RUBY_CFLAGS = -I/System/Library/Frameworks/Ruby.framework/Versions/2.0/usr/lib/ruby/2.0.0/universal-darwin13
RUBY_INSTALL_DIR = /System/Library/Frameworks/Ruby.framework/Versions/2.0/usr/lib/ruby/vendor_ruby/2.0.0/universal-darwin13
RUBY_LIBS = -L/System/Library/Frameworks/Ruby.framework/Versions/2.0/usr/lib -lruby.2.0.0
R_CFLAGS = 
R_LIBS = 
SED = /usr/bin/sed
SET_MAKE = 
SHARP_INCLUDES = 
SHARP_LIBS = 
SHELL = /bin/sh
SIZEOF_INT_BITS = 32
SOCKET_LIBS = 
SORT = sort
STRIP = strip
SVG_2_36_CFLAGS = -D_REENTRANT -I/opt/X11/include/libpng16 -I/opt/X11/include/cairo -I/opt/X11/include/pixman-1 -I/opt/X11/include -I/opt/X11/include/freetype2 -I/opt/X11/include/libpng16 -I/opt/X11/include -I/usr/local/Cellar/librsvg/2.36.3_1/include/librsvg-2.0 -I/usr/local/Cellar/gdk-pixbuf/2.30.8/include/gdk-pixbuf-2.0 -I/usr/local/Cellar/glib/2.44.1/include/glib-2.0 -I/usr/local/Cellar/glib/2.44.1/lib/glib-2.0/include -I/usr/local/opt/gettext/include
SVG_2_36_LIBS = -L/opt/X11/lib -L/usr/local/Cellar/librsvg/2.36.3_1/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/Cellar/gdk-pixbuf/2.30.8/lib -L/usr/local/Cellar/glib/2.44.1/lib -L/usr/local/opt/gettext/lib -lrsvg-2 -lm -lgio-2.0 -lgdk_pixbuf-2.0 -lgobject-2.0 -lglib-2.0 -lintl -lcairo
SWIG = swig
SWIGJAVA_CPPFLAGS = 
SWIG_PHP_OPT = -php5
TCLINT_INCLUDES = -I$(top_srcdir)/tclpkg/tclstubs
TCLSH = /usr/bin/tclsh8.5
TCL_CFLAGS =  -DUSE_TCL_STUBS
TCL_DEFS = -DPACKAGE_NAME=\"tcl\" -DPACKAGE_TARNAME=\"tcl\" -DPACKAGE_VERSION=\"8.5\" -DPACKAGE_STRING=\"tcl\ 8.5\" -DPACKAGE_BUGREPORT=\"\" -DSTDC_HEADERS=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_SYS_STAT_H=1 -DHAVE_STDLIB_H=1 -DHAVE_STRING_H=1 -DHAVE_MEMORY_H=1 -DHAVE_STRINGS_H=1 -DHAVE_INTTYPES_H=1 -DHAVE_STDINT_H=1 -DHAVE_UNISTD_H=1 -DNO_VALUES_H=1 -DHAVE_LIMITS_H=1 -DHAVE_SYS_PARAM_H=1 -DUSE_THREAD_ALLOC=1 -D_REENTRANT=1 -D_THREAD_SAFE=1 -DHAVE_PTHREAD_ATTR_SETSTACKSIZE=1 -DHAVE_PTHREAD_GET_STACKSIZE_NP=1 -DTCL_THREADS=1 -DTCL_CFGVAL_ENCODING=\"iso8859-1\" -DMODULE_SCOPE=extern\ __attribute__\(\(__visibility__\(\"hidden\"\)\)\) -DMAC_OSX_TCL=1 -DHAVE_COREFOUNDATION=1 -DTCL_SHLIB_EXT=\".dylib\" -DTCL_CFG_OPTIMIZED=1 -DTCL_CFG_DEBUG=1 -DTCL_TOMMATH=1 -DMP_PREC=4 -DTCL_WIDE_INT_IS_LONG=1 -DHAVE_GETCWD=1 -DHAVE_OPENDIR=1 -DHAVE_STRTOL=1 -DHAVE_WAITPID=1 -DHAVE_GETADDRINFO=1 -DHAVE_GETPWUID_R_5=1 -DHAVE_GETPWUID_R=1 -DHAVE_GETPWNAM_R_5=1 -DHAVE_GETPWNAM_R=1 -DHAVE_GETGRGID_R_5=1 -DHAVE_GETGRGID_R=1 -DHAVE_GETGRNAM_R_5=1 -DHAVE_GETGRNAM_R=1 -DHAVE_MTSAFE_GETHOSTBYNAME=1 -DHAVE_MTSAFE_GETHOSTBYADDR=1 -DHAVE_SYS_TIME_H=1 -DTIME_WITH_SYS_TIME=1 -DHAVE_GMTIME_R=1 -DHAVE_LOCALTIME_R=1 -DHAVE_MKTIME=1 -DHAVE_TM_GMTOFF=1 -DHAVE_TIMEZONE_VAR=1 -DHAVE_STRUCT_STAT_ST_BLOCKS=1 -DHAVE_STRUCT_STAT_ST_BLKSIZE=1 -DHAVE_BLKCNT_T=1 -DHAVE_INTPTR_T=1 -DHAVE_UINTPTR_T=1 -DHAVE_SIGNED_CHAR=1 -DHAVE_LANGINFO=1 -DHAVE_CHFLAGS=1 -DHAVE_GETATTRLIST=1 -DHAVE_COPYFILE_H=1 -DHAVE_COPYFILE=1 -DHAVE_LIBKERN_OSATOMIC_H=1 -DHAVE_OSSPINLOCKLOCK=1 -DHAVE_PTHREAD_ATFORK=1 -DUSE_VFORK=1 -DTCL_DEFAULT_ENCODING=\"utf-8\" -DTCL_LOAD_FROM_MEMORY=1 -DTCL_WIDE_CLICKS=1 -DHAVE_AVAILABILITYMACROS_H=1 -DHAVE_WEAK_IMPORT=1 -D_DARWIN_C_SOURCE=1 -DHAVE_FTS=1 -DHAVE_SYS_IOCTL_H=1 -DHAVE_SYS_FILIO_H=1 -DTCL_UNLOAD_DLLS=1 -DUSE_DTRACE=1 -DTCL_STACK_GROWS_UP=1 -DTCL_FRAMEWORK=1 
TCL_EXEC_PREFIX = /usr
TCL_INCLUDES = 
TCL_INSTALL_DIR = /usr/lib/tcl8.5
TCL_LIBS = 
TCL_MAJOR_VERSION = 8
TCL_MINOR_VERSION = 5
TCL_PATCH_LEVEL = .9
TCL_PKGINDEX = tcldot/pkgIndex.tcl tclpathplan/pkgIndex.tcl
TCL_PKGINDEX_GD = gdtclft/pkgIndex.tcl
TCL_PKGINDEX_SWIG = gv/pkgIndex.tcl
TCL_SHLIB_SUFFIX = .dylib
TCL_SRC_DIR = /SourceCache/tcl/tcl-102/tcl/tcl
TCL_STUB_LIB_SPEC = -L/System/Library/Frameworks/Tcl.framework/Versions/8.5 -ltclstub8.5
TCL_VERSION = 8.5
VERSION = 2.39.20161126.1803
VISIO_CFLAGS = 
VISIO_LIBS = 
WEBP_CFLAGS = -I/usr/local/Cellar/webp/0.4.3/include
WEBP_LIBS = -L/usr/local/Cellar/webp/0.4.3/lib -lwebp
XAW_INCLUDES = -I/opt/X11/include
XAW_LIBS =  -L/opt/X11/lib -L/opt/X11/lib -lXaw
XMKMF = 
XPM_INCLUDES = 
XPM_LIBS =  -lXpm
XRENDER_CFLAGS = -I/opt/X11/include
XRENDER_LIBS = -L/opt/X11/lib -lXrender -lX11
X_CFLAGS =  -I/opt/X11/include
X_EXTRA_LIBS = 
X_LIBS =  -L/opt/X11/lib
X_PRE_LIBS =  -lSM -lICE
YACC = bison -y
YFLAGS = 
Z_INCLUDES = 
Z_LIBS =  -lz
abs_builddir = /Users/erg/gviz/doc/info
abs_srcdir = /Users/erg/gviz/doc/info
abs_top_builddir = /Users/erg/gviz
abs_top_srcdir = /Users/erg/gviz
ac_ct_AR = ar
ac_ct_CC = gcc
ac_ct_CXX = g++
ac_ct_DUMPBIN = 
ac_ct_OBJC = gcc
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build = x86_64-apple-darwin13.4.0
build_alias = 
build_cpu = x86_64
build_os = darwin13.4.0
build_vendor = apple
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = x86_64-apple-darwin13.4.0
host_alias = 
host_cpu = x86_64
host_os = darwin13.4.0
host_vendor = apple
htmldir = $(pkgdatadir)/doc/html/info
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /Users/erg/gviz/config/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
ltdl_LIBOBJS =  lt__argz.o
ltdl_LTLIBOBJS =  lt__argz.lo
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /Users/erg
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
subdirs =  libltdl
sys_symbol_underscore = yes
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../../
top_builddir = ../..
top_srcdir = ../..
html_DATA = attrs.html colors.html command.html \
  index.html lang.html output.html shapes.html arrows.html \
  Mcircle.gif Mdiamond.gif Msquare.gif a_box.gif a_crow.gif a_diamond.gif \
  a_dot.gif a_ediamond.gif a_empty.gif a_forward.gif a_halfopen.gif \
  a_inv.gif a_invdot.gif a_invempty.gif a_invodot.gif a_lteeoldiamond.gif \
  a_nohead.gif a_none.gif a_normal.gif a_obox.gif a_odiamond.gif \
  a_odot.gif a_open.gif a_tee.gif aa_box.gif aa_crow.gif aa_diamond.gif \
  aa_dot.gif aa_inv.gif aa_lbox.gif aa_lcrow.gif aa_ldiamond.gif \
  aa_linv.gif aa_lnormal.gif aa_ltee.gif aa_lvee.gif aa_none.gif \
  aa_normal.gif aa_obox.gif aa_odiamond.gif aa_odot.gif aa_oinv.gif \
  aa_olbox.gif aa_oldiamond.gif aa_olinv.gif aa_olnormal.gif \
  aa_onormal.gif aa_orbox.gif aa_ordiamond.gif aa_orinv.gif \
  aa_ornormal.gif aa_rbox.gif aa_rcrow.gif aa_rdiamond.gif aa_rinv.gif \
  aa_rnormal.gif aa_rtee.gif aa_rvee.gif aa_tee.gif aa_vee.gif back.gif \
  both.gif box.gif box3d.gif circle.gif colorlist.gif component.gif underline.gif \
  constraint.gif cylinder.gif diamond.gif doublecircle.gif doubleoctagon.gif egg.gif \
  ellipse.gif fill.gif folder.gif forward.gif hexagon.gif house.gif \
  g_lin0.png g_lin270.png g_lin45.png g_rad0.png g_rad270.png g_rad45.png \
  g_lin180.png g_lin360.png g_lin90.png g_rad180.png g_rad360.png g_rad90.png \
  html1.gif html2.gif html3.gif html4.gif invhouse.gif invtrapezium.gif \
  invtriangle.gif mrecord.gif nohead.gif none.gif plain.gif note.gif octagon.gif \
  oval.gif parallelogram.gif pentagon.gif plaintext.gif point.gif polygon.gif \
  record.gif record2.gif rect.gif rectangle.gif round.gif septagon.gif tab.gif \
  trapezium.gif triangle.gif tripleoctagon.gif sdlshapes.jpg sdlshapes.png \
  square.gif html2.gv html3.gv html4.gv plugins.png \
  c_bold.png c_dashed.png c_dotted.png c_filled.png c_rounded.png c_solid.png c_striped.png \
  e_bold.png e_dashed.png e_dotted.png e_solid.png \
  g_lin0.png g_lin180.png g_lin270.png g_lin360.png g_lin45.png g_lin90.png g_rad0.png \
  g_rad180.png g_rad270.png g_rad360.png g_rad45.png g_rad90.png \
  n_bold.png n_dashed.png n_diagonals.png n_dotted.png n_filled.png \
  n_rounded.png n_solid.png n_striped.png n_wedged.png \
  none_back.png none_both.png none_forward.png none_none.png \
  normal_back.png normal_both.png normal_forward.png normal_none.png \
  spline_curved.png spline_none.png spline_polyline.png \
  spline_line.png spline_ortho.png spline_spline.png

EXTRA_DIST = $(html_DATA)
all: all-am

.SUFFIXES:
$(srcdir)/Makefile.in:  $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --gnu doc/info/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --gnu doc/info/Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure:  $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4):  $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs
install-htmlDATA: $(html_DATA)
	@$(NORMAL_INSTALL)
	@list='$(html_DATA)'; test -n "$(htmldir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(htmldir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(htmldir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(htmldir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(htmldir)" || exit $$?; \
	done

uninstall-htmlDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(html_DATA)'; test -n "$(htmldir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(htmldir)'; $(am__uninstall_files_from_dir)
tags TAGS:

ctags CTAGS:

cscope cscopelist:


distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(DATA)
installdirs:
	for dir in "$(DESTDIR)$(htmldir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic clean-libtool mostlyclean-am

distclean: distclean-am
	-rm -f Makefile
distclean-am: clean-am distclean-generic

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am: install-htmlDATA

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am:

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-generic mostlyclean-libtool

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-htmlDATA

.MAKE: install-am install-strip

.PHONY: all all-am check check-am clean clean-generic clean-libtool \
	cscopelist-am ctags-am distclean distclean-generic \
	distclean-libtool distdir dvi dvi-am html html-am info info-am \
	install install-am install-data install-data-am install-dvi \
	install-dvi-am install-exec install-exec-am install-html \
	install-html-am install-htmlDATA install-info install-info-am \
	install-man install-pdf install-pdf-am install-ps \
	install-ps-am install-strip installcheck installcheck-am \
	installdirs maintainer-clean maintainer-clean-generic \
	mostlyclean mostlyclean-generic mostlyclean-libtool pdf pdf-am \
	ps ps-am tags-am uninstall uninstall-am uninstall-htmlDATA

.PRECIOUS: Makefile


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
