# linear_algebra
hls implementation of linear algebra

reference: ~Xilinx/Vivado/2019.2/examples/design/linear_algebra

- **linear_algebra** - In linear algebra, the singular value decomposition (SVD) is a factorization of a matrix that generalizes the eigen-decomposition of a square normal matrix to any m x n matrix via an extension of the polar decomposition.

## DESIGN FILE HIERARCHY

	|   README.md
	|   
	\---code
			\---hls_library
					hls_svd.h
			svd.h
			svd.cpp
	\---code_opt
			svd.h
			svd.cpp
	\---script
			run_hls.tcl
	\---impl
			csynth.xml
			top_svd_sim.log
	\---testdata
			svd_tb.cpp


## OTHER INFORMATION

For more information check here: 

[Vivado HLS User Guide][]

## SUPPORT

For questions and to get help on this project or your own projects, visit the [Vivado HLS Forums][]. 

