rnastruc_clanstix
-------------------------------------------------------------------------------

A tool for visualizing RNA 3D structures based on pairwise structural similarity.
<img src="doc/yndSrLTb7l.gif">

The RMSDs between structures are converted into p-values based on the method from the Dokholyan lab.

Hajdin, C. E., Ding, F., Dokholyan, N. V, & Weeks, K. M. (2010). On the significance of an RNA tertiary structure prediction. RNA (New York, N.Y.), 16(7), 1340–9. doi:10.1261/rna.1837410

An output of this tool can be viewed using <a href="http://www.eb.tuebingen.mpg.de/research/departments/protein-evolution/software/clans.html">CLANS</a>.

Frickey, T., & Lupas, A. (2004). CLANS: a Java application for visualizing protein families based on pairwise similarity. Bioinformatics (Oxford, England), 20(18), 3702–4. doi:10.1093/bioinformatics/bth444

INSTALL

    git clone --recursive  git@github.com:m4rx9/rnastruc_clanstix.git
	$ ./test.sh
	rnastruc_clanstix.py
	------------------------------------------------------------
	input test_data/matrix.txt
	clans_run.txt generated