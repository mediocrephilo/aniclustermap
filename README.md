# aniclustermap
.yml + setup files for using aniclustermap

Steps for setting up and running aniclustermap:

	1. make sure you have miniconda2 activated
		- you can do this by typing *export PATH="/lwork/public/miniconda2/bin:$PATH"* and hitting enter
		- then type *cd Desktop* and enter
		- then type *conda init bash* and hit enter
		- you only need to do this the first time, then you are set
	2. if it isn't already, put the .yml file in your home directory (where Desktop, Documents, etc. are)
	3. open the terminal
	4. type *conda env create -f aniENV.yml* and hit enter
	 	- you only need to do this the first time you set it up as well
		- now you should see (aniENV) before your terminal username
		- you're ready to run aniclustermap! follow the instructions on their website to do so