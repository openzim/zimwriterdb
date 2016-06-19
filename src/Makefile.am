bin_PROGRAMS = zimwriterdb zimindexer zimcreatorsearch wikizim

AM_CPPFLAGS=-I$(top_srcdir)/include

# wikizim
#
wikizim_SOURCES = \
	wikizim.cpp
wikizim_LDFLAGS = -lcxxtools -lcxxtools-http -lzim

# zimwriterdb
#
zimwriterdb_SOURCES = \
    dbsource.cpp \
    filesource.cpp \
    zimwriterdb.cpp

zimwriterdb_LDFLAGS = -lcxxtools -lzim -ltntdb

# zimindexer
#
zimindexer_SOURCES = \
    articleparser.cpp \
    indexersource.cpp \
    mstream.cpp \
    zimindexer.cpp
zimindexer_LDFLAGS = -lcxxtools -lzim

# zimcreataorsearch
#
zimcreatorsearch_SOURCES = \
    zimcreatorsearch.cpp \
    search.cpp
zimcreatorsearch_LDFLAGS = -lcxxtools -lzim
