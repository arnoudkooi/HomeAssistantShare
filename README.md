# Home Assistant Collection

A curated collection of Home Assistant blueprints, automations, and utilities to enhance your smart home experience.

## 🎯 Current Blueprints

### 🔢 [Numeric Keypad Remote Control](./blueprints/numeric-keyboard/)
Transform any numeric keypad or calculator into a powerful Home Assistant remote control. Control lights, scenes, media players, and more with individual key actions.

**Features:**
- ✅ Complete support for all 17 keys (numbers, operators, special functions)
- ✅ Skip unused keys - leave any key action blank to ignore it
- ✅ Simple configuration with no complex sequences
- ✅ Works with USB and Bluetooth keypads

[![Import Numeric Keypad Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A//raw.githubusercontent.com/arnoudkooi/HomeAssistantShare/main/blueprints/numeric-keyboard/keypad.yaml)

### 🎨 [XP-Pen ACK05 Remote Control](./blueprints/xp-pen/)
Professional remote control for XP-Pen ACK05 devices with support for complex multi-key sequences and rotary knob control.

**Features:**
- ✅ Complete support for all 10 keys plus rotary knob (CW/CCW)
- ✅ Multi-key sequence detection with intelligent debouncing
- ✅ Orientation support (landscape and portrait modes)
- ✅ State management for reliable operation

[![Import XP-Pen Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A//raw.githubusercontent.com/arnoudkooi/HomeAssistantShare/main/blueprints/xp-pen/xp-pen-ack05.yaml)

## 🚀 Getting Started

### Quick Import
Click the import buttons above to automatically add these blueprints to your Home Assistant instance.

### Manual Installation
1. Navigate to **Settings** → **Automations & Scenes** → **Blueprints**
2. Click **"IMPORT BLUEPRINT"**
3. Enter the raw GitHub URL of the desired blueprint
4. Click **"PREVIEW BLUEPRINT"** and then **"IMPORT BLUEPRINT"**

### Prerequisites
- Home Assistant with blueprint support
- [keyboard_remote integration](https://github.com/bendavid/keyboard_remote) installed and configured

## 📁 Repository Structure

```
ha/
├── blueprints/
│   ├── numeric-keyboard/     # Numeric keypad/calculator remote
│   │   ├── keypad.yaml      # Blueprint file
│   │   ├── README.md        # Detailed documentation
│   │   └── keypad.jpg       # Key layout reference
│   └── xp-pen/              # XP-Pen ACK05 remote
│       ├── xp-pen-ack05.yaml    # Blueprint file
│       ├── README.md            # Detailed documentation
│       └── XPPEN-ACK05-Keys.png # Key layout reference
└── README.md                # This file
```

## 🔮 Future Plans

This repository is designed to be a comprehensive collection of useful Home Assistant resources. Coming soon:

- 🎛️ **Additional Device Blueprints**: Support for more remote controls and input devices
- 🤖 **Advanced Automations**: Complex multi-device automation examples
- 🎭 **Scene Collections**: Pre-built scenes for common scenarios
- 🔧 **Utility Scripts**: Helper scripts for device setup and troubleshooting
- 📊 **Dashboard Cards**: Custom Lovelace cards and configurations
- 🏠 **Integration Guides**: Step-by-step guides for popular integrations

## 🤝 Contributing

Have a useful Home Assistant blueprint, automation, or utility to share? Contributions are welcome!

1. Fork this repository
2. Create a feature branch
3. Add your contribution with proper documentation
4. Submit a pull request

## 📝 License

This project is open source. Feel free to use, modify, and distribute these blueprints and utilities.

## 🆘 Support

- 📖 Check the individual blueprint README files for detailed setup instructions
- 💬 Open an issue if you encounter problems or have suggestions
- 📺 Watch the referenced video guides for visual setup instructions

---

*Happy automating! 🏠✨*
