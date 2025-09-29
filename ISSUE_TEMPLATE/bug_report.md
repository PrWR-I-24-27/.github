name: Feature Request
description: Schlage eine Idee für dieses Projekt vor.
title: ": "
labels: enhancement
body:
  - type: markdown
    attributes:
      value: "Vielen Dank, dass du dir die Zeit nimmst, diesen Feature-Request auszufüllen!"
  - type: textarea
    id: problem-description
    attributes:
      label: "Welches Problem soll mit diesem Feature gelöst werden?"
      description: "Beschreibe das Problem oder den Anwendungsfall. Warum ist dieses Feature notwendig?"
      placeholder: "Als Benutzer möchte ich..."
    validations:
      required: true
  - type: textarea
    id: solution-description
    attributes:
      label: "Wie stellst du dir die Lösung vor?"
      description: "Beschreibe, wie das Feature deiner Meinung nach funktionieren sollte."
    validations:
      required: true
  - type: dropdown
    id: priority
    attributes:
      label: "Priorität"
      description: "Wie wichtig ist dieses Feature für dich?"
      options:
        - "Hoch"
        - "Mittel"
        - "Niedrig"
    validations:
      required: true
  - type: checkboxes
    id: confirmation
    attributes:
      label: "Bestätigung"
      options:
        - label: "Ich habe nach ähnlichen, bereits existierenden Feature-Requests gesucht."
          required: true