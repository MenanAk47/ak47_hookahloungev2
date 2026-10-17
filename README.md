**The ultimate hookah lounge and bar experience for FiveM servers.** This script completely revamps the nightlife and social roleplay with realistic hookah smoking mechanics, a fully functional mixology bar job, dynamic coal heaters, interactive maintenance, and immersive effects. Powered by `ak47_lib`, it features multi-framework support, physical rope hoses, custom audio, synced smoke particles, and bartender tipping systems.

---

## 🎥 Showcase
<img width="1920" height="1080" alt="thumbnail" src="https://github.com/user-attachments/assets/4bd0adc1-6993-4be0-8c4c-fe42b7419434" />

> **[Click here to watch the full feature showcase on YouTube](https://youtu.be/uCFnH9ZgTsU)**

---

## 🔥 Key Features

Designed to elevate roleplay, social interaction, and business management:

### 💨 Realistic Hookah Smoking Mechanics

* **Physical Rope Hoses:** Dynamically attaches a 3D rope hose connecting the hookah pipe directly to the player's hand with complete physics sync.
* **Synchronized Audio & Visuals:** Features custom bubbling inhale sounds, exhale sounds, custom facial expressions, and dense 3D mouth smoke particle effects.
* **Buffs & Stress Relief:** Smoking provides visual screen effects, relaxed/drunk movement clipsets, armor recovery (+25 armor), and progressive stress reduction (-30 stress).
* **Session Economics:** Configurable session fee per table that automatically routes earnings directly into the hookah lounge society fund.

### 🔥 Deep Preparation & Maintenance System

* **5-Point Hookah Condition:** Every hookah tracks Water cleanliness, Hose condition, Foil durability, Coal heat/burn percentage, and Tobacco level.
* **Real-time Degradation:** Hookahs naturally degrade over time and with every puff taken, requiring staff to clean, change water, and re-coal.
* **Coal Heating Burners:** Functional coal burners (`prop_cooker_03`) where staff place raw coals, wait for them to heat, and collect hot coals.
* **Foil Poking Tool:** Interactive foil preparation where employees poke holes into foil paper before mounting it to the bowl.
* **16 Premium Shisha Flavors:** Choose from a wide selection of authentic flavors including 4Play Passion, Vintage Blueberry, Absolute Zero Mint, Secret Love 66, Blue Mist, Double Apple, White Gummy Bear, and more.

### 🍸 Full Mixology Bar Job & Tipping

* **Extensive Drink Menu:** Prepare and serve Cocktails, Champagne, Daiquiri, Red Wine, White Wine, Whisky, Tequila Shots, and Mojitos.
* **Immersive Bartending Animations:** Multi-stage drink preparation animations with cocktail shakers, bottles, shot glasses, ice cubes, and mint leaves.
* **Interactive Tip System:** Customers inside dedicated tip zones can drink and tip the closest on-duty bartender directly via Cash or Bank Card.
* **Stock & Supplies Shop:** Multi-slot ingredient stock shops with auto-regeneration and society purchasing.

### 🛠️ Technical Excellence & Administration

* **Multi-Framework & Target Support:** Seamlessly works with ESX, QB-Core, and QBX, utilizing any target system (`ox_target`, `qb-target`, `qtarget`) via `ak47_lib`.
* **Full Database Persistence:** Hookah status, coal burn levels, and tobacco persist across server restarts via `oxmysql`.
* **Admin Utilities:** Includes `/refillallhookah` (and `/refillhookah`) commands and server export `RefillAllHookahs` to instantly refill all lounge hookahs to 100%.
* **Boss Management:** Native support for `esx_society`, `qb-management`, and `qbx_management`.

---

## 💻 Framework:

* ESX, QB, QBX

---

## ⚙️ Dependencies:

* ak47_lib: https://github.com/MenanAk47/ak47_lib/releases/latest
* oxmysql

---

## ⚙️ How To Install:

* Download ak47_hookahloungev2 from your cfx portal.
* Add the script into your resources folder.
* Import the database SQL (`INSTALL ME FIRST/database/`) into your database.
* Add items and jobs based on your framework instruction from the `INSTALL ME FIRST` folder.
* Add item images into your inventory's image directory.
* Start the script in your `server.cfg` below framework files and `ak47_lib`.
* Make sure you have all dependencies.
* Restart the server.

---

## 🔗 Links & Support:

* **📖 Documentation:** [https://docs.menanak47.com/multi-framework/ak47_hookahloungev2](https://docs.menanak47.com/multi-framework/ak47_hookahloungev2)
* **🛒 Buy Now (Tebex):** [https://menanak47.tebex.io/package/6654654](https://menanak47.tebex.io/package/6654654)
* **💬 Discord Support:** [https://discord.gg/menanak47](https://discord.gg/menanak47)

---

## 📝 Note:
* We don't support custom framework. Make sure you are using official framework update.
* Renaming the script is not allowed. It may break the functionalities.
* Don't upload the script with FileZilla, Use Winscp if you are using FTP for file uploading.
