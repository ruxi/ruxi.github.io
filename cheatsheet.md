# virtual environment

conda env update		 		
 - makes venv via environment.yml

source activate githubpage      	 	
 - load venv (might be different name)

conda env export --file environment.yml
 -  exports requirement list. 
 -  doesn't include software channels metadata

conda list --explicit > explicit_environment.yml
