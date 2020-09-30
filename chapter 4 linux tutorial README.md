# csc221
Coursework for CSC221 Effective Programming

Have a skim through the man page for ls. Have a play with some of the command line options you find there. Make sure you play with a few as combinations. Also make sure you play with ls with both absolute and relative paths.
Now try doing a few searches through the man pages. Depending on your chosen terms you may get quite a large listing. Look at a few of the pages to get a feel for what they are like.

ls -a
 ./                   hw2/
 ../                  IntelGraphicsProfiles/
 .bash_history        Links/
 .git/               'Local Settings'@
 .gitconfig           MicrosoftEdgeBackups/
 .ipython/            Music/
 .pylint.d/          'My Documents'@
 .ssh/                NetHood@
 .viminfo             NTUSER.DAT
 .vscode/             ntuser.dat.LOG1
'3D Objects'/         ntuser.dat.LOG2
 AppData/             NTUSER.DAT{fd9a35db-49fe-11e9-aa2c-248a07783950}.TM.blf
 Apple/               NTUSER.DAT{fd9a35db-49fe-11e9-aa2c-248a07783950}.TMContainer00000000000000000001.regtrans-ms
'Application Data'@   NTUSER.DAT{fd9a35db-49fe-11e9-aa2c-248a07783950}.TMContainer00000000000000000002.regtrans-ms
 Contacts/            ntuser.ini
 Cookies@             OneDrive/
 courses/             PrintHood@
 csc121/              Recent@
 csc221/             'Saved Games'/
 csc321/              Searches/
 cs-classwork/        SendTo@
 Documents/          'Start Menu'@
 Downloads/           temp/
 emacs.tutor.txt/     Templates@
 emacstutor.txt/      Videos/
 Favorites/
 
  ls -all
