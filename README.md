# Godzilla: King of the Monsters (2019)

**Godzilla: King of the Monsters** is an epic American monster film directed by *Michael Dougherty* and the third installment in Legendary's **MonsterVerse**. The movie pits humanity's crypto-zoological agency, **Monarch**, against a battery of god-sized monsters as they collide for supremacy.

> "Long live the King." — *Dr. Ishirō Serizawa*

---

## Featured Titans

The film brings four iconic Toho monsters to the big screen with massive scale and lore:

* **Godzilla (*Titanus Gojira*)**: The alpha predator and ancient guardian of Earth's natural balance.
* **King Ghidorah (*Monster Zero*)**: A three-headed extraterrestrial dragon and Godzilla's ultimate rival.
* **Mothra (*Titanus Mosura*)**: The benevolent "Queen of the Monsters" with a symbiotic connection to Godzilla.
* **Rodan (*Titanus Rodan*)**: A fiery, winged Titan awakened from a volcano in Isla de Mara.

---

## MonsterVerse Watch Order

If you want to watch the core MonsterVerse timeline in chronological order, follow these steps:

1. **Kong: Skull Island** (Set in 1973)
2. **Godzilla** (Set in 2014)
3. **Godzilla: King of the Monsters** (Set in 2019)
4. **Godzilla vs. Kong** (Set in 2024)
5. **Godzilla x Kong: The New Empire** (Set in 2027)

---

## Titan Stats & Classifications

| Titan Name | Designation | Primary Ability | Status |
| :--- | :--- | :--- | :--- |
| **Godzilla** | `Titanus Gojira` | Atomic Breath | Alpha |
| **King Ghidorah** | `Monster Zero` | Gravity Beams & Storms | Defeated |
| **Mothra** | `Titanus Mosura` | God Rays & Silk Attack | Reborn |
| **Rodan** | `Titanus Rodan` | Cyclonic Drift & Heat | Subservient |

---

## Fun Dev Easter Egg

If you ever build a Titan tracker in your `app-dev` repository, you could log Monarch alerts like this:

```python
def monarch_alert(titan_name, status):
    if status == "Awakened":
        return f"WARNING: {titan_name} has breached containment!"
    return f"{titan_name} is currently dormant."

print(monarch_alert("Titanus Gojira", "Awakened"))
