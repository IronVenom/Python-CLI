![PyPI](https://img.shields.io/pypi/v/iitbbscliupdates.svg) ![PyPI - License](https://img.shields.io/pypi/l/iitbbscliupdates.svg)

## IIT Bhubaneswar CLI
A CLI (Command Line Interface) App to get the following stuff related to institute:
* Holidays List for the current year.
* Top 30 headlines depicting the ongoings inside the institute.
* Biometric Attendance from ERP.
* Results from ERP (SGPAs, CGPA and Report Card).

### Installation
```
$ pip install iitbbscliupdates
```
### Usage
After the installation, go to the command line :
1. To get the help menu: 
```
$ iitbbscli --help
```
![Alt Text](https://github.com/IronVenom/iitbbscli/blob/master/assets/help.JPG)

2. To get the list of holidays:
```
$ iitbbscli holidays
```
![Alt Text](https://github.com/IronVenom/iitbbscli/blob/master/assets/holidays.JPG)

3. To get the headlines:
```
$ iitbbscli headlines
```
![Alt Text](https://github.com/IronVenom/iitbbscli/blob/master/assets/headlines.JPG)

4. To get the biometric attendance: ( Username and Password are the ones that are required in the ERP System )
```
$ iitbbscli attendance
```
![Alt Text](https://github.com/IronVenom/iitbbscli/blob/master/assets/attendance_.png)

5. To get results of examinations:
```
$ iitbbscli result
```
![Alt Text](https://github.com/IronVenom/iitbbscli/blob/master/assets/sgpa_.png)
![Alt Text](https://github.com/IronVenom/iitbbscli/blob/master/assets/report%20card_.png)
![Alt Text](https://github.com/IronVenom/iitbbscli/blob/master/assets/cgpa_.png)




