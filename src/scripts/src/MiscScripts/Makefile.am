INCLUDES = -I$(top_srcdir)/src/arcemu-logonserver \
   -I$(top_srcdir)/src/arcemu-realmserver -I$(top_srcdir)/src/arcemu-shared -I$(top_srcdir)/src/arcemu-voicechat \
   -I$(top_srcdir)/src/arcemu-world -I$(srcdir) -I$(srcdir)/../../../../dep/include \
   -I$(srcdir)/../../../../dep/src -I$(srcdir)/../../../../src

AM_CXXFLAGS = -DSCRIPTLIB

lib_LTLIBRARIES = libMoonMiscScripts.la

libMoonMiscScripts_la_SOURCES = Creatures.cpp \
GameObjectTeleportTable.cpp \
GameObjects.cpp \
RandomScripts.cpp \
WyrmrestTemple.cpp \
EbonHold.cpp \
Logride_GrizzlyHills.cpp \
Setup.cpp
