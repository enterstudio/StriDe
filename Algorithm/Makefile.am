noinst_LIBRARIES = libalgorithm.a

libalgorithm_a_CPPFLAGS = \
	-I$(top_srcdir)/Bigraph \
	-I$(top_srcdir)/Util \
	-I$(top_srcdir)/StringGraph \
	-I$(top_srcdir)/SQG \
	-I$(top_srcdir)/SuffixTools \
	-I$(top_srcdir)/Thirdparty \
	-I$(top_srcdir)/GraphDiff \
	-I$(top_srcdir)/FMIndexWalk \
    -I$(top_srcdir)/Concurrency

libalgorithm_a_SOURCES = \
        OverlapAlgorithm.h OverlapAlgorithm.cpp \
	SearchSeed.h SearchSeed.cpp \
	OverlapBlock.h OverlapBlock.cpp \
	SearchHistory.h SearchHistory.cpp \
        ErrorCorrectProcess.h ErrorCorrectProcess.cpp \
        QCProcess.h QCProcess.cpp \
        FMMergeProcess.h FMMergeProcess.cpp \
        KmerOverlaps.h KmerOverlaps.cpp
