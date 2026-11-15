---
hidden: true
---

# Coterie Onboarding & Admin Checklist

Use this checklist whenever a new permanent coterie is approved in a ticket, or when an existing coterie changes its domain or disbands.

---

## Part 1: Discord Admin Setup

- [ ] **Create Coterie Role:** Create the `@Coterie: [Emoji] [Coterie Name]` role and add all the coterie's players to the role.
- [ ] **Create Haven Channel:** Create a channel for their haven with their chosen description and a picture, and set the channel permissions for the new coterie role.
- [ ] **Update Territory Pin:** Edit the pinned location message in the corresponding Montreal district channel to show `Currently Owned by @Coterie` and their Domain traits.
- [ ] **Update Discord Rules Index:** Edit the rules index message under `Current Coteries in Montréal` to add their direct GitBook link:
  ~~~markdown
    - :emoji_shortcode: [Coterie Name](<https://montreal-by-night.gitbook.io/mtrwiki/coteries/coterie-name>)
  ~~~

---

## Part 2: GitHub / GitBook Wiki Updates

### 1. Create the Coterie Sheet (`coteries/coterie-name.md`)
- [ ] Create a new markdown file inside the `coteries/` folder using lowercase letters and hyphens (e.g., `coteries/the-night-shift.md`).
- [ ] Copy the `Coordinates` directly from the sect location file (`Camarilla Locations.md`, `Anarch Locations.md`, or `Contested Locations.md`) so they match the interactive map.

~~~markdown
# 🆕Coterie Name

* **Type:** [Archetype]
* **Name:** [Coterie Name]
* **Symbol:** 🆕

## 🏰 Domain Traits

* **Domain:** ●
* **Location:** #[Channel-Name] - [Named Location]
* **Chasse:** ●
* **Lien:** ●
* **Portillon:** ●
  * ↪ **[Trait Merit if applicable]:** ●

## 📍 Location Details

* **Primary HQ:** [Named Location]
* **Coordinates:** `00.0000, -00.0000`
* **Description:** [Short description of the location]
* **Hunting:** General Hunting DC 6.

## 🏚️ Havens

The coterie maintains one haven.

### 1. [Haven Name]

**Location:** #[Channel-Name] - [Named Location]\
**Haven Rating:** ●●

* ↪ **[Haven Merit]:** ●

## 💎 Coterie Advantages

**General Advantages:**

* **[Advantage]:** ●

**Clan Merits:**

* **[Clan Merit]:** ●●

## 👥 Members

* [Member 1]
* [Member 2]
* [Member 3]

## 🤝 Pooled Backgrounds

* **[Background]:** ●● ([Details / Owner])
~~~

---

### 2. Add to GitBook Sidebar (`SUMMARY.md`)
- [ ] Open `SUMMARY.md` and add the new coterie file at the bottom under `* [Coteries](coteries/README.md)`:
  ~~~markdown
  * [Coteries](coteries/README.md)
    * [⚜️Maison Des Lys Violets](coteries/maison-des-lys-violets.md)
    * [🐺The Wolfhounds](coteries/the-wolfhounds.md)
    * [♻️Ordinance 16 49](coteries/ordinance-16-49.md)
    * [🏥The Night Shift](coteries/the-night-shift.md)
    * [🆕New Coterie Name](coteries/new-coterie-name.md)
  ~~~

---

### 3. Add to Locations Legend (`locations/README.md`)
- [ ] Open `locations/README.md` and add the coterie's emoji and link under the appropriate faction (`Camarilla Coteries`, `Anarchs Coteries`, or `Indie and Hecata Coteries`):
  ~~~markdown
  * 🆕: [New Coterie Name Coterie](../coteries/new-coterie-name.md)
  ~~~

---

### 4. Update the Sect Location File & Map Pin (`locations/[Sect] Locations.md`)
- [ ] Open `locations/Camarilla Locations.md`, `locations/Anarch Locations.md`, or `locations/Contested Locations.md`.
- [ ] Find the claimed location and paste the ownership block directly below its coordinates and hunting DCs:
  ~~~markdown
    * **Currently Owned by 🆕 New Coterie Name Coterie**
      * **Domain:** ●
      * **Chasse:** ●
      * **Lien:** ●
      * **Portillon:** ●
  ~~~
> **Map Pin Automation Note:** `map/index.html` uses the regex `/\*\*Currently Owned [Bb]y (?:[Tt]he )?(.*?)\s/` to automatically swap the default 🟠/🟣/🔴 map pin to the coterie's emoji and populate the popup. Make sure there is a single space before and after the emoji (`Owned by 🆕 New Coterie...` or `Owned by the 🆕 New Coterie...`).

---

### 5. Update the Master Directory (`locations/Locations Directory.md`)
- [ ] Open `locations/Locations Directory.md`, find the claimed location, and add the single-line summary at the bottom of its bullet list:
  ~~~markdown
    * **Domain Traits:** Owned by 🆕 New Coterie Name Coterie | Domain: ●, Chasse: ●, Lien: ●, Portillon: ●.
  ~~~

---

## Part 3: Conditional & Long-Term Updates

- [ ] **Unique Loresheets (`rules/discipline-and-advantages/loresheets.md`):** If the coterie takes a server-limited loresheet dot (e.g., *Neillson Library*), add `*[Currently Owned by X Coterie]*` next to that dot.
- [ ] **Location Bonus Project (Coterie Ticket & `rules/Coterie.md`):**
  - When requested, assign their **DC 100 Timeskip Project** (1 specific Attribute + Skill pool, max 4 rolls per member per timeskip, roll OR teamwork, surges/WP allowed, no Disciplines or Domain trait bonuses).
  - Once completed, add the discovered bonus to `rules/Coterie.md` under `### Location bonuses` and to the territory channel pin.