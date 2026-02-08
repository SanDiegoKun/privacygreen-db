name: "💼 Lizenzanfrage"
description: "Schreibe uns deine Anfrage – wir antworten innerhalb von 48 Stunden."
title: "[Lizenz] "
labels: ["lizenz", "privat"]
body:
  - type: markdown
    attributes:
      value: |
        **Deine Anfrage ist nur für dich und uns sichtbar.**
        Beschreibe einfach, was du vorhast – wir melden uns mit einem Angebot.
  - type: textarea
    id: anfrage
    attributes:
      label: "Deine Anfrage"
      description: "Freitext – keine Vorgaben."
    validations:
      required: true
