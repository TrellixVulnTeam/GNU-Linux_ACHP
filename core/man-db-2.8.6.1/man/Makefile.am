## Process this file with automake to produce Makefile.in
##
## Copyright (C) 1994, 1995 Graeme Wilford.
## Copyright (C) 2001, 2002, 2003, 2007 Colin Watson.
##
## This file is part of man-db.
##
## man-db is free software; you can redistribute it and/or modify it
## under the terms of the GNU General Public License as published by
## the Free Software Foundation; either version 2 of the License, or
## (at your option) any later version.
##
## man-db is distributed in the hope that it will be useful, but
## WITHOUT ANY WARRANTY; without even the implied warranty of
## MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
## GNU General Public License for more details.
##
## You should have received a copy of the GNU General Public License
## along with man-db; if not, write to the Free Software Foundation,
## Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA

SUBDIRS = $(MAN_SUBDIRS)
DIST_SUBDIRS = \
	po4a \
	da \
	de \
	es \
	fr \
	id \
	it \
	ja \
	nl \
	pl \
	pt \
	pt_BR \
	ru \
	sr \
	sv \
	tr \
	zh_CN

LINGUA = .

man1_MANS = \
	man1/apropos.1 \
	man1/lexgrog.1 \
	man1/man.1 \
	man1/manconv.1 \
	man1/manpath.1 \
	man1/whatis.1 \
	man1/zsoelim.1
man5_MANS = \
	man5/manpath.5
man8_MANS = \
	man8/accessdb.8 \
	man8/catman.8 \
	man8/mandb.8

EXTRA_DIST = LINGUAS LINGUAS.po4a check-man

include $(srcdir)/Rules.man
