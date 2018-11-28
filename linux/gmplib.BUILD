genrule(
	name = "gmplib",
	srcs = glob(["**/*"]),
	outs = [
	  "gmp.h",
	],
	local=0,
    cmd = "position=`pwd`; cp -r ./external/gnuimage /tmp/gnuimage && cd /tmp/gnuimage; ./configure && make && make install; cp /usr/local/include/gmp.h $$position/$(@D)"
)