total 10114
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 30 02:49  ./
drwxr-xr-x 1 Michael Bonds 197121       0 Dec 18  2019  ../
-rw-r--r-- 1 Michael Bonds 197121     780 Sep 25 09:13  .bash_history
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 25 21:34  .git/
-rw-r--r-- 1 Michael Bonds 197121     199 Aug 30 22:28  .gitconfig
drwxr-xr-x 1 Michael Bonds 197121       0 Aug 30 21:40  .ipython/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 17 20:13  .pylint.d/
drwxr-xr-x 1 Michael Bonds 197121       0 Jan 15  2020  .ssh/
-rw-r--r-- 1 Michael Bonds 197121   11910 Sep 14 09:04  .viminfo
drwxr-xr-x 1 Michael Bonds 197121       0 Jan 15  2020  .vscode/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 11 21:57 '3D Objects'/
drwxr-xr-x 1 Michael Bonds 197121       0 Dec 18  2019  AppData/
drwxr-xr-x 1 Michael Bonds 197121       0 Feb  8  2020  Apple/
lrwxrwxrwx 1 Michael Bonds 197121      38 Dec 18  2019 'Application Data' -> '/c/Users/Michael Bonds/AppData/Roaming'/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 11 21:57  Contacts/
lrwxrwxrwx 1 Michael Bonds 197121      66 Dec 18  2019  Cookies -> '/c/Users/Michael Bonds/AppData/Local/Microsoft/Windows/INetCookies'/
drwxr-xr-x 1 Michael Bonds 197121       0 Aug 30 22:08  courses/
drwxr-xr-x 1 Michael Bonds 197121       0 Apr 27 22:24  csc121/
drwxr-xr-x 1 Michael Bonds 197121       0 Aug 26 22:59  csc221/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 28 19:14  csc321/
drwxr-xr-x 1 Michael Bonds 197121       0 Jan 15  2020  cs-classwork/
drwxr-xr-x 1 Michael Bonds 197121       0 Apr 27 17:56  Documents/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 25 21:25  Downloads/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 25 09:48  emacs.tutor.txt/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 25 21:26  emacstutor.txt/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 11 21:57  Favorites/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 30 00:53  hw2/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 30 00:02  IntelGraphicsProfiles/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 11 21:57  Links/
lrwxrwxrwx 1 Michael Bonds 197121      36 Dec 18  2019 'Local Settings' -> '/c/Users/Michael Bonds/AppData/Local'/
drwxr-xr-x 1 Michael Bonds 197121       0 Dec 18  2019  MicrosoftEdgeBackups/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 11 21:57  Music/
lrwxrwxrwx 1 Michael Bonds 197121      32 Dec 18  2019 'My Documents' -> '/c/Users/Michael Bonds/Documents'/
lrwxrwxrwx 1 Michael Bonds 197121      74 Dec 18  2019  NetHood -> '/c/Users/Michael Bonds/AppData/Roaming/Microsoft/Windows/Network Shortcuts'/
-rw-r--r-- 1 Michael Bonds 197121 6029312 Sep 28 20:21  NTUSER.DAT
-rw-r--r-- 1 Michael Bonds 197121 1552384 Dec 18  2019  ntuser.dat.LOG1
-rw-r--r-- 1 Michael Bonds 197121 1552384 Dec 18  2019  ntuser.dat.LOG2
-rw-r--r-- 1 Michael Bonds 197121   65536 Dec 18  2019  NTUSER.DAT{fd9a35db-49fe-11e9-aa2c-248a07783950}.TM.blf
-rw-r--r-- 1 Michael Bonds 197121  524288 Dec 18  2019  NTUSER.DAT{fd9a35db-49fe-11e9-aa2c-248a07783950}.TMContainer00000000000000000001.regtrans-ms
-rw-r--r-- 1 Michael Bonds 197121  524288 Dec 18  2019  NTUSER.DAT{fd9a35db-49fe-11e9-aa2c-248a07783950}.TMContainer00000000000000000002.regtrans-ms
-rw-r--r-- 1 Michael Bonds 197121      20 Dec 18  2019  ntuser.ini
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 30 00:04  OneDrive/
lrwxrwxrwx 1 Michael Bonds 197121      74 Dec 18  2019  PrintHood -> '/c/Users/Michael Bonds/AppData/Roaming/Microsoft/Windows/Printer Shortcuts'/
lrwxrwxrwx 1 Michael Bonds 197121      63 Dec 18  2019  Recent -> '/c/Users/Michael Bonds/AppData/Roaming/Microsoft/Windows/Recent'/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 11 21:57 'Saved Games'/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 11 21:57  Searches/
lrwxrwxrwx 1 Michael Bonds 197121      63 Dec 18  2019  SendTo -> '/c/Users/Michael Bonds/AppData/Roaming/Microsoft/Windows/SendTo'/
lrwxrwxrwx 1 Michael Bonds 197121      67 Dec 18  2019 'Start Menu' -> '/c/Users/Michael Bonds/AppData/Roaming/Microsoft/Windows/Start Menu'/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 21 13:44  temp/
lrwxrwxrwx 1 Michael Bonds 197121      66 Dec 18  2019  Templates -> '/c/Users/Michael Bonds/AppData/Roaming/Microsoft/Windows/Templates'/
drwxr-xr-x 1 Michael Bonds 197121       0 Sep 11 21:57  Videos/

 ls -alh
