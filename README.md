# verein.4830.org

In diesem Repository liegen die Webseiten des vereins. Sie werden mit Hugo als statische Webseite bereitgestellt.

## Webseite erstellen

Der Prozess zum erstellen der Webseite ist automatisiert, so weit es geht.

### Lokal

Der devcontainer ruft beim Starten das *install_theme_geeksblog.sh*. Die Webseite kann lokal erstellt werden, indem ```hugo server``` aufgerufen wird. Die Option *-d* berücksichtigt auch Seiten die noch als Draft markiert sind.

### GitHub Actions

Das Theme muss in Steps installiert werden.

## Theme

Das aktuell genutzt Theme wird nicht über ein GitHub submodule hinzugeügt, da es noch kompiliert werden müsste. Deshalb muss es heruntergeladen und entpackt werden.

> Das Theme wird nicht im Repository eingecheckt.

## Links

- [Hugo](https://gohugo.io)
- [Hugo Geekblog Theme](https://github.com/thegeeklab/hugo-geekblog)
