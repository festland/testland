# Development von Lokal

## Lokale Entwicklungsumgebung

Jeder Entwickler hat die Entwicklungsumgebung lokal auf seinem Gerät und nicht auf einem Testserver, auf dem alle gleichzeitig arbeiten.

###Vorteile:

* Fehler eines Entwicklers beeinträchtigen die anderen Entwickler nicht, z.B. Javascript/PHP Fehler, der die Website kaputt macht. So kann man ausprobieren, ohne die Anderen zu stören.
* Jeder kann seinen eigenen Code mit Git versionieren. Somit weiss man immer, wer welchen Code zu welcher Zeit zum Projekt beigesteuert hat.
* Man überschreibt sich nicht gegenseitig Code, wenn man zufällig am gleichen File arbeitet. 

###Nachteile:
* Jeder Entwickler muss in der Lage sein, auf seinem Gerät die Entwicklungsumgebung laufen zu lassen (Ehrensache ;)).

## Entwicklungsumgebung aufsetzen

Tools, die man haben sollte:

* Terminal oder iTerm
* XCode (immer schön die neuste Version installieren). Auf OS 10.9 einfach mal `gcc` in einem Terminal Fenster eintippen. Ist dieses Programm nicht installiert, fragt OSX nach, ob die XCode Developer Tools installiert werden sollten. Mit `xcode-select -p` kann man danach prüfen, ob es geklappt hat. Es sollte der Installationspfad ausgegeben werden, z.B. `/Library/Developer/CommandLineTools`
* Homebrew, ein Packetmanager für OS X: http://brew.sh
* Git, Version > 1.8 ist relativ aktuell: `git --version`
* Ruby, Version > 2.0 ist relativ aktuell: `ruby -v`
* Rubygems, Hosting für sämtliche Ruby Programme, sogenannte "gems": `gem -v`
* Bundler, installiert "gems" pro Projektordner in der gewünschten Version  : `sudo gem install bundler`, `bundle -v`

###SSH Setup
Anleitung:
https://help.github.com/articles/generating-ssh-keys
