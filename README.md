# EDDY Pump Purchase Line Item Builder

Static GitHub Pages MVP for the HubSpot Product Builder project.

## What it does

- Loads `pump_config_rules.json`
- Guides sales rep through model → product family → rotor → material → HP → voltage
- Generates configured SKU
- Generates line item name and description
- Shows HubSpot-ready line item payload
- Does **not** write to HubSpot yet

## Host on GitHub Pages

1. Create a new GitHub repo, e.g. `eddy-pump-line-item-builder`.
2. Upload the contents of this folder to the repo root:
   - `index.html`
   - `pump_config_rules.json`
   - `README.md`
3. In GitHub, go to **Settings → Pages**.
4. Source: **Deploy from a branch**.
5. Branch: `main`, folder `/root`.
6. Save.
7. GitHub will provide a URL like:
   `https://<org>.github.io/eddy-pump-line-item-builder/`

## Next step

After the sales flow is approved, convert this into a HubSpot private app / CRM card and replace the payload preview with a real HubSpot line item creation call.
