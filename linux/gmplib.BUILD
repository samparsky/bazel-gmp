genrule(
	name = "gmplib",
	srcs = glob(["**/*"]),
	outs = [
	  "gmp.h",
	],
  cmd = "curdir=`pwd`; cp -r ./external/gnuimage /tmp/gnuimage && cd /tmp/gnuimage; ./configure && make && make install; cp /usr/local/include/gmp.h $$curdir/$(@D)"
)