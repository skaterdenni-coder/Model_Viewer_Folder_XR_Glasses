📦 AR Model Viewer (Folder Mode)
Ein webbasierter 3D-Modell-Viewer, der es ermöglicht, ganze Ordner mit .glb-Dateien zu laden, sie im Browser zu betrachten und per Cloud-Link für Augmented Reality (AR) zu teilen.

✨ Features
Ordner-Upload: Lade einen kompletten lokalen Ordner hoch und wähle Modelle bequem über ein Dropdown-Menü aus.

Instant Preview: Modelle werden sofort lokal im Browser gerendert (via Google <model-viewer>).

Cloud Sharing: Automatischer Upload zu Litterbox (24h Speicher), um einen teilbaren Link und einen QR-Code zu generieren.

Augmented Reality (AR): Betrachte die Modelle direkt in deiner Umgebung (unterstützt WebXR, Scene-Viewer und Quick-Look).

Theme Toggle: Wechsel zwischen einem sauberen weißen Modus und einem eleganten Off-White (Creme) Design.

Responsive Design: Optimiert für Desktop und mobile Endgeräte.

🚀 Installation & Nutzung
Datei speichern: Speichere den Code als index.html.

Im Browser öffnen: Öffne die Datei einfach per Doppelklick in einem modernen Browser (Chrome, Edge oder Safari empfohlen).

Modelle laden:

Klicke auf das gestrichelte Upload-Feld.

Wähle einen Ordner auf deinem Computer aus, der .glb-Dateien enthält.

Bestätige die Browser-Abfrage zum Zugriff auf den Ordner.

Teilen: Sobald ein Modell ausgewählt ist, wird im Hintergrund ein Link generiert. Scanne den QR-Code mit deinem Smartphone, um das Modell in AR zu sehen.

🛠 Technische Details
Framework: Google Model Viewer

Bibliotheken: * qrcode.js für die Generierung von QR-Codes.

Litterbox API für den temporären Datei-Host (Dateien werden nach 24h gelöscht).

Sprachen: HTML5, CSS3 (CSS Variables für Themes), JavaScript (ES6+).

📋 Voraussetzungen
Dateiformat: Nur .glb (glTF Binary) wird unterstützt.

Internetverbindung: Erforderlich für das Laden der Skripte (CDN) und den Cloud-Upload.

AR-Support: Ein AR-fähiges Mobilgerät (Android mit ARCore oder iOS mit ARKit).

⚖️ Lizenz & Credits
Entwickelt von: Simba

Nutzung: Dieses Projekt ist für Testzwecke und Präsentationen optimiert. Beachte, dass hochgeladene Dateien über den Litterbox-Dienst öffentlich (via Link) zugänglich sind.
