Opis:
Oxidized to system zbierający backupy w formie textowej (exporty) z urządzeń i zapisuje je do bazy git.
Niniejszy plugin dodaje na karcie urządzenia sieciowego dodatkową belkę z odnosnikiem do strony oxidized z backupami zrobionymi dla danego urządzenia.

Instalacja wtyczki:
1. Zawartość paczki umieścić w katalogu plugins w LMS.
2. composer update --no-dev -n
3. Uaktywnić wtyczkę z poziomu interfejsu użytkownika LMS.

Konfiguracja wtyczki:
1. Jako adres dostępu do Oxidized wpisać url pod ktorym zainstalowany jest Oxidized w konfiguracji ui w oxidized.url

Grzegorz Cichowski <gc@ptlanet.pl>

PS: konfigurację oxidized i załadowanie go bazą urządzeń z LMS trzeba zrobić niezależnie od tego pluginu:
https://github.com/ytti/oxidized

