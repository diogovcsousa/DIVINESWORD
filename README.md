# Divine Sword — Michael vs Demons 🗡️👼

**A rogue-like action game where Michael the Archangel battles endless waves of demons in Hell.**

## 🎮 Game Overview

**DivineSword** is a fast-paced, top-down action game featuring:
- **Michael the Archangel** as the protagonist
- **Endless demon waves** with increasing difficulty
- **Three divine weapons:** Sword, Crossbow, Heavenly Burst
- **Rogue-like progression** with upgrades and meta-progression
- **Explosive contact mechanics** and blood effects
- **Controller support** for Xbox/PC gamepads

## 🚀 Features

### **Combat System**
- **Divine Sword:** 120° cone slash, primary weapon
- **Holy Crossbow:** Ranged attacks, limited ammo
- **Heavenly Burst:** AOE explosion, consumes Divine Favor
- **Roll/Dash:** Evasive maneuver with explosion immunity

### **Progression System**
- **Divine Favor:** Earned by slaying demons
- **Weapon Upgrades:** 5 levels, increases damage by 20% each
- **Wave Scaling:** Progressive difficulty and demon mix
- **Boss Waves:** Every 10th wave with special bonuses

### **Visual Effects**
- **Particle Systems:** Dynamic effects for all weapons
- **Blood System:** Realistic pools and splatter
- **Explosions:** Multi-stage contact explosions
- **Hell Environment:** Floating platforms, fire effects

## 🎯 Controls

### **Keyboard & Mouse**
- **WASD/Arrows:** Move Michael
- **Mouse:** Aim direction
- **Left Click:** Attack with current weapon
- **R:** Switch weapon (Sword ↔ Crossbow)
- **E:** Heavenly Burst
- **T:** Upgrade weapon
- **Q:** Use medkit
- **Spacebar:** Roll/Dash

### **Xbox Controller**
- **Left Stick:** Movement
- **Right Stick:** Aim
- **RT:** Attack
- **RB:** Upgrade weapon
- **B:** Roll/Dash
- **X:** Switch weapon
- **Y:** Heavenly Burst
- **LB:** Use medkit

## 🎲 Gameplay

### **Objective**
Survive endless waves of demons while earning Divine Favor to upgrade your weapons.

### **Strategy**
- **Sword is primary:** Fast cooldown, directional attacks
- **Use roll wisely:** Immune to explosions during roll
- **Manage resources:** Crossbow ammo and Divine Favor
- **Positioning:** Keep demons at sword range
- **Upgrade timing:** Balance upgrades with survival

### **Demon Types**
- **Imp:** Fast, explosive on contact (80 damage)
- **Hellhound:** Very fast, explosive on contact (120 damage)
- **Fallen:** Slow, high HP, melee damage only

## 🛠️ Technical Details

### **Performance Targets**
- **Target FPS:** 120 FPS
- **Warning FPS:** 90 FPS (yellow indicator)
- **Critical FPS:** 60 FPS (red indicator)
- **Particle Limit:** 200 max
- **Blood Pool Limit:** 50 max

### **Browser Compatibility**
- **Chrome:** Full support
- **Firefox:** Full support
- **Safari:** Full support
- **Edge:** Full support

### **System Requirements**
- **Modern browser** with ES6+ support
- **WebGL** support for canvas rendering
- **Gamepad API** support for controllers
- **4K display** recommended for full experience

## 🚀 Installation & Play

### **Quick Start**
1. **Download** `DivineSword.html`
2. **Open** in any modern web browser
3. **Game starts automatically** - no installation needed
4. **Connect controller** for best experience
5. **Fullscreen** recommended (F11)

### **Local Development**
```bash
# Clone repository
git clone https://github.com/diogo-vibe/DIVINESWORD.git

# Navigate to directory
cd DIVINESWORD

# Open in browser
# Or use Live Server extension in VS Code
```

## 🎨 Development

### **Architecture**
- **Single HTML file** with embedded CSS/JS
- **Canvas 2D rendering** for performance
- **Modular functions** for maintainability
- **ES6+ features** for modern JavaScript

### **Key Systems**
- **Game Loop:** `requestAnimationFrame` based
- **Particle System:** Dynamic creation and cleanup
- **Input Handling:** Keyboard, mouse, and gamepad
- **State Management:** Global game object
- **Rendering:** Optimized canvas operations

### **Performance Features**
- **Particle culling** for off-screen effects
- **Blood pool limits** to prevent memory issues
- **Error handling** with graceful degradation
- **FPS monitoring** with visual indicators

## 🏆 Achievements & Progression

### **Wave Milestones**
- **Wave 10:** First boss wave
- **Wave 25:** Mid-game challenge
- **Wave 50:** Expert level
- **Wave 100:** Master level

### **Upgrade Paths**
- **Level 1:** Base damage
- **Level 3:** 40% damage increase
- **Level 5:** 100% damage increase (max)

### **Divine Favor Economy**
- **Base earning:** 3-12 per demon
- **Wave bonus:** +0.5 per wave
- **Boss bonus:** +5 per boss wave
- **Upgrade cost:** 50 Divine Favor

## 🐛 Known Issues & Solutions

### **Performance Issues**
- **Low FPS:** Reduce browser tabs, close other applications
- **Particle lag:** Game automatically limits particles
- **Memory issues:** Refresh page if needed

### **Controller Issues**
- **Not detected:** Ensure controller is connected before page load
- **Button mapping:** Check Xbox controller compatibility
- **Dead zone:** Built-in dead zone handling

### **Browser Issues**
- **Canvas not working:** Update browser or enable WebGL
- **Audio issues:** Check browser audio permissions
- **Fullscreen issues:** Use F11 or browser controls

## 🔮 Future Features

### **Planned Updates**
- **Sound effects** and background music
- **More demon types** and boss variants
- **Additional weapons** and abilities
- **Save system** for progress persistence
- **Leaderboards** and achievements

### **Modding Support**
- **Custom demon types**
- **Weapon modifications**
- **Level editors**
- **Community content**

## 📱 Mobile Support

### **Touch Controls**
- **Virtual joystick** for movement
- **Touch buttons** for actions
- **Gesture support** for special moves
- **Responsive design** for all screen sizes

### **Performance**
- **Optimized rendering** for mobile GPUs
- **Reduced particle counts** on low-end devices
- **Adaptive quality** based on device capabilities

## 🤝 Contributing

### **Development Setup**
1. **Fork** the repository
2. **Create** feature branch
3. **Make** changes
4. **Test** thoroughly
5. **Submit** pull request

### **Code Standards**
- **ES6+ syntax** preferred
- **Clear comments** for complex logic
- **Performance-first** approach
- **Cross-browser** compatibility

## 📄 License

**DivineSword** is open source software. See LICENSE file for details.

## 🙏 Acknowledgments

- **Three.js community** for inspiration
- **Canvas API** for rendering performance
- **Gamepad API** for controller support
- **VIBE CODING** community for feedback

---

**🎮 Ready to slay demons in Hell? Open DivineSword.html and begin your divine mission!**

**👼 Michael awaits your command...**
