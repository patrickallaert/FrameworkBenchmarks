all: cppsp_0.2

clean:
	rm -rf cppsp_0.2-rc9 cppsp_0.2
	rm -f www/*.so www/*.txt
cppsp_0.2: cppsp_0.2-rc9.tar.xz
	tar xf cppsp_0.2-rc9.tar.xz
	ln -s cppsp_0.2-rc9 cppsp_0.2
	$(MAKE) CXX=g++-4.8 -C cppsp_0.2 all

cppsp_0.2-rc9.tar.xz:
	wget -c http://downloads.sourceforge.net/project/cpollcppsp/CPPSP%200.2%20%28testing%29/cppsp_0.2-rc9.tar.xz

