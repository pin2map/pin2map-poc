# pin2map UI-PoC – Arbeitsanweisung

> [!IMPORTANT]
> **ABGRENZUNG ZU pin2map NEW (10.11.2026):** Dieses Repository ist der frühere UI-Prototyp und bleibt **Design-/Verhaltensreferenz**, nicht die aktive Codebasis der neuen modularen Anwendung. Für neue pin2map-NEW-Aufträge gelten [Projektwegweiser](https://github.com/pin2map/pin2map-new-test/blob/feature/leaflet-modular-core/docs/PROJEKTWEGWEISER.md) und [aktuelle Arbeitsanweisung](https://github.com/pin2map/pin2map-new-test/blob/feature/leaflet-modular-core/AGENTS.md). Nachfolgende PoC-spezifische Anweisungen gelten nur, wenn ausdrücklich Arbeiten **am PoC selbst** beauftragt werden. Keine Änderungen am PoC als Änderung der aktuellen NEW-Preview ausgeben.


Dies ist ausschließlich die **öffentliche, auf dem iPhone testbare PoC-Webseite**: https://pin2map.github.io/pin2map-poc/

- Aktuelle Oberfläche: `index.html` auf `main`; GitHub Pages veröffentlicht sie.
- **Verbindliche, private Planung und der aktuelle UI-Übergabestand liegen in einem anderen Repository:** `pin2map/pin2map-2/docs/POC_HANDOFF.md` und `docs/PROJECT_STATE.md`. Bei jedem PoC-Änderungswunsch diese privaten Unterlagen zuerst lesen, wenn Zugriff besteht.
- Änderungen in `index.html` umsetzen und hier committen. **Im selben Arbeitsgang und ohne weitere Nutzeraufforderung** die Änderung, Motivation, Commit-SHA, möglichen Testbedarf sowie neuen Stand in `pin2map/pin2map-2/docs/POC_HANDOFF.md` committen.
- Die GitHub-Commit-Historie erfasst Änderungen automatisch; das private, erklärende Übergabeprotokoll wird nicht automatisch von GitHub geschrieben, sondern muss als Arbeitsroutine aktualisiert werden. Der Assistent soll dies eigenständig ausführen.
- Kein privates Dokument, Login-/Backend-Geheimnis oder sonstiges sensibles Material in diese öffentliche Website übernehmen. Die Ursprungsanwendung in `pin2map/pin2map` nicht verändern.
- iPhone zuerst, Darstellung auf anderen Displays ähnlich, **alle runden Buttons immer perfekte Kreise**. Sync-/Anmelde-Symbole im PoC sind vorläufige Demos; keine echte Synchronisierung vortäuschen. Fotos nicht geplant.
