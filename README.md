<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=2500&pause=800&color=FA00D8&center=true&vCenter=true&width=500&lines=~/accessing+root+identity...;~/injecting+automation+into+chaos...;~/establishing+command+channel..." alt="Typing SVG" />

### 🧠 whoami

```bash
┌──(nevsd㉿kali)-[~]
└─$  finger $(whoami)

Login: nevsd                    Name: Flavio Neves
Directory: /home/nevsd          Shell: /usr/bin/zsh
On since Wed Jan 22 22:20 2020 (UTC)  on pts/1  56 minutes 32 seconds idle
	(messages off)
Mails.
	Flavio Neves <flavio@nevs.dev>
No plan

#############
# Get Certs #
#############

┌──(flavio㉿nevsd)-[~]
└─$ keytool -list -keystore certs
Enter Keystore password:

Keystore type: JKS
Keystore provider: SUN

Your Keystore contains 1 entries

solution-architect-associate, Dec 31, 2024, AmazonWebServices,
Certificate fingerprint (SHA1): 5A:50:3D:0B:DF:1D:4B:2C:6F:52:E6:23:3C:2B:99:A0:CA:71:87:E2

#########################
# Get Current Processes #
#########################

┌──(flavio㉿nevsd)-[~]
└─$ ps aux | grep dev

USER       PID %CPU %MEM    VSZ   RSS  TTY      STAT START   TIME COMMAND
flavio     1337  5.0  3.2  40256 13024 pts/0    S    09:00   0:12 Python
flavio     4200  2.8  2.5  35840 10560 pts/0    S    09:02   0:07 Go
flavio     2718  3.6  2.0  27400  8704 pts/1    S    09:05   0:05 Rust

┌──(flavio㉿nevsd)-[~]
└─$ ps aux | grep cloud

USER       PID %CPU %MEM    VSZ   RSS  TTY      STAT START   TIME COMMAND
flavio     1531  9.0  3.2  40256 13024 pts/0    S    09:00   0:12 AWS
```

