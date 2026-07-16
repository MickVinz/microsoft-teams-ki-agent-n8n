# Microsoft Teams KI-Agent (n8n Workflow)

DSGVO-konformer n8n-Workflow für einen KI-Agenten in Microsoft Teams, mit Claude als LLM.

## Inhalt

- `Microsoft-KI-Agent (1).json` – n8n-Workflow-Export, importierbar in n8n
- `DSGVO-konforme_Automatisierung_mit_KI-Agenten.png` – Übersicht des Workflows
- `Screenshot 2026-07-16 123625.png` – Screenshot
- `KI-Agenten im Unternehmen_ So baust du eine DSGVO-konforme Lösung mit Microsoft und n8n.pdf` – Begleitartikel

## Übersicht

![Workflow-Übersicht](DSGVO-konforme_Automatisierung_mit_KI-Agenten.png)

## Screenshots

![Screenshot 1](Screenshot%202026-07-16%20123625.png)

## Setup

1. `Microsoft-KI-Agent (1).json` in n8n importieren
2. Credentials verknüpfen: Microsoft Teams API, Claude/Anthropic API
3. Workflow aktivieren

## Verwendete Nodes

- Microsoft Teams Trigger/Node
- Claude (Anthropic) LLM
- LangChain-Integration für n8n
