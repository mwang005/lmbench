# lmbench
Clone from http://www.bitmover.com/lmbench/

---

Quick Start

    cd lmbench3/src

    vim ./Makefile
	      231 $O/lmbench : ../scripts/lmbench bk.ver
		        delete bk.ver
	      231 $O/lmbench : ../scripts/lmbench

    make results

    cd ../results

    make LIST=x86_64-linux-gnu/*

