*.sublime-project
*.sublime-workspace
todo.txt
reset-files.bash

*.tar.gz

*.exe
src/unode
src/unoded
src/unode-cli
src/unode-tx
src/test/test_unode
src/qt/test/test_unode-qt
src/bench/bench_unode

# autoreconf
Makefile.in
aclocal.m4
autom4te.cache/
build-aux/config.guess
build-aux/config.sub
build-aux/depcomp
build-aux/install-sh
build-aux/ltmain.sh
build-aux/m4/libtool.m4
build-aux/m4/lt~obsolete.m4
build-aux/m4/ltoptions.m4
build-aux/m4/ltsugar.m4
build-aux/m4/ltversion.m4
build-aux/missing
build-aux/compile
build-aux/test-driver
config.log
config.status
configure
libtool
src/config/unode-config.h
src/config/unode-config.h.in
src/config/stamp-h1
share/setup.nsi
share/qt/Info.plist

src/univalue/gen

src/qt/*.moc
src/qt/moc_*.cpp
src/qt/forms/ui_*.h

src/qt/test/moc*.cpp
libconftest.dylib*

.deps
.dirstamp
.libs
.*.swp
*.*~*
*.bak
*.rej
*.orig
*.pyc
*.o
*.o-*
*.patch
.unode
*.a
*.pb.cc
*.pb.h

*.log
*.trs
*.dmg

*.json.h
*.raw.h

#libtool object files
*.lo
*.la

# Compilation and Qt preprocessor part
*.qm
Makefile
unode-qt
unode-Qt.app

# Unit-tests
Makefile.test
unode-qt_test
src/test/buildenv.py

# Resources cpp
qrc_*.cpp

# Mac specific
.DS_Store
build

#lcov
*.gcno
*.gcda
/*.info
test_unode.coverage/
total.coverage/
coverage_percent.txt

#build tests
linux-coverage-build
linux-build
win32-build
qa/pull-tester/run-bitcoind-for-test.sh
qa/pull-tester/tests_config.py
qa/pull-tester/cache/*
qa/pull-tester/test.*/*
qa/tmp
cache/
share/BitcoindComparisonTool.jar

!src/leveldb*/Makefile

.cproject
.project
.autotools
/doc/doxygen/

libunodeconsensus.pc
src/qt/unode-qt.bash
qa/pull-tester/tests-config.sh

#development symlinks
unode-cli
unoded
unode-qt
make
