## Process this file with automake to produce Makefile.in
##
## Copyright (C) 2003 Carnegie Mellon University
## Written by H�kan L. S. Younes.
##
## Permission is hereby granted to distribute this software for
## non-commercial research purposes, provided that this copyright
## notice is included with any such distribution.

## THIS SOFTWARE IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND,
## EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, THE
## IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
## PURPOSE.  THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE
## SOFTWARE IS WITH YOU.  SHOULD THE PROGRAM PROVE DEFECTIVE, YOU
## ASSUME THE COST OF ALL NECESSARY SERVICING, REPAIR OR CORRECTION.
##
## $Id: Makefile.am,v 1.6 2003/03/01 18:56:34 lorens Exp $

bin_PROGRAMS = vhpop
vhpop_SOURCES = vhpop.cc exceptions.cc exceptions.h parameters.cc parameters.h types.cc types.h formulas.cc formulas.h domains.cc domains.h problems.cc problems.h bindings.cc bindings.h orderings.cc orderings.h flaws.cc flaws.h reasons.cc reasons.h heuristics.cc heuristics.h plans.cc plans.h requirements.cc requirements.h pddl.yy tokens.ll chain.h debug.h hashing.h mathport.h
vhpop_LDADD = @LIBOBJS@
MAINTAINERCLEANFILES = pddl.cc tokens.cc
EXTRA_DIST = getopt.c getopt1.c getopt.h ipc3-vhpop examples scripts

YFLAGS = -d
