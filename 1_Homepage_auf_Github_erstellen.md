Im Folgenden findest du eine Schritt-für-Schritt-Anleitung, wie du ausschliesslich über die GitHub-Weboberfläche eine kostenlose Workshop-Seite mit Jekyll auf GitHub Pages erstellst. 

## 1. GitHub-Account erstellen oder anmelden

1. **GitHub-Account**:  
   - Besuche [github.com](https://github.com), klicke auf **Sign up** (falls du noch keinen Account hast) oder melde dich an (Sign in).  
2. **Profil**:  
   - Nach dem Login siehst du oben rechts dein Profilbild bzw. Avatar.

---

## 2. Neues Repository anlegen (mit Initial-Commit)

1. Klicke oben rechts auf das **Plus-Symbol** (**+**) und wähle **New repository**.  
2. **Repository-Name**:  
   - Wenn du möchtest, dass deine Seite unter `https://<dein_username>.github.io/` zu finden ist, **nennst du das Repository** genau `<dein_username>.github.io`.  
   - Ansonsten wähle einen beliebigen Namen (z. B. `workshop-material`). Dann erscheint deine Seite später unter `https://<dein_username>.github.io/<repo_name>`.  
3. **Description** (optional): Kurze Beschreibung wie “Workshop-Seite mit Jekyll und GitHub Pages”.  
4. **Public** auswählen, damit die Seite öffentlich zugreifbar ist.  
5. WICHTIG: **Haken bei “Add a README file”** setzen.  
6. Klicke auf **Create repository**.  

Dadurch hast du jetzt bereits **einen Branch (main)** mit mindestens einer Datei (`README.md`). Das ist notwendig, um GitHub Pages nachher aktivieren zu können.

---

## 3. Erste Dateien im Webfrontend anlegen

### 3.1 `_config.yml` (Jekyll-Konfiguration)

1. Im neuen Repository siehst du die Dateien-Liste (bislang nur `README.md`). Klicke auf **Add file** → **Create new file**.  
2. **Dateiname**: `_config.yml` (bitte genau so schreiben, Unterstrich am Anfang).  
3. **Inhalt** (Minimalbeispiel):
   ```yaml
   title: "Mein Workshop"
   description: "Materialien für meinen Workshop"
   theme: minima
   markdown: kramdown

   

