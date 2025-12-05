---
name: Fehler
about: Es gibt Verhalten, das so nicht stattfinden soll.
title: 'Nightshade crits'
labels: Fehler
assignees: JaredBeluzi

---

**Beschreibung**
Es gibt critical hits beim move Nightshade.

**Reproduzierbarkeit**
1. Hab Dusclops im Team mit dem Move Nightshade
2. Benutze Nightshade mehrfach im Kampf

**Erwartung**
Es sollte nie einen crit geben, da der Move einen festen Damagewert hat.

**Realität**
Es gibt critical hits.

**Screenshots**
Falls möglich, gib einen Screenshot an, der den Fehler zeigt.

**Vermutungen / Zusatzinfos**
Es kann sein, dass die crits durch die Gen 9 (?) Einstellung kommen, dass Pokemon, die dich mögen besondere Buffs bekommen. Dadurch kann ein Pokemon z.B. sonst tötlichen Schaden mit einem HP überleben oder es beseitigt selbst einen Statuseffekt. Das erhöht eventuell auch die crit chance und gibt auch moves critical hits, bei denen das eigentlich nicht möglich sein sollte.

**TODO**
- [ ] reproduziere Fehler
- [ ] überprüfe ab wann Pokemon wegen Freundlichkeit Buffs bekommen
- [ ] finde den Code und teste, ob dieser ohne diese Buffs immer noch auftaucht