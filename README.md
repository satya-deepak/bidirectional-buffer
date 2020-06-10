# bidirectional-buffer with non-inverting CMOS input
This project has files needed to design and implement GPIO

steps to install NI multism on windows:
1) go to the following link https://www.malavida.com/en/soft/ni-multisim/#gref 
2) click the download button 
3) open the .exe file from the downloads
4) click ok in the dailoge box opened and unzip the file to a particular destination on the PC
5) After the files are unzipped click on install NI circuit design suite 14.0 and continue the installation process
6) Now open NI multism and continue the simualtion

Getting strted with simulation:
1) Go to place->component->all families->nmos to get the component NMOS
2) similarly import PMOS, inverter(NOT gate), digital clock to give inputs to both buffers connected in bidirectional fashion
3) import digital constant which can used as an enable pin connecting it directly to source terminal of the PMOS
4)place 5 voltage probes (place->probe->voltage) as shown in the 
5)
