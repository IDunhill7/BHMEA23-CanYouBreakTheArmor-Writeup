Firstly, i tried to run the program after installing the pyarmor library with :

*pip install pyarmor*

![image](https://github.com/IDunhill7/BHMEA23-CanYouBreakTheArmor-Writeup/assets/110286932/879944ae-869b-4bdc-95a4-d8a0d8425a03)

When I tried to read the code, it was obfuscated so this won't work :C

![image](https://github.com/IDunhill7/BHMEA23-CanYouBreakTheArmor-Writeup/assets/110286932/58ad66a3-a1a2-43e1-9b55-1281702f6f0e)

So I tried to run it as it is and what does it do :

![image](https://github.com/IDunhill7/BHMEA23-CanYouBreakTheArmor-Writeup/assets/110286932/c7059bd8-5014-43ec-aecb-17fd0f4e1305)

I searched how to fix this error and found some articles that says some codes that are obfuscated with pyarmor doesn't work with all versions of python :|

So I started to download older versions of python and try to run the code until it worked with python3.10.6 version

![image](https://github.com/IDunhill7/BHMEA23-CanYouBreakTheArmor-Writeup/assets/110286932/2d1a74ec-b2a9-4534-9d75-80d19c505712)

When I run it. It removed it self. So I run it again but with ltrace so I get the memory dump :

there was to much going on 

![image](https://github.com/IDunhill7/BHMEA23-CanYouBreakTheArmor-Writeup/assets/110286932/e1d51797-d0f4-43a3-a12e-25ed92b6b277)

then I searched with Find in terminal with flag prefix BHFlagY{ 

![image](https://github.com/IDunhill7/BHMEA23-CanYouBreakTheArmor-Writeup/assets/110286932/11482199-6774-4c70-b8df-1712483de472)

And got the Flag !! 

BHFlagY{th4t_4rm0r_wasnt_v3ry_5tr0ng}

thanks for reading



