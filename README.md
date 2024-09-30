# Konfiguracja-Firewalli
To repozytorium zawiera trzy przewodniki dotyczące konfiguracji zapór sieciowych (firewalla) na różnych systemach operacyjnych: Linux (nftables i UFW) oraz Windows. Każdy z tych przewodników dostarcza szczegółowych informacji na temat tworzenia i zarządzania regułami bezpieczeństwa w celu ochrony systemów przed nieautoryzowanym dostępem i innymi zagrożeniami. Poniżej znajdziesz opis każdego z plików.

Pliki
Konfiguracja NFT firewall - Linux

Zawiera szczegółowy opis konfiguracji firewalla za pomocą nftables na systemie Linux. Instrukcje obejmują m.in. tworzenie tabel, łańcuchów oraz reguł filtrujących ruch sieciowy.
Przykłady konfiguracji obejmują zezwolenie na ruch dla SSH (port 22), HTTP (port 80), HTTPS (port 443), ochronę przed atakami brute-force oraz blokowanie złośliwych adresów IP.
Plik jest przeznaczony dla zaawansowanych użytkowników, którzy chcą stworzyć własne reguły bezpieczeństwa na poziomie sieci przy użyciu nftables.
Konfiguracja UFW firewall - Linux

Przewodnik po UFW (Uncomplicated Firewall) – uproszczonej nakładce na iptables dla systemów Linux, szczególnie Ubuntu.
Obejmuje podstawowe operacje, takie jak zezwalanie na ruch dla portów SSH, HTTP i HTTPS oraz ograniczanie dostępu do określonych usług.
Opisano również zaawansowane funkcje, takie jak limitowanie połączeń (SSH), blokowanie portów, zarządzanie regułami dla adresów IP i protokołów oraz monitorowanie logów.
Idealny dla użytkowników szukających prostszego rozwiązania w zarządzaniu zaporą sieciową.
Konfiguracja Windows firewall

Zawiera przewodnik dotyczący konfiguracji zapory sieciowej w systemie Windows z wykorzystaniem wbudowanego narzędzia Windows Firewall.
Opisuje proces tworzenia reguł dla programów, portów oraz protokołów, a także scenariusze blokowania nieautoryzowanego ruchu, w tym reagowanie na ataki typu ping, skanowania nmap oraz zarządzanie logami.
Odpowiedni dla użytkowników systemu Windows, którzy chcą dostosować reguły zabezpieczeń w swoich sieciach i aplikacjach.
Jak korzystać
nftables (Linux): Skonfiguruj zaawansowaną zaporę sieciową poprzez definiowanie szczegółowych reguł z poziomu terminala.
UFW (Linux): Skorzystaj z uproszczonego interfejsu do tworzenia i zarządzania regułami firewall w systemach Linux.
Windows Firewall: Dostosuj ochronę systemu Windows poprzez szczegółową konfigurację zapory z użyciem Windows Defender Firewall.
Każdy z przewodników zawiera przykłady praktycznych zastosowań oraz najlepsze praktyki w zabezpieczaniu systemów operacyjnych.
