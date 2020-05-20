all : ng_fpga_lattice_ice40.lib 

ice := ice40pinouthx4k

ng_fpga_lattice_ice40.lib  : $(ice:=.csv)
	kipart $^ -s row -o $@ -w --fill bg_fill
	mv -f $@ ..
