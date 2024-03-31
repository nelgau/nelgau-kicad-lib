all : ng_fpga_lattice_ice40.kicad_sym 

ice := ice40pinouthx4k

ng_fpga_lattice_ice40.kicad_sym  : $(ice:=.csv)
	kipart $^ -s row -o $@ -w --fill bg_fill
	mv -f $@ ..
