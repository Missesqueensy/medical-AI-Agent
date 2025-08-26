# Agent IA Chercheur de Médicaments (n8n Workflow)

## Description
Ce workflow n8n permet de :
- Chercher des médicaments dans une base locale (SQLite).
- Effectuer une recherche web si le médicament est introuvable.
- Envoyer les résultats par email et Telegram (avec audio généré automatiquement).

## Configuration
Avant d'utiliser ce workflow :
1. Importez `Agent_IA_de_Medicament.json` dans votre instance n8n.
2. Configurez vos credentials dans n8n :
   - SMTP (pour l'envoi d'email)
   - Telegram (pour l'envoi d'audio)
   - Google Gemini (ou autre modèle LLM)
3. Remplacez les placeholders dans le JSON :
   - `your_email@example.com`
   - `YOUR_TELEGRAM_CHAT_ID`
   - vos propres identifiants API

⚠️ Aucun identifiant sensible n'est inclus. Vous devez entrer les vôtres dans n8n.
