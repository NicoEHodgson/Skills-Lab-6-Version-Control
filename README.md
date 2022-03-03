# SaveTheGlobe

sglobe is an interative program that solves global warming by shutting down all computers in a 5 mile range with a kill command. By shutting down the computers, the computer stops emitting heat and taking up energy. This program is wide spread through all major companies including Google, Microsoft, Apple, Facebook, and Tesla Mainframes to reduce global warming and shutdown cyberattacks on their machine.

## Installation

To install from Debian repositories

```shell
        sudo apt update
        sudo apt install sglobe
```
To Compile
```shell
        sudo apt install g++ make libmbedtls-dev libssl-dev liblz4-dev cmake
        export O3=~/sglobe && mkdir $O3
        export DEP_DIR=$O3/deps && mkdir $DEP_DIR
        export DL=$O3/dl && mkdir $DL
```

## Usage
```shell
        sudo sglobe --help
```
* The above command will give you a short rundown of the avalible commands of sglobe.

```shell
        sudo sglobe --r 1
```
* The command above will run sglobe in a radius of 1 mile. The radius can be between 0 miles exlusive and 5 miles inclusive.

```shell
        sudo sglobe --d 00:00:00:00:00:00
```
* The command above will run sglobe in a debug mode. Here, you have to specify the mac address of the device that sglobe should target, in this case it is 00:00:00:00:00:00.


## Contribute
Please view are our [Code Of Conduct](https://github.com/NicoEHodgson/Skills-Lab-6-Version-Control/blob/main/CoC.md) before you continue.

If you would like to contribute to the project, you just have to fork the code. To run it, you have to clone the files from your fork to any linux machine and compile it with the steps above. To test your code, run it using the debug flag --d and enter that mac address of your target computer to shutdown. We are open to considering any types of modifications to the code. If your modification betters the efficiency of a run of sglobe or it adds a necessary feature to the project we will most likely integrate it. To send us your edits, just send a pull request from your fork with a message explaining what your altercations do.

## License
View our [License](https://github.com/NicoEHodgson/Skills-Lab-6-Version-Control/blob/main/LICENSE.md) for the software.

## Contributers
The contributers who started the project are Nico Hodgson and Parth Patel.