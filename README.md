<img src=./logo.png><br/>

Siemaneczko. Miło mi w końcu zaprezentować modpack **SUDO Vanilla+**. Paczka modów, która pojawiała się i znikała na przestrzeni ostatnich kilku lat w końcu została uporządkowana, przetestowana i przygotowana jako (prawie) plug & play.

Paczka została przygotowana według mojego personalnego gustu. Jest pełna bajerów, fajnych animacji, nowych efektów (mocno inspirowanych modem _actions & stuff_) oraz optymalizacji, ale jednocześnie pozostaje wierna oryginalnemu stylowi minecrafta. Dokładna lista modów znajduje się [tutaj](./lists/modlist.md), a resource-packów [tutaj](./lists/resourcepacks.md).

**SUDO V+** jest w pełni **client-sided** tj. nie potrzebuje żadnych instalacji po stronie serwera. Możecie jej używać zarówno w światach singleplayer jak i waniliowych serwerach multiplayer. Jest to też dobra baza do budowania własnych paczek. Porady dotyczące modyfikacji i wprowadzania zmian w paczce znajdują się poniżej.

## Set-up

### Launcher

Jeżeli korzystasz z domyślnego launchera od microsoftu, to przestań. Jest on przestarzały i pełen śmieci, a instalacja modów i modpacków jest mega niewygodna.

Te launchery są wspierane przez paczkę:

- [Prism Launcher](https://prismlauncher.org/) - mój personal choice
- [CurseForge](https://www.curseforge.com/download/app)
- [Modrinth](https://modrinth.com/app)

### Instalacja paczki

1. Pobierz [release paczki](https://github.com/tymek-gryszkalis/sudo-vanilla-plus/releases) odpowiedni dla twojego launchera.
2. Włącz launcher i wybierz opcję dodania nowej instacji.
3. Wybierz opcję importowania paczki z pliku.

I gotowe, możesz grać :)

Jeżeli chcesz zaktualizować paczkę, pamiętaj że nowo pobrany release nie ma zapisanych światów ani serwerów. Jeżeli nazwa pliku jest taka sama jak instancji Prism pozwala na aktualizację jej z zachowaniem światów i serwerów. Nie jestem niestety pewien jak to jest w przypadku innych launcherów.

## Modyfikacja

Paczka jest przygotowana tak żeby nie trzeba było nic w niej grzebać, ale jednocześnie wszystkie mody i prawie wszystkie resource-packi są niezależne od siebie, więc w zależności od preferencji można je edytować, włączać i wyłączać. Poniżej parę sugestii czemu warto się przyjrzeć.

### Mody

- **Controllable** - jeżeli korzystasz z pada, to koniecznie tam zajrzyj i zmodyfikuj ustawienia pod swój kontroler. Domyślnie jest on ustawiony pod pad XBOX.
- **Distant Horizons** - jeżeli gra się tnie to jednym z rozwiązań może być zmniejszenie ilości renderowanych chunków.
- **Show Me Your Skin** - pozwala na ustawienie widoczności zbroi, peleryn i elytry na graczach. Dobra opcja jeżeli chcemy oglądać śliczne skiny znajomych.
- **Subtle Effects** - bardzo duży pakiet efektów i nowych cząsteczek. Polecam zajrzeć i sprawdzić które nam się podobają, a które nie.

### Resourcepacki

- **Vanilla Tweaks** - ogromny zestaw małych i niemałych zmian do gry. Ponadto jeden z modów pozwala na edytowanie paczki z poziomu gry. Zaaplikowałem niektóre zmiany, ale polecam chociaż przejrzeć paczkę.
  - Nie zmieniaj widoku zbroi, ponieważ zajmuje się tym już mod _Detail Armor Bar_.
  - Jeśli chcesz zmienić czcionkę, to wyłącz resourcepack _Compact Font_.
  - W ogóle przed edycją _Vanilla Tweaks_ zwróć uwagę na resourcepacki, czy któryś już nie zajmuje się rzeczą, którą chcesz ustawić.
- **ClientSort Dark Mode** - wyłacz jeżeli w _Vanilla Tweaks_ wyłączyłxś ciemne GUI

### Shadery

Do paczki dodałem [shadery BSL](https://modrinth.com/shader/bsl-shaders/version/10.0) z paroma personalnymi zmianami. Są one całkiem ładne i są kompatybilne z Distant Horizons. Są one jednak wymagające dla komputera, więc jeśli gra źle chodzi to można spokojnie zmienić ustawienia, albo w ogóle je wyłączyć.
