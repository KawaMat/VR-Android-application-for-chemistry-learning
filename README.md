# VR-Android-application-for-chemistry-learning

Celem było stworzenie aplikacji, która by obrazowała przebiegi reakcji chemicznych w zależności od równania reakcji, przy pomocy filmów wideo. Miałoby to uatrakcyjnić i ułatwić naukę chemii poprzez szybki i łatwy dostęp do zobrazowanych na filmach eksperymentów. Istnieje szereg reakcji o odmiennym przebiegu, na maturze czy egzaminach wymagany jest ich dokładny opis. Należy znać m.in. kolor i konsystencję produktu, wiedzieć czy reakcja przebiega gwałtownie czy powoli itp., zaproponowana przeze mnie aplikacja zdecydowanie ułatwiłaby naukę. 

Prace programistyczne zostały wykonane w środowisku Unity przy pomocy narzędzia rzeczywistości rozszerzonej o nazwie Vuforia. Praca ze wspomnianym narzędziem ułatwia implementację obiektów wirtualnych na rzeczywistym tle poprzez tworzenie bazy danych złożonej ze znaczników (targetów) i informacji o nich.

Dostęp do filmu uzyskuje się poprzez najechanie kamerą smartphone-a na równanie reakcji w podręczniku do nauki chemii, przy którym widnieje oznaczenie o możliwej interakcji. Dodatkowo po najechaniu kamerą na pojedynczy związek chemiczny biorący udział w reakcji, otrzymujemy dodatkowe informacje o nim.


Przeprowadzone testy pokazały skuteczne działanie aplikacji, spełniającej założone na wstępie cele. Targetami do rozpoznawania są wzory chemiczne co może stanowić problem w trakcie rozwijania aplikacji o dodatkowe związki chemiczne, ponieważ ich struktura może okazać się zbyt uproszczona.
