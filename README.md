# 🩸 BloodLust Resource Pack

> Custom textures and models for the BloodLust Minecraft plugin.

![Version](https://img.shields.io/badge/version-1.1.0-red)
![Minecraft](https://img.shields.io/badge/minecraft-1.21.4-green)
![Pack Format](https://img.shields.io/badge/pack--format-46-orange)

---

## 📦 Download

Grab the latest `BloodLust-ResourcePack.zip` from the [Releases](../../releases) tab.

---

## 🚀 Installation

### For Players (Client-Side)
1. Download `BloodLust-ResourcePack.zip` from the Releases tab
2. Copy the zip into your `.minecraft/resourcepacks/` folder
3. Launch Minecraft → **Options → Resource Packs** → enable **BloodLust**

### For Server Owners
1. Host `BloodLust-ResourcePack.zip` on a public URL (this GitHub Release page works great)
2. Get the SHA1 hash of the zip:
   - **Linux/Mac:** `sha1sum BloodLust-ResourcePack.zip`
   - **Windows:** `certUtil -hashfile "BloodLust-ResourcePack.zip" SHA1`
3. Add the following to your BloodLust `config.yml`:

```yaml
resource-pack:
  url: "https://github.com/YourName/BloodLust-ResourcePack/releases/download/v1.1.0/BloodLust-ResourcePack.zip"
  sha1: "your-sha1-hash-here"
  prompt: "<red>BloodLust <gray>requires a resource pack to display custom items correctly."
  required: true
```

The plugin will automatically send the pack to players when they join.

---

## 🎨 Included Textures

### Weapons
| Item | Base Item | Custom Model Data |
|---|---|---|
| BloodLust Sword | Netherite Sword | 1001 |
| Ritual Sword | Netherite Sword | 1301 |
| Solarius Axe | Netherite Axe | 1002 |
| Tenebris Axe | Netherite Axe | 1003 |

### Materials
| Item | Base Item | Custom Model Data |
|---|---|---|
| Blood Shard I | Amethyst Shard | 1101 |
| Blood Shard II | Amethyst Shard | 1102 |
| Blood Shard III | Amethyst Shard | 1103 |
| Blood Shard IV | Amethyst Shard | 1104 |
| Sun Shard | Amethyst Shard | 1113 |
| Dark Shard | Amethyst Shard | 1114 |
| Sun Ingot | Gold Ingot | 1111 |
| Dark Ingot | Netherite Ingot | 1112 |
| Ritual Crate Key | Tripwire Hook | 1401 |

---

## 🔗 Related

- [BloodLust Plugin](https://github.com/BloodLustMC/BloodLust) — The plugin this resource pack is designed for

---

## 📜 License

This resource pack is maintained by the **BloodLust Team** and is intended for use with the BloodLust plugin only.
