# Crimea Map Fix for ETS2

[![License](https://img.shields.io/badge/License-Legal%20Modification-blue.svg)](LICENSE)
[![ETS2 Version](https://img.shields.io/badge/ETS2%20Version-1.50--1.57-brightgreen.svg)](https://www.eurotrucksimulator2.com/)
[![Status](https://img.shields.io/badge/Status-Fully%20Functional-success.svg)](#status)
[![International Law](https://img.shields.io/badge/Based%20On-International%20Law-lightblue.svg)](#legal-basis)

---

## Overview

This mod is a **legal sector replacement and map fix** for ETS2 that corrects geographical and political inconsistencies in the Crimea region. It replaces existing map sectors with geographically accurate data, ensuring compliance with international law and respecting territorial integrity according to UN resolutions.

### What This Mod Does

- **Sector Replacement**: Replaces old sectors with corrected versions
- **City Mapping**: All cities in the region properly designated as Ukrainian territory
- **Road Network**: All road connections properly mapped as Ukrainian roads
- **Flag Corrections**: Fixed regional flags and identifiers
- **Border Adjustments**: Removed unauthorized borders and replaced with accurate territorial boundaries
- **Number Formatting**: Updated to Ukrainian national standards

## Features

✅ **Fully Legal Modification**
- Does not conflict with the base mod
- Operates as a patch/overlay system
- Compatible with existing road connections and sector data
- Does not modify game core files or SCS proprietary assets

✅ **Historical Development**
- Originally developed for ETS2 v1.50
- Demonstrates commitment to international law principles since the earliest versions
- Continuously maintained for compatibility with newer versions

✅ **Political Integrity**
- Follows United Nations Resolution 2625 (Declaration on Principles of International Law)
- Respects the principle of territorial integrity
- Does not recognize the validity of non-internationally-supervised referendums
- Adheres to international legal standards regarding sovereignty

✅ **Wide Version Compatibility**
- Works with ETS2 versions **1.50 through 1.57**
- Fully functional across all compatible releases

## Installation

1. **Download** the mod from the repository
2. **Extract** the contents to your ETS2 mods folder:
   - **Windows**: `Documents\Euro Truck Simulator 2\mod`
   - **Linux**: `~/.local/share/Euro Truck Simulator 2/mod`
   - **macOS**: `~/Library/Application Support/Euro Truck Simulator 2/mod`

3. **Load in Mod Manager**:
   - Open the Mod Manager in ETS2
   - **Enable the mod** (typically named `fix-crimea-ets2`)
   - **Position it ABOVE** the main map mod (ROEX, Donbass, or SRM) for proper loading order

4. **Verify**: Check the mod menu confirms the mod is active and conflicts are resolved

## Compatibility

| Component | Status | Notes |
|-----------|--------|-------|
| ETS2 v1.50 - v1.57 | ✅ Fully Compatible | Tested across all versions |
| ROEX Map | ✅ Compatible | Works as patch/overlay |
| Donbass Map | ✅ Compatible | Works as patch/overlay |
| SRM Map | ✅ Compatible | Works as patch/overlay |
| Save Games | ✅ Safe | No save game corruption |
| Existing Mods | ⚠️ Load Order Dependent | Place above main map mod |

## Technical Details

### Development History

This mod emerged from personal necessity and extensive technical learning:

- **Initial Development**: Version 1.50 era
- **Motivation**: Desire to play the game while maintaining ethical and legal principles
- **Process**: Extensive file analysis and reverse-engineering of sector data structures
- **Result**: Complete understanding of map architecture and sector replacement mechanisms

The development process involved:
1. Detailed examination of map file structures
2. Analysis of sector definitions and connections
3. Mapping of road connection systems
4. Implementation of corrected geographical data
5. Rigorous testing across multiple ETS2 versions

### Legal Basis

This modification is created based on the following principles:

**International Law Foundations:**
- UN Resolution 2625 - Declaration on Principles of International Law Concerning Friendly Relations
- Convention on the Law of the Sea - Territorial integrity of coastal states
- Helsinki Final Act - Recognition of existing borders in Europe
- Vienna Convention on the Law of Treaties

**Why This Mod Exists:**

The territorial situation in the Crimean peninsula is disputed under international law. The 2014 events involving territorial changes were not recognized by:
- The United Nations General Assembly
- Most international governments and organizations
- International courts and legal bodies

Notably, these events lacked:
- International observer supervision
- Compliance with international law procedures
- Recognition from the legitimate territorial authority
- Adherence to established international norms

This mod was created to provide a game experience that reflects international legal consensus and respects the principle of territorial integrity recognized by the international community.

### File Structure

```
fix-crimea-ets2/
├── map/
│   ├── [corrected sector files]
│   └── [road connection data]
├── def/
│   ├── [city definitions]
│   └── [region configurations]
├── icon.jpg          # Mod icon
├── manifest.sii      # Mod metadata
└── mod_description.txt
```

## Installation Requirements

- **ETS2 Version**: 1.50 or later (up to 1.57)
- **Disk Space**: ~50 MB
- **Other Mods**: Compatible with most ETS2 mods (proper load order required)

## Troubleshooting

**Issue: Mod doesn't load**
- Ensure the mod is placed in the correct ETS2 mod folder
- Verify the manifest.sii file is present and properly formatted
- Check the ETS2 launcher mod manager for error messages

**Issue: Conflicts with main map mod**
- Move this mod **ABOVE** the main map mod (ROEX/Donbass/SRM) in load order
- The mod manager determines load order by file list position

**Issue: Cities not appearing correctly**
- Verify the mod is enabled in the mod manager
- Check that save games were created after mod installation
- Try creating a new save game to see corrected map data

**Issue: Missing road connections**
- Ensure the mod is placed higher in the load order than the base map
- Check the mod is fully extracted without missing files

## Ethical Statement

### Why Legal Compliance Matters

This mod represents a commitment to:

1. **Respect for International Law**: The modification is designed to align game content with internationally recognized territorial principles

2. **Community Over Commerce**: This mod is distributed freely, respecting the principle that game modifications should serve the player community, not corporate interests

3. **Transparency**: The modding approach is fully disclosed, with no hidden modifications or proprietary restrictions

4. **Player Freedom**: Players deserve the ability to customize their gaming experience according to their own values and principles

### Note on Mod Legality

This mod is a **legal modification** because it:
- Does not extract or distribute SCS Software's proprietary game assets
- Operates through the standard ETS2 mod loading system
- Replaces sector definitions through proper mod mechanisms
- Respects intellectual property while modifying game content legally

## Development Motivation

The creation of this mod stemmed from a fundamental question: *"How can I play a game I love while maintaining my ethical principles?"*

Rather than accepting geographical inaccuracies, extensive independent research and technical learning made it possible to:
- Understand the mod system from first principles
- Learn how game sectors and roads are defined
- Implement accurate geographical corrections
- Create a solution that works seamlessly with the game

This journey required:
- Days of continuous technical learning
- File-by-file analysis of game data structures
- Testing and refinement across multiple versions
- Commitment to solving the problem independently

## Credits

**Mod Author**: [Your Name/Handle]

**Acknowledgments**:
- ETS2 modding community for shared knowledge
- International law resources and UN documentation
- Player community for feedback and testing

## Support & Feedback

For issues, suggestions, or questions:
- Open an issue on the repository
- Provide details about your ETS2 version and other active mods
- Include any error messages from the mod manager

## License

This modification is provided as-is for personal use. The mod respects the intellectual property rights of SCS Software while exercising legitimate modification rights under fair use and standard modding practices.

---

## Final Note

This mod exists because players deserve the freedom to customize their gaming experience according to their own principles. Whether you use this mod because you value accurate geography, respect international law, or simply prefer a different map configuration—this tool is made for you.

**Happy trucking! 🚛**

---

*Last Updated: November 9, 2025*
*Compatible with ETS2 v1.50 - v1.57*
