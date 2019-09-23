# Installation
 * Es empfiehlt sich die Linux-Distributionen in Virtual-Machines (Virtual Box, VM-Ware) zu testen, bevor eine echte Installation durchgeführt wird.
 * Für den Wechsel von Windows auf Linux empfiehlt es sich eine neue Festplatte zu verwenden, um im Fall der Fälle auf das alte System wechseln zu können

# Einige Linux Befehle
 Cheat Sheet: [https://files.fosswire.com/2007/08/fwunixref.pdf](https://files.fosswire.com/2007/08/fwunixref.pdf)
 
 Einige Befehle: ls, cd, rm, cp, mv, ln, ps aux, kill pid, chmod, dmesg, apt-get
 
# GUI-Tools
 * GParted
 * Software (Aptitude)
 
# Shell Scripts
  ```
  vi restartnetwork.sh
  ```
  
  Inhalt der Datei:
  ```
  #!/bin/bash
  service network-manager restart
  ```
  
  Rechte zum Ausführen der Datei erteilen:
  ```
  chmod +x 
  ```
  
  Siehe [https://www.shellbefehle.de/befehle/chmod/](https://www.shellbefehle.de/befehle/chmod/)


# Cron-Tabs
  [https://www.linuxwiki.de/crontab](https://www.linuxwiki.de/crontab)
  
  [https://crontab-generator.org/](https://crontab-generator.org)
  
  crontab -e
  
  m  h  dom  mon  dow  command

# Sonstiges

  /etc/fstab
  
