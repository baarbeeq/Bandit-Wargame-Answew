ssh bandit0@bandit.labs.overthewire.org -p 2220
bandit0
ls
cat readme
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
ssh bandit1@bandit.labs.overthewire.org -p 2220
ls
cat ./-
263JGJPfgU6LtdEvgfWU1XP5yac29mFx
ssh bandit2@bandit.labs.overthewire.org -p 2220
ls
--spaces in this filename--
cat ./'--spaces in this filename--'
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
ssh bandit3@bandit.labs.overthewire.org -p 2220
ls
cd inhere
ls
ls -a
cat ./'...Hiding-From-You'
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
ssh bandit4@bandit.labs.overthewire.org -p 2220
ls
cd inhere
ls
cat ./'-file07'
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
ssh bandit5@bandit.labs.overthewire.org -p 2220
ls
cd inhere
ls
find -size 1033c
cat ./maybehere07/.file2
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
ssh bandit6@bandit.labs.overthewire.org -p 2220
cd /
find -user bandit7 -group bandit6 -size 33c
cat ./var/lib/dpkg/info/bandit7.password
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
ssh bandit7@bandit.labs.overthewire.org -p 2220
ls
grep millionth data.txt
dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
ssh bandit8@bandit.labs.overthewire.org -p 2220
ls
sort data.txt | uniq -u
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
ssh bandit9@bandit.labs.overthewire.org -p 2220
ls
strings -10 data.txt
FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
ssh bandit10@bandit.labs.overthewire.org -p 2220
ls
cat data.txt
base64 -d data.txt
dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
ssh bandit11@bandit.labs.overthewire.org -p 2220
ls
cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
ssh bandit12@bandit.labs.overthewire.org -p 2220
ls
mkdir /tmp/newfolder
cp data.txt /tmp/newfolder
xxd -r data.txt dataR
mv dataR data2.gz
gzip -d data2.gz
mv data2 data3.bz2
bzip2 -d data3.bz2
mv data3 data4.gz
gzip -d data4.gz
tar -xvf data4
tar -xvf data5.bin
mv data6.bin data7.bz2
bzip2 -d data7.bz2
tar -xvf data7
mv data8.bin data9.gz
gzip -d data9.gz
cat data9
FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
ssh bandit13@bandit.labs.overthewire.org -p 2220
ls
cat sshkey.private
scp -P 2220 bandit13@bandit.labs.overthewire.org:sshkey.private .
ssh -i sshkey.private -p 2220 bandit14@bandit.labs.overthewire.org
cd /etc/bandit_pass/
cat bandit14
MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
nc localhost 30000
MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
ssh bandit15@bandit.labs.overthewire.org -p 2220
openssl s_client -connect localhost:30001 
8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx
ssh bandit16@bandit.labs.overthewire.org -p 2220



















