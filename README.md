# medien

Öffentlich erreichbare Bilder und Videos für die Instagram-Veröffentlichung.

## Warum dieses Repository öffentlich ist

Instagram lädt die Medien beim Veröffentlichen **anonym**: es bekommt eine URL
und holt die Datei ohne jeden Zugang. Liegt sie in einem privaten Repository,
antwortet GitHub mit 404, und der Medien-Container scheitert mit `ERROR`.

Genau daran ist am 07.09.2026 die erste echte Veröffentlichung gestorben —
nicht am Token, der war gültig.

Deshalb liegen hier die fertig gerenderten Medien, und **nur** die. Sie stehen
ohnehin Minuten später öffentlich auf Instagram; es gibt an ihnen nichts zu
schützen.

## Was hier NICHT hineingehört

- Captions und Beitragstexte
- der Redaktionsplan (`schedule.json`, `veroeffentlicht.json`)
- die Stimmführung und die Markenblätter
- Code, Workflows, Secrets
- alles, was noch nicht veröffentlicht ist

Das bleibt in den privaten Repositories. Der Redaktionsplan enthält Beiträge,
die noch nicht erschienen sind — der gehört nicht hierher.

## Aufbau

```
shortheaven3/images/post-NN.jpg      Karussell-Slides
shortheaven3/videos/post-NN.mp4      Reels
denkbeleg/<slug>/01.jpg …            Slides je Beitrag
```

## Wer schreibt hier hinein

Niemand von Hand. Die Renderläufe der beiden privaten Repositories legen ihre
Ergebnisse nach jedem Lauf zusätzlich hier ab, mit dem Zugang
`GH_AUTOMATION_TOKEN`.

## Bildnachweise

Die Fotohintergründe stammen von [Pexels](https://www.pexels.com) unter deren
Lizenz. Der Nachweis je Bild steht im jeweiligen Quell-Repository neben der
Datei (`backgrounds/post-NN-M.quelle`).
