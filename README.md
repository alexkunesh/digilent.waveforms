Hacky fix so classmates and I can use the (currently broken) Waveforms AUR package. Installation instructions:

1. Clone this repository.
2. Download this file and place it in the cloned repo https://files.digilent.com/Software/Waveforms/3.25.1/digilent.waveforms_3.25.1_amd64.deb
3. `yay -S --asdeps digilent.adept.runtime qt6-serialport`
4. In the repo directory: `makepkg -si`
