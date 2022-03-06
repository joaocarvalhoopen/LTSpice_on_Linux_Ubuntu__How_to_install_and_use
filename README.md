# LTSpice on Linux Ubuntu - How to install and use
Make great analog designs

## Description
This are the steps to install and use LTSpice 64 bits on Linux Ubuntu 20.04 . <br>

## Installation

```
# Update your package manager.
sudo apt-get update

# Install Wine
sudo apt-get install wine-stable

# Download LTSpice 64 bits
cd /tmp/
wget https://ltspice.analog.com/software/LTspice64.exe

# Install LTSpice
wine LTspice64.exe
rm LTspice64.exe
```

## How to execute LTSpice 

```
# Start lstpice through wine
wine ~/.wine/drive_c/Program\ Files/LTC/LTspiceXVII/XVIIx64.exe
```

## Create a directory for your simulation files

```
# To open file in LTSpice, move it to somewhere in ~/.wine/drive_c folder which is the C drive in wine.
mkdir ~/.wine/drive_c/Program\ Files/LTC/LTspiceXVII/examples/Educational/my_ltspice_files

# Copy file from Examples to my_ltspice_files diretory this is more pratical.
cp ~/.wine/drive_c/Program\ Files/LTC/LTspiceXVII/examples/Educational/Clapp.asc ~/.wine/drive_c/Program\ Files/LTC/LTspiceXVII/examples/Educational/my_ltspice_files/Clapp.asc 

# In this way it is better organized but the examples are far away from your projects directory.
mkdir ~/.wine/drive_c/my_ltspice_files_2
cp ~/my_files/test.asc ~/.wine/drive_c/my_ltspice_files_2/
```

## References on LTSpice Simulation

1. **LTspice - Site Analog Devices** <br>
   Program, documentation, tutorials, videos. <br>
   [https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) 

2. Play List - **LTspice tutorial** - **FesZ Electronics** <br>
   Great youtube Channel on LTSpice and Analog Design. <br>
   [https://www.youtube.com/playlist?list=PLT84nve2j1g_wgGcm0Bv3K4RSl2Jdjsey](https://www.youtube.com/playlist?list=PLT84nve2j1g_wgGcm0Bv3K4RSl2Jdjsey)

3. Play List - **LTspice** - **Getting Started Tutorial** - Official tutorials <br>
   [https://www.analog.com/en/education/education-library/videos/video-series/ltspice-getting-started-tutorial.html](https://www.analog.com/en/education/education-library/videos/video-series/ltspice-getting-started-tutorial.html) 

4. Play List - **LTspice** - Essentials Tutorial - Official tutorials <br>
   [https://www.analog.com/en/education/education-library/videos/video-series/ltspice-essentials-tutorial.html](https://www.analog.com/en/education/education-library/videos/video-series/ltspice-essentials-tutorial.html)

5. Video - **LTspice** - **Stepping Parameters** <br>
   [https://www.analog.com/en/education/education-library/videos/5579239884001.html](https://www.analog.com/en/education/education-library/videos/5579239884001.html)

6. Book - **The LTSpice XVII simulator** - Commands and Applications <br>
   by Gilles Brocard <br>

7. Book - **The LTSpice IV Simulator** - Manual, methods and applications <br>
   by Gilles Brocard <br>


## References on installing LTSpice

* ```daniw/ltspice.sh``` - install ltspice on ubuntu (arch commented) <br>
  Note: I use this info but updated it and modified it. <br>
  [https://gist.github.com/daniw/7439488](https://gist.github.com/daniw/7439488)


## My guides on electronics and common components

* **How to learn modern Electronics** <br>
  [https://github.com/joaocarvalhoopen/How_to_learn_modern_electronics](https://github.com/joaocarvalhoopen/How_to_learn_modern_electronics)

* **Most common Components in electronics** <br>
  [https://github.com/joaocarvalhoopen/Most_common_components_in_electronics](https://github.com/joaocarvalhoopen/Most_common_components_in_electronics)


## All my other guides

* The links to all my guides are in: <br>
  **Guides on Linux - Programming - Embedded - Electronics - Aeronautics** <br>
  [https://github.com/joaocarvalhoopen/Guides_Linux-Programming-Electronics-Aeronautics](https://github.com/joaocarvalhoopen/Guides_Linux-Programming-Electronics-Aeronautics)


## Have fun!
Best regards, <br>
João Nuno Carvalho <br>
