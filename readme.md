# DIY 3-Way Speaker Crossover + Amplifier System

This project is a custom-built 3-way audio system designed from scratch, including the amplifier, crossover network, and speaker configuration. The goal was to create a solid, practical setup that delivers good sound without overcomplicating the design.

---

## 🔊 System Overview

- Subwoofer: 10" DVC (handles low frequencies)
- Tower Speakers (x2):
  - 2 × Woofers (connected in series → 8Ω)
  - 1 × Midrange driver (4Ω)
  - 1 × Tweeter (4Ω)

- Passive 3-way crossover (2nd order)
- Custom PCB amplifier

---

## 📸 Screenshots

### PCB Layout
*(add screenshot here)*

---

### Schematic
*(add screenshot here)*

---

### 3D Model
*(add screenshot here)*

---

### Crossover Design
*(add screenshot here)*

---

## ⚙️ How It Works (Short)

The amplifier sends a full-range audio signal to the crossover.

The crossover splits this signal into three parts:

- Low frequencies → go to the woofers  
- Mid frequencies → go to the mid driver  
- High frequencies → go to the tweeter  

This is done using inductors and capacitors arranged as filters:

- Inductors block high frequencies  
- Capacitors block low frequencies  

Each driver only receives the frequencies it is meant to play, improving clarity and reducing distortion.

---

## 🧠 Design Choices

- Used a 2nd order crossover (12dB/octave) for better separation  
- Polypropylene capacitor for tweeter to improve high-frequency clarity  
- Electrolytic capacitors for mid and woofer to keep cost reasonable  
- Thick gauge inductors for low resistance and better power handling  

---

## 🧾 Components Used

### Capacitors
- 10µF Polypropylene (Tweeter)
- 68µF Electrolytic (Mid)
- 39µF Electrolytic (Woofer)

### Inductors
- 2.2mH (Woofer)
- 1.2mH (Mid)
- 0.22mH (Mid/Tweeter)

### Speakers
- Woofer: 2 × 4Ω (series → 8Ω)
- Mid: 4Ω
- Tweeter: 4Ω

---

## ⚠️ Notes

- Inductors should be placed apart and rotated to avoid interference  
- Ensure proper polarity when wiring drivers  
- The enclosure design significantly affects final sound quality  

---

## 🚀 Status

- [x] Amplifier designed  
- [x] PCB layout completed  
- [x] Crossover designed  
- [ ] Assembly  
- [ ] Testing  

---

## 📌 Future Improvements

- Fine-tune crossover after listening tests  
- Improve enclosure design  
- Add damping and internal bracing  

---

This is a work-in-progress build focused on learning and practical implementation rather than perfection.
