# LB 324

## Aufgabe 2
# Installation Pre-commit
1. Installieren Sie die pre-commit python Pakete mit `pip install pre-commit`
```
pip install pre-commit
```
2. Um zu überprüfen, ob es installiert ist, gehen Sie in Ihr Terminal und verwenden Sie `pre-commit --version`
```
pre-commit --version
```
3. Nach der Installation gehen Sie mit dem Terminal zu Ihrem Wurzelverzeichnis des Projekts und verwenden `pre-commit install`.
```
cd "your project path*
pre-commit install
```
4. Nun können gewünschte Änderungen am Code vorgenommen werden, wobei jetzt beim Commiten und Pushen automatisch Vorkehrungen getroffen werden. Sie können überprüfen, ob alle Dataeien in Ordnung sind mit `pre-commit run --all-files`
```
pre-commit run --all-files
```
## Notice!
Wenn pre-commit installiert ist, aber der Modul nicht gefunden werden kann:
Öffnen die Umgebungsvariable und fügen Sie den Pfad hinzu, in dem pre-commit installiert ist

## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.

### Website
https://studer-diary.azurewebsites.net/

Öffnen Sie Azure und gehe Sie im Navigationsverzeichnis auf `Konfiguration`/`Configuration`.

![image](https://github.com/Rosidvas/StuderRandonLB-324/assets/89085444/5ea77d9c-96b5-432f-a3d3-f0cc96af4551)

Nehmen Sie eine neue Anwendungseinstellung vor und legen Sie das Passwort fest.
![image](https://github.com/Rosidvas/StuderRandonLB-324/assets/89085444/b5541fe0-b41c-4d1c-92fd-18dda35d1651)
![image](https://github.com/Rosidvas/StuderRandonLB-324/assets/89085444/b99860f0-68be-4d64-afc0-cf66fae4c451)

Sobald Sie auf die Website geladen sind, können Sie auf das Tagebuch zugreifen
![image](https://github.com/Rosidvas/StuderRandonLB-324/assets/89085444/3a683b3c-0c55-4fba-97da-bdd1f6cae78e)

![image](https://github.com/Rosidvas/StuderRandonLB-324/assets/89085444/3d07f7d0-a1ea-4403-b62d-46cce47005a5)

