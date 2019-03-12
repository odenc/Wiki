# Troubleshooting

## **Als erstes**

Sei dir sicher, dass du die [Erweiterung](../installation/extension.md) **und** das [Programm](../installation/application.md) installiert hast!  
Du kannst die Schritte auch in einer anderen Reihenfolge ausprobieren.

## Discord zeigt die Präsenz nicht an

### Sei dir sicher, dass Discord NICHT als Administrator ausgeführt wird

Wirklich wichtig. Discord RPC wird nicht funktionieren, wenn du Discord als Administrator ausführst.

### Stelle sicher, dass du die neueste Version von PreMiD hast

Du kannst das prüfen, idem du auf **'Auf Updates überprüfen'** auf dem Premid-Symbol in deiner Taskbar klickst.  
Andernfalls wird dich das Programm benachrichtigen, wenn ein Update verfügbar ist.  
Und mach dir keine Sorgen um die Erweiterung - Die aktualisiert sich automatisch.

{% hint style="info" %}
Dev-Versionen und self-injected Versionen werden nicht automatisch aktualisiert.
{% endhint %}

![Windows Taskbar](https://github.com/PreMiD/PreMiD/raw/master/wiki/assets/CheckForUpdates.png)

### Stelle sicher, dass du Discord RPC in den Einstellungen aktiviert hast

![Discord Game Activity](https://github.com/PreMiD/PreMiD/raw/master/wiki/assets/GameActivity.png)

### Lase die Seite neu

Du kannst auch **Strg+R**/**F5** oder **CMD+R** auf deiner Tastatur drücken, befor du nach dem "Neu Laden"-Button suchst.

### Starte dein Browser neu

**Alt+F4** macht auch seinen Job. \(Du musst offensichtlich danach deinen Browser neustarten\)

### Deaktiviere deine Add-Ons

Deaktiviere alle deine Add-Ons und schaue, ob es wieder funktioniert.  
Wenn ja, versuche deine Add-Ons nach und nach zu deaktivieren und erzähle uns welches Add-On PreMiD unfunktionell gemacht hat.

### PreMiD neustarten \(App\)

![Windows Taskbar](https://github.com/PreMiD/PreMiD/raw/master/wiki/assets/Quit.png)

du musst danach PreMiD neu starten.

### Discord neuladen/neustarten 

Press **Strg+R** or **CMD+R** on you keyboard or restart Discord manually.

### Deinen Computer neustarten

Ich hoffe du weißt, wie man einen Computer neustartet.

### PreMiD neuinstallieren

Manchmal ist etwas mit den Dateien schiefgelaufen... Installationstutorials können [hier](../installation/application.md) gefunden werden.

### Manuelle Entfernung

{% tabs %}
{% tab title="Windows" %}
1. Gehe zu `C:\Users\USER\AppData\Local` und lösche Ordner`premid`
2. Gehe zu `C:\Users\USER\AppData\Roaming`und lösche Ordner`PreMiD`
{% endtab %}

{% tab title="Mac OS" %}
Gehe zu `YOURDISK:/users/USER/~Library/Application Support` und lösche Ordner`PreMiD`
{% endtab %}
{% endtabs %}

Makiere ein Teammitglied auf unserem [Discord-Server](https://discord.gg/WvfVZ8T), wenn keine dieser Schritte geholfen haben.

## Das hat mein Problem nicht gelöst

Du kannst:

* [Ein Ticket](https://github.com/PreMiD/PreMiD/issues/new/choose) auf [GitHub](https://github.com/PreMiD/PreMiD) eröffnen
* Ein Teammitglied in [\#support](https://discord.gg/WvfVZ8T) fragen

