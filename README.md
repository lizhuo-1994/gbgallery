# gbgallery


Abstract
Software bug database and benchmark are the wheels of automated software testing advancement. Real bugs often occur rather sparsely in relative to the amount of software code, the extraction and curation of which are quite labor-intensive but can be the essentials to innovate testing techniques.

What is GBGallery?

GBGallery is an opened game bug database and game testing framework, which contains 5 commercial games and 76 real industrial game bugs in total. 

In GBGallery, we have integrated 5 automated game testing strategies include : Random, DQN, A2C, A2C+curiosity, and Wuji (the distinguished paper in ASE 2019).  DQN and  A2C are basic deep reinforcement learning algorithm (DRL), A2C+curiosity contains an extra curiosity-driven agent exploration guidance than A2C, Wuji is a combination of search-based optimization with DRL. Currently few research was proposed for automated game testing by AI, thus we propose GBGallery to encourage the above research.

What is structure of  the GBGallery?

GBGallery is constructed by 5 games and the game bugs, therefore GBGallery contains 5 independent program package.



Environment installation

Installation for anaconda on Linux:

		wget https://repo.anaconda.com/archive/Anaconda3-2020.11-Linux-x86_64.sh 

		bash ./Anaconda3-2020.11-Linux-x86_64.sh 

		echo 'export PATH="$pathToAnaconda/anaconda3/bin:$PATH"' >> ~/.bashrc 

		conda config --set auto_activate_base false 

Installation for anaconda on MS-Windows:

See specific tutorial from official website: Documentation 	

Download the packaged environment:

		download [benchmark_env.tar.gz](https://drive.google.com/file/d/1Kv3Y5krhCEP4Ikhl7_tt2MFCJ61B3Ndt/view?usp=sharing)

Activate the environment:

		(1) mkdir -p benchmark_env

		(2) tar -xzf benchmark_env.tar.gz -C benchmark_env/

		(3) source benchmark_env/bin/activate

Finally, the set up of environment is done, please download GBGallery and refer to the following document for usage:

	 	download [gbgallery.zip](https://drive.google.com/file/d/13gyC_xxQcZmNi_jxebTBEfhCwIIJgtXl/view?usp=sharing)
		
