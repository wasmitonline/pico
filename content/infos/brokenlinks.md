---

Title: Wie man bei Änderungen an Webseiten tote Links vermeidet
Description: Umbenannte und verschobene Internetseiten sind ein echtes Ärgernis – nämlich dann, wenn die alten Adressen nicht umbenannt werden und User im Nichts landen. Wie es besser geht, beschreiben wir hier.
Author: Titus Gast
Date: 2024-10-13

---

# Wie man bei Änderungen an Webseiten tote Links vermeidet

Wenn Sie Ihre Website mit Hilfe eines Content-Management-Systems (CMS) verwalten, sind Änderungen wie das Umbenennen, Verschieben oder Löschen von Seiten oder Beiträgen denkbar einfach. Häufig wird dann in der täglichen Arbeit vergessen, dass vielleicht noch andere Webseiten, Suchmaschineneinträge oder Lesezeichen einzelner Nutzer auf diese Seite verweisen. 

Bekommt ihre Webseite einen neuen Namen, bekommt sie häufig automatisch vom CMS eine neue Adresse (und das gilt für jede Unterseite). Diese ist den Suchmaschinen, externen Webseiten oder Nutzer erst mal unbekannt. Sie kennen nur die alte Adresse – die aber mit der Umbenennung nicht mehr existiert.

## Broken Links vermeiden

Das führt dann zu sogenannten *Broken Links* (auch: „tote Links“). Diese Toten Links sind Verknüpfungen, die auf nicht mehr existierende Seiten führen und für die Benutzer und Suchmaschinen gleichermaßen problematisch sind. Sie sollten solche Verweise, die ins Nichts führen, unbedingt vermeiden.

Grundsätzlich gilt: Jede strukturelle Änderung an einer Website ist ein kleines Relaunch-Projekt und sollte auch strategisch geplant werden. Sie sollten also vorher analysieren: Welche Verlinkungen verweisen auf meine alte Seite, wie bekomme ich diese am besten auf die neue Seite umgeleitet. 

## Im Zweifel: Webmaster fragen

Die gute Nachricht ist: Webseiten lassen sich umleiten. Die schlechte Nachricht ist: Das passiert nicht automatisch und muss häufig im Webserver eingestellt werden – dafür müssen Sie sich dann i.d.R. an Ihren Webmaster wenden. 

## Allgemeine Grundsätze zum Vermeiden von Broken Links

Unabhängig vom verwendeten CMS sollten die folgenden Punkte immer beachtet werden, um tote Links zu vermeiden:

1. **Verlinkung vor Änderungen überprüfen:** Bevor eine Seite oder ein Beitrag gelöscht oder verschoben wird, sollte man prüfen, ob andere Inhalte darauf verlinken.
2. **Weiterleitungen einrichten:** Wenn URLs (also die Adresse einer Seite) geändert werden, sollte immer eine 301-Weiterleitung von der alten auf die neue URL eingerichtet werden. Diese sorgt dafür, dass Nutzer und Suchmaschinen die richtige Seite finden.
3. **Broken-Link-Checker nutzen:** Es gibt zahlreiche Tools, die tote Links auf einer Website identifizieren. Diese sollten regelmäßig genutzt werden.
4. **Sorgfältige Namensgebung:** Es ist wichtig, URLs so gut wie möglich von Anfang an festzulegen, damit spätere Änderungen minimiert werden.
5. **Immer wieder prüfen:** Durch das Auswerten von Fehlermeldungen und die Verwendung entsprechender Funktionen in Ihrem CMS können Sie sehen, ob und ggf. mit welchem Ziel ihre Nutzer auf Fehlerseiten gelandet sind – und so auch nachträglich noch Umleitugen auf die richtige Seite einbauen. 

Besonders wichtig ist in diesem Zusammenhang: Broken Links führen nicht nur zu schlechtem Suchmaschinen-Rankung und Fehlermeldungen, sondern zu Frust bei Nutzern; diese kommen dann im Zweifel überhaupt nicht auf Ihrer Website an oder brechen den Besuch entnervt ab, weil sie die gewünschte Information nicht direkt finden. 

## Anleitungen für einzelne CMS

Im Folgenden einige Hinweise zu weit verbreiteten Content-Management-Systemen:

- WordPress
- TYPO3
- Joomla
- Drupal

### 1. WordPress

WordPress ist das am weitesten verbreitete CMS und verfügt über zahlreiche Plugins, die beim Vermeiden toter Links hilfreich sind.

#### Vorgehensweise in WordPress:

1. **Permalink-Struktur beachten:** In den WordPress-Einstellungen kann die Permalink-Struktur der Seite festgelegt werden. Diese sollte so gewählt werden, dass URLs stabil bleiben und Änderungen minimiert werden.
2. **Änderung von URLs oder Slugs:** Wenn der "Slug" (der Teil der URL, der nach der Domain kommt) einer Seite oder eines Beitrags geändert wird, passt WordPress die Verlinkungen innerhalb des CMS nicht automatisch an. Eine manuelle Prüfung der internen Verlinkungen ist daher notwendig.
3. **301-Weiterleitungen einrichten:** Plugins wie „Redirection“ oder „Yoast SEO“ erleichtern das Einrichten von 301-Weiterleitungen bei URL-Änderungen. Sobald ein Beitrag oder eine Seite verschoben oder gelöscht wird, kann hier direkt eine Weiterleitung eingerichtet werden.
4. **Plugins für Broken-Link-Checks:** Es gibt spezielle Plugins wie „Broken Link Checker“, die regelmäßig alle internen und externen Links überprüfen und tote Links melden.

