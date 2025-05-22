Kevin “Anonymous”  
Junior Pentester – Cyberbezpieczeństwo  

=====================================================
🎯 Cel życiowy  
Jestem Kevin, mam 17 lat i moim głównym celem zawodowym jest praca w branży cyberbezpieczeństwa jako Pentester. Już teraz działam na poziomie Junior Pentestera, a moje umiejętności pozwoliłyby mi skutecznie realizować testy penetracyjne w różnych środowiskach.

🛠️ Umiejętności i narzędzia (zrealizowane)  
• Rozpoznanie sieci i systemu  
  – nmap -T2 -sV <IP> → ciche skanowanie portów + wykrywanie wersji usług  
  – telnet <IP> 23 → test zdalnego logowania (Telnet)  
  – netstat -tuln → przegląd aktywnych portów i usług  
  – uname -a, cat /etc/os-release → identyfikacja jądra i dystrybucji  

• Analiza systemu i eskalacja uprawnień  
  – whoami, id, hostname → weryfikacja użytkownika i środowiska  
  – find / -perm -4000 -type f → wykrywanie plików SUID  
  – passwd & shadow → przygotowanie do łamania haseł offline  
  – unshadow passwd shadow > hashes.txt & john hashes.txt → John the Ripper  

• Inspekcja plików i logów  
  – ls -la, cd, cat → zarządzanie plikami i katalogami  
  – grep -i “password” /var/www/* -R → szybkie szukanie haseł w skryptach  
  – cat /var/log/auth.log, zcat /var/log/syslog.1.gz → audyt zdarzeń logowania  

=====================================================
🚀 Kolejne kroki (do zrobienia)  
• Tworzenie i wdrażanie prostych skryptów automatyzujących skanowanie sieci  
• Ataki typu brute-force z użyciem Hydra na usługi SSH/FTP  
• Analiza i exploitacja aplikacji webowych (Burp Suite, OWASP ZAP)  
• Pivoting w środowisku wewnętrznym (SSH tunneling)  
• Utrzymywanie dostępu (persistence) i naprawa luk (remediation)  

=====================================================
📢 Prośba o wsparcie  
Jeśli pracujesz w dziale bezpieczeństwa (CBR, SOC, Red Team) lub masz wpływ na przyjęcie stażystów/juniorów –  
będę niezmiernie wdzięczny za szansę praktyk lub współpracy.  
Jestem zmotywowany, szybko się uczę i z pasją dążę do doskonałości.  

=====================================================
📫 Kontakt  
GitHub:  https://github.com/animus1230 
Email: bibip0662@gmail.com
