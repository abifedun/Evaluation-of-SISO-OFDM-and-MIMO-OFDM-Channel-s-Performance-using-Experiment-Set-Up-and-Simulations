# Evaluation-of-SISO-OFDM-and-MIMO-OFDM-Channel-s-Performance-using-Experiment-Set-Up-and-Simulations
# Evaluation of SISO-OFDM and MIMO-OFDM Channel’s Performance using Experiment Set Up and Simulations
Simulation and Laboratory Experiment were carried out using the GNU Radio software platform.
OFDM System was evaluated using Simulation and Experiment with USRP N210.
An IEEE 802.11 WLAN system is built using the SISO-OFDM and MIMO-OFDM transciever network in GNU Radio.
The channel's performance is evaluated by using various Channel Models such as AWGN Noise Channel Model and Frequency Selective Fading Model which consists of Compact Rayleigh and Rician fading simulator based on random walk processes.
Performance measurement includes PER for experiemntation and BER for simulation.
A complete guide on how to install GNU Radio can be followed using this link:
https://wiki.gnuradio.org/index.php/InstallingGR
A short description of installation commands to follow is depicted below:
•Installing GNU Radio
•cd
•git clone https://github.com/gnuradio/gnuradio.git
•cd gnuradio
•mkdir build
•cd build
•cmake -DCMAKE_BUILD_TYPE=Release -DPYTHON_EXECUTABLE=/usr/bin/python3 ../
•make