#### Tipp:

Vermeiden Sie das willkürliche Löschen von Seiten oder Beiträgen ohne Weiterleitung. Selbst wenn der Inhalt nicht mehr relevant ist, kann er auf eine ähnliche oder allgemeine Seite weitergeleitet werden, um den Besucher nicht ins Leere laufen zu lassen.

### 2. TYPO3

TYPO3 ist ein sehr flexibles, aber auch komplexes CMS, das oft in größeren Projekten zum Einsatz kommt.

#### Vorgehensweise in TYPO3:

1. **RealURL oder TYPO3 SEO nutzen:** TYPO3 verwendet oft Erweiterungen wie RealURL oder SEO-Router, um „sprechende URLs“ zu erstellen. Diese URL-Struktur sollte von Beginn an gut geplant sein, um spätere Änderungen zu minimieren.
2. **Manuelle Link-Pflege:** Wenn Seiten in TYPO3 umbenannt oder verschoben werden, passt das System interne Verlinkungen nicht automatisch an. Verlinkte Inhalte müssen daher manuell überprüft und angepasst werden.
3. **Weiterleitungen in TYPO3:** TYPO3 verfügt über ein eingebautes Weiterleitungssystem (Redirects). Mit der TYPO3-Weiterleitungsverwaltung können 301-Weiterleitungen einfach erstellt werden. Beim Löschen oder Ändern von Seiten sollte dies immer genutzt werden.
4. **Externe Erweiterungen:** Es gibt Erweiterungen wie „Linkvalidator“, die TYPO3-Administratoren dabei unterstützen, gebrochene Links in der Website zu finden und zu korrigieren.

#### Tipp:

Die Verwendung von Caching und Optimierungstools in TYPO3 kann manchmal das Auffinden von toten Links erschweren. Es ist wichtig, regelmäßig den Cache zu leeren und die Website auf aktuelle Verlinkungen hin zu überprüfen.

### 3. Joomla

Joomla ist ein weiteres populäres CMS, das oft für kleine bis mittelgroße Websites verwendet wird. Es bietet eine gute Balance zwischen Flexibilität und Benutzerfreundlichkeit.

#### Vorgehensweise in Joomla:

1. **Suchmaschinenfreundliche URLs (SEF) aktivieren:** Joomla erlaubt das Aktivieren von „Suchmaschinenfreundlichen URLs“ in den globalen Einstellungen. Diese sollten von Anfang an eingeschaltet werden, um stabile URLs zu gewährleisten.
2. **Änderungen an URLs:** Joomla aktualisiert interne Links nicht automatisch, wenn Seiten verschoben oder umbenannt werden. Daher ist es wichtig, alle Seitenverlinkungen manuell zu prüfen und anzupassen.
3. **301-Weiterleitungen in Joomla:** In Joomla gibt es eine eingebaute Redirect-Komponente. Damit können Weiterleitungen erstellt werden, wenn eine URL sich ändert oder eine Seite gelöscht wird. Dies sollte bei jeder URL-Änderung genutzt werden.
4. **Erweiterungen für Link-Prüfungen:** Es gibt Erweiterungen wie „Broken Links Checker“, die Joomla-Nutzern helfen, tote Links auf der Website zu finden und zu korrigieren.

#### Tipp:

In Joomla ist es wichtig, regelmäßig die „Redirect-Komponente“ zu überprüfen, da sie automatisch fehlerhafte Zugriffe protokolliert. Dies erleichtert die Verwaltung von Weiterleitungen.

### 4. Drupal

Drupal ist besonders bei größeren, komplexen Websites beliebt, da es hohe Flexibilität und Skalierbarkeit bietet.

#### Vorgehensweise in Drupal:

1. **URL-Aliase:** In Drupal können URL-Aliase verwendet werden, um benutzerfreundliche URLs zu erstellen. Diese Aliase sollten stabil und gut durchdacht sein, um spätere Änderungen zu vermeiden.
2. **Änderungen an URLs:** Drupal aktualisiert Verlinkungen intern nicht automatisch, wenn URL-Aliase geändert werden. Alle Links müssen manuell überprüft werden.
3. **301-Weiterleitungen in Drupal:** Das Modul „Redirect“ ermöglicht es, 301-Weiterleitungen zu erstellen. Diese sollten bei jeder Änderung einer URL verwendet werden, um sicherzustellen, dass keine toten Links entstehen.
4. **Link-Check-Module:** In Drupal gibt es Module wie „Link Checker“, die helfen, tote Links zu finden und zu korrigieren. Diese Module sollten regelmäßig verwendet werden, um die Seite aktuell zu halten.

#### Tipp:

Da Drupal oft für umfangreiche Webseiten verwendet wird, sollte bei größeren Änderungen an der Seitenstruktur immer eine gründliche Planung erfolgen.

*Erstellt mit Hilfe von ChatGPT*