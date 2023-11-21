#Praktikum9
1. Mitu protsessi? Linux- 188(ps -aux | wc -l); Windows- 223(Task Manager, Perforamance(kasutan isiklikku arvutit, mitte VM, sellest ka inglise keel))
   
3. Milline on kõige esimene protsess? Linux- /sbin/init splash(ps axo pid, cmd,comm,etime); Windows- ssms.exe(tasklist)

4. Kui kaua on arvuti järjest töötanud (up time)? Linux- 17min(uptime); Windows/ 14päeva 15tundi 23minutit(Task Manager, Performance)

5. Milline protsess käivitati kõige hiljem? Linux-[kworker /u4:2-events_unbound](ps aux) Windows- XtuService.exe(Task Manager, Details)

6. Milline on kõige rohkem protsessoriaega võttev protsess? Linux- /usr/bin/gnome-shell(htop) Windows- System Idle Process(Task Manager, Details, vajutan cpu peale, et sorteerida, see on kõige ülemine)

7. Milline on kõige rohkem virtuaalmälu võttev protsess? Linux- /lib/systemd/systemd --user(htop, F6 et sortida ja ss VIRT M) Windows- 

8. Milline on kõige rohkem füüsilist mälu võttev protsess? Linux- /usr/bin/gnome-shell(htop, f6, resident m)Windows- VirtualBoxVM.exe(Task Manager, Details, seekord vajutan Memory peale ja sorteerin niiviisi)

9. Kui palju füüsilisest mälust (Physical Memory) on vaba? Linux- 1,8GB(free -h) Windows- 6GB(Task Manager, Performance, Memory, Available)

10. Kui palju on põhikettal (C:, /) vaba ruumi mahult (GB) ja protsentuaalselt? - Linux: 11G, 51%(free -h)Windows: 332GB, ~70%(file explorer, this pc, valisin c ketta, properties)

11. Milline on kõige suurem kõvakettal olev fail ja kõige suurem alamkaust? Linux: Fail- /var/lib/snapd/snaps/gnome-42-2204_141.snap(find / -type f -exec du -h {} + | sort -rh | head -n 1); Kaust

Windows: Fail- {339e1538-d039-4f47-95a4-7352b7b44e03}.vdi(File Explorer, size:gigantic ja sealt sorteerisin suuruse järgi) Alamkaust- C:\VB(system, storage, other)

13.
Milline protsess kõige rohkem salvestusseadmele kirjutab?- System(Task Manager, Processes, Disk)
Millisesse faili eelmise küsimuse protsess kõige rohkem kirjutab?-?
Milline protsess kõige rohkem salvestusseadmelt loeb?- chrome
Millisest failist eelmise küsimuse protsess kõige rohkem loeb?-?

15. Avan Task Manageri. Vaatan esmalt CPU ja ss Memory tulpa. See on see mis ma teeks.
