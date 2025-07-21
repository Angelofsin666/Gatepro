e# Gatepro
🏡 Gate Pro: Controllo Intelligente di Cancello, Allarme e Casa con Notifiche (Rientro/Uscita &amp; Casa Vuota)
# Blueprint: GatePro 🚪

Gestisce apertura cancello, allarme, tapparelle, luci e automazioni extra
al rientro, all'uscita o quando nessuno è in casa (es. vacanza o serata fuori).

## Caratteristiche
- Riconosce eventi: **rientro**, **uscita**, **nessuno a casa (>2 min)**
- Azioni:
  - apertura cancello
  - arm/disarm allarme
  - gestione tapparelle e luci
  - esecuzione di script/automazioni extra
  - notifiche interattive personalizzabili (Android/iOS)
- Completamente parametrizzabile, nessuna entità hardcoded

## Installazione
1. Copia `gestione_casa_cancello.yaml` in 
   `config/blueprints/automation/davide/`
2. Ricarica i blueprint in Home Assistant (`Impostazioni → Automazioni → Blueprints`)
3. Crea una nuova automazione da blueprint e configura i parametri

## Import diretto in Home Assistant
Usa il link:https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/Angelofsin666/Gatepro/main/gatepro.yaml
