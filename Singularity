Bootstrap: shub
From: CNC-UMCG/cnc_base


%post
        apt-get instal -y software-properties-common
        apt-key adv --keyserver keyserver.ubuntu.com --recv-keys E298A3A825C0D65DFD57CBB651716619E084DAB9
	add-apt-repository 'deb [arch=amd64,i386] https://cran.rstudio.com/bin/linux/ubuntu xenial/'
	apt-get update
	
	apt-get install -y r-core
