# **********************************************************
# Makefile for rfilter1 Directory
# **********************************************************
SHELL = /bin/sh
PREFIX=/Users/jfesslmeier/Downloads/sctk-2.4.0
bindir = $(PREFIX)/bin
T=../test_suite

all: mergectm2rttm.pl

mergectm2rttm.pl: 
	chmod +x mergectm2rttm.pl

check: all
	@echo "No Tests for mergectm2rttm.pl"

install: all
	cp mergectm2rttm.pl $(bindir)

clean:

distclean: clean
	rm -r *~ makefile
