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

## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.
