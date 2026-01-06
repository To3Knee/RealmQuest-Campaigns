# 🌐 Player Portal Specifications

## 🖥️ View Layer
* **Tech:** Streamlit (Python) for rapid dashboarding.
* **Sync:** WebSockets for real-time dice and HP updates.

## 🔗 Integrations
* **Foundry VTT:** Embeds the Foundry map view via iframe (if hosted).
* **GitHub API:** Fetches images and logs to populate the Gallery and Chronicler.
* **Dice Engine:** Integration with dddice API for 3D synchronized rolling.

## 🔐 User Experience
* **Login:** Discord OAuth2 (Ensures only you and your brother can edit sheets).
* **Mobile Friendly:** Scalable UI for viewing sheets on a phone during play.