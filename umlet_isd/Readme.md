##The Directory Structure of Umlet_ISD##

	umlet_isd/
	├── examples/
	├── html/
	├── img/
	├── lib/
	├── palettes/
	├── umlet.jar
	└── umlet.sh

##How to start Umlet ISD ?##
1. open a terminal
2. cd /path/to/umlet_isd
3. exec "./umlet.sh" or "java -jar umlet.jar".

##How to use Umlet ISD to verify Interrupt Sequence Diagram(ISD) model ?
1. boot Umlet ISD
2. build ISD model (tips: some ISD models that you can refer to in examples/)
3. click menu button - "ModelCherker", select "spaceex" (notice: the checking process may cost a lot of time)
4. checking result displays in a dialog box after the previous step has done

##NOTICE##
> make sure jre has been installed. 
> model checker - spaceex has been installed.

##Install spaceex###
1. download spaceex for Linux_x86_64(may need change according to OS). (http://spaceex.imag.fr/sites/default/files/downloads/private/spaceex_exe-0.9.8f.tar.gz)
2. extract *.tar.gz file. (tar -xvf spaceex_exe-0.9.8f.tar.gz /path/to/)
3. add the installation path into profile
	3.1 open file "/etc/profile" or "~/.profile" .
	3.2 add a new line (eg. "export PATH=$PATH:/path/to/spaceex_exe).
4. restart.
