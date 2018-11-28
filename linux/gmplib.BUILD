genrule(
	name = "gmplib",
	srcs = glob(["**/*"]),
	outs = [
	  "gmp.h",
	],
	local=0,
  cmd = "curdir=`pwd`; cp -r ./external/gnuimage /home/gnuimage && cd /home/gnuimage; ./configure && make && make install; cp /usr/local/include/gmp.h $$curdir/$(@D)"
)