total 9.9M
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 30 02:49  ./
drwxr-xr-x 1 Michael Bonds 197121    0 Dec 18  2019  ../
-rw-r--r-- 1 Michael Bonds 197121  780 Sep 25 09:13  .bash_history
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 25 21:34  .git/
-rw-r--r-- 1 Michael Bonds 197121  199 Aug 30 22:28  .gitconfig
drwxr-xr-x 1 Michael Bonds 197121    0 Aug 30 21:40  .ipython/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 17 20:13  .pylint.d/
drwxr-xr-x 1 Michael Bonds 197121    0 Jan 15  2020  .ssh/
-rw-r--r-- 1 Michael Bonds 197121  12K Sep 14 09:04  .viminfo
drwxr-xr-x 1 Michael Bonds 197121    0 Jan 15  2020  .vscode/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 11 21:57 '3D Objects'/
drwxr-xr-x 1 Michael Bonds 197121    0 Dec 18  2019  AppData/
drwxr-xr-x 1 Michael Bonds 197121    0 Feb  8  2020  Apple/
lrwxrwxrwx 1 Michael Bonds 197121   38 Dec 18  2019 'Application Data' -> '/c/Users/Michael Bonds/AppData/Roaming'/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 11 21:57  Contacts/
lrwxrwxrwx 1 Michael Bonds 197121   66 Dec 18  2019  Cookies -> '/c/Users/Michael Bonds/AppData/Local/Microsoft/Windows/INetCookies'/
drwxr-xr-x 1 Michael Bonds 197121    0 Aug 30 22:08  courses/
drwxr-xr-x 1 Michael Bonds 197121    0 Apr 27 22:24  csc121/
drwxr-xr-x 1 Michael Bonds 197121    0 Aug 26 22:59  csc221/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 28 19:14  csc321/
drwxr-xr-x 1 Michael Bonds 197121    0 Jan 15  2020  cs-classwork/
drwxr-xr-x 1 Michael Bonds 197121    0 Apr 27 17:56  Documents/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 25 21:25  Downloads/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 25 09:48  emacs.tutor.txt/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 25 21:26  emacstutor.txt/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 11 21:57  Favorites/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 30 00:53  hw2/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 30 00:02  IntelGraphicsProfiles/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 11 21:57  Links/
lrwxrwxrwx 1 Michael Bonds 197121   36 Dec 18  2019 'Local Settings' -> '/c/Users/Michael Bonds/AppData/Local'/
drwxr-xr-x 1 Michael Bonds 197121    0 Dec 18  2019  MicrosoftEdgeBackups/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 11 21:57  Music/
lrwxrwxrwx 1 Michael Bonds 197121   32 Dec 18  2019 'My Documents' -> '/c/Users/Michael Bonds/Documents'/
lrwxrwxrwx 1 Michael Bonds 197121   74 Dec 18  2019  NetHood -> '/c/Users/Michael Bonds/AppData/Roaming/Microsoft/Windows/Network Shortcuts'/
-rw-r--r-- 1 Michael Bonds 197121 5.8M Sep 28 20:21  NTUSER.DAT
-rw-r--r-- 1 Michael Bonds 197121 1.5M Dec 18  2019  ntuser.dat.LOG1
-rw-r--r-- 1 Michael Bonds 197121 1.5M Dec 18  2019  ntuser.dat.LOG2
-rw-r--r-- 1 Michael Bonds 197121  64K Dec 18  2019  NTUSER.DAT{fd9a35db-49fe-11e9-aa2c-248a07783950}.TM.blf
-rw-r--r-- 1 Michael Bonds 197121 512K Dec 18  2019  NTUSER.DAT{fd9a35db-49fe-11e9-aa2c-248a07783950}.TMContainer00000000000000000001.regtrans-ms
-rw-r--r-- 1 Michael Bonds 197121 512K Dec 18  2019  NTUSER.DAT{fd9a35db-49fe-11e9-aa2c-248a07783950}.TMContainer00000000000000000002.regtrans-ms
-rw-r--r-- 1 Michael Bonds 197121   20 Dec 18  2019  ntuser.ini
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 30 00:04  OneDrive/
lrwxrwxrwx 1 Michael Bonds 197121   74 Dec 18  2019  PrintHood -> '/c/Users/Michael Bonds/AppData/Roaming/Microsoft/Windows/Printer Shortcuts'/
lrwxrwxrwx 1 Michael Bonds 197121   63 Dec 18  2019  Recent -> '/c/Users/Michael Bonds/AppData/Roaming/Microsoft/Windows/Recent'/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 11 21:57 'Saved Games'/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 11 21:57  Searches/
lrwxrwxrwx 1 Michael Bonds 197121   63 Dec 18  2019  SendTo -> '/c/Users/Michael Bonds/AppData/Roaming/Microsoft/Windows/SendTo'/
lrwxrwxrwx 1 Michael Bonds 197121   67 Dec 18  2019 'Start Menu' -> '/c/Users/Michael Bonds/AppData/Roaming/Microsoft/Windows/Start Menu'/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 21 13:44  temp/
lrwxrwxrwx 1 Michael Bonds 197121   66 Dec 18  2019  Templates -> '/c/Users/Michael Bonds/AppData/Roaming/Microsoft/Windows/Templates'/
drwxr-xr-x 1 Michael Bonds 197121    0 Sep 11 21:57  Videos/
