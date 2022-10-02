# Pieraksti vieglākai dzīvei :)))))
## Komandas un to skaidrojumi 
1. Paņēmieni
   * ↓ un ↑ lai navigētu komandu izmantošanas vēsturi un nosacīta automātiskā aizpilde.
   * `Tab` poga priekš automātiskās aizpildes un lai redzētu iespējamās opcijas.


2. Kommandas
   * `uname` - OS noskaidrošana
   * `whoami` - Parāda esošā Shell lietotāja nosaukumu.
     * `id -un` = `whoami` (komandas dara to pašu)
   * `pwd` - **Print Working Directory**, lai uzzinātu, kurā directory atrodies pašlaik.
   * `ls` - Dod informāciju par failiem un mapēm konkrētajā sistēmā, kur `ls` bez argumentiem izprintē esošās mapes saturu, izņemot slēptos failus.
     * `ls /[Directory name]` - lai dabūtu saturu kādam konkrētam directory.
        * `ls -a` - Tas pats, bet parāda arī slēptos failus.
     * `ls -l` - parāda esošās mapes saturu detalizētā saraksta veidā.
        * `ls -la` - tas pats, bet parāda arī slēptos failus.
     * `ls ~` - izprintē saturu ierīces "mājas" mapei.
     * `ls -d */` - izprintē tikai mapes, jeb folderus.
     * `ls *` - Dod tagadējā folder un tajā esošo folder saturu.
     * `ls -s`- Izprintē mapes saturu un dod folderā esošo failu un citu folderu lielumus
     * `ls -t`- Dod mapes saturu to izmainīšanas datumu un laiku secībā.
     * `ls -[arguments]r` - "ls" komandas izvade, tikai pretējā secībā.
     * `ls >[fileName].txt` - Izvada IEPRIEKŠĒJĀS shell komandas printēto saturu txt failā, šis fails tiks radīts esošajā mapē.


   * `cd` - lai pārvietotos.
     * `cd ..` - Lai pārvietotos vienu directory līmeni atpakaļ.
     * `cd -` - Lai pārvietotos uz iepriekšējo directory līmeni neatkarīgi no attāluma starp tām.
     * `cd /[Directory name]` - Lai nokļūtu uz konkrētu mapi uz augšu vai leju.


3. Citas lietas
   * `.` pirms faila vai mapes apzīmē to, ka tas ir slēpts.
   * `~`, jeb tilde simbolizē home directory. Uz to var tikt ar `cd ~` vai `cd ~/`

Second thing second
- whoami - parāda lietotāja username

- clear - notīra termināli

- who - prints information about currently logged in users

- last - parāda wtmp (a file containing a history of all logins and logouts)

- pwd - (Print Working Directory) parāda, kur atrodamies

- man man - atver pamācību

- man "any command" - atver pamācību attiecīgajai komandai

- history - apskatīt sarakstu ar iepriekš veiktajām darbībām

- ls - uzskaita failus un directories pašreizējā directory.

- ls -l - uzskaita failus un directories pašreizējā directory kā sarakstu un ar padziļinātāku info.

- ls -a - uzskaita failus un directories, tajā skaitā ar slēptos failus un directories.

- snap - savāc sistēmas config. info un saspiež līdz pax(Portable Archive Exchange) failam

- echo - displays line of text that are passed as argument

- sh - executes commands read from a command line string, the standard input, or a specified file

- cd "exact name of directory" - aiziet uz attiecīgo directory

- cd . - navigate down one directory

- cd .. - aiziet atpakaļ uz iepriekšējo directory

- cd / - aiziet uz pašu sākotnējo "root" directory

- cd ~ - navigate to home directory

- cp "name of a text file" - kopēt failu

- cp "name of a text file" /home/"name of the repository"- kopēt failu attiecīgajā repository

- rm "name of a file" - notīrīt, nodzēst failu

- mkdir "name of a new directory" - izveido directory ar šādu nosaukumu

- rmdir "name of an empty directory" -izdzēš directory, kurā nav failu

- rm -r "name of the directory" -izdzēš attiecīgo directory

- echo "text" > a.txt - creates a file of the echoed text

- mv "nosaukums failam"/a.txt "name of the folder"/ - pārvieto failu uz citu directory

- firefox & - palaiz firefox

- kill "name of the prog" - aptur lietotāja palaisto programmu

- uname -a - print system info

- ps aux -parāda, kādi procesi ir notikuši

- history > history_20220913a.txt

- cat history > history_20220913a.txt

- whereis ls - noskaidrojam, kur sistēmā atrodas fails, šajā gadījumā ls. dators nepārmeklē visu sistēmu, bet noteiktas mapes.

- echo $PATH - var pateikt kāds bija ceļš, lai atrastu failu. parādās saraksts ar caurskatāmajām mapēm.

- ls -l - ar detalizāciju saraksts, + linki(?)

- ls -lt /bin/ls - (domuzime un trīs x (rwxr -xr - x(read, write, execute - trīs reizes, jo kāds ir owner, owner group, ...)) atbilst failam, kuram ir izpildīšanas tiesības, ls -faila nosaukums, šis fails atrodas bin mapite)

- cd /bin -aizved uz sarakstu ar failiem ar izpildīšanas tiesībām, zaļā krāsās

- echo $0 - ar kādu bash vai citu shell lietotājs strādā.

- bash - pārslēdzas uz bash sh - pārslēdzas uz sh shell

- ls -l ls - var apskatīt šo ls failu, to var lasīt, rediģēt dzēst, apskatīt

- cat ls - var lasīt failu (cat izmanto tikai txt failu lasīšanai, ja izmamto izpildāmajiem failiem - nekas nesanāks) komanda, piemēram, ls -fails, ar instrukcijām, nevis txt fails.

- cd -aieziet uz home

- git clone https .... - nokopet repository uz sistēmas

- absolūta adrese - sākot ar / relatīva - ar $

- nano git-upload -atveram nano -teksta editors whereis nano - apskatīt komandas dokumentāciju un instrukcijām.

- #!/bin/bash -

- chmod- nomaina tiesības

- git pull -pirms taisa git push, ja githuba fails tiek editots.

- rm - rf README.rm

- history | grep clone

Piemērs ar emoji 😬
