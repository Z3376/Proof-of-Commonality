The code file is a jupyter notebook (.ipynb).

Check requirements in requirements.txt file.

txedges.dat file will be required to run the code.

To create txedge.dat you can follow the instructions below. Also, code has been provided in the "Terminal" section of the ipython notebook. 

Instructions to create txedges.dat:
	1. Download txin.dat and txout.dat from https://senseable2015-6.mit.edu/bitcoin/
	2. Clone https://github.com/dkondor/txedges
	3. Compile txedges.cpp using command "g++ -o txedge txedge.cpp -std=gnu++14 -O3 -march=native"
	4. Run txedges on txin.dat and txout.dat to produce txedges.dat using command "./txedge -ix txin.dat.xz -ox txout.dat.xz > txedges.dat"


[IMPORTANT]
Once you have created txedges.dat change the path_to_txedges variable in "Data" section of the notebook.


After changing the path, you can run the code.



