
# **ducky-pad-pro**

A repository for managing configurations and sharing custom designs for the **duckyPad Pro**, a customizable macro pad. This includes:
- Configuration files written in **Ducky Script** for macro automation.
- Custom-designed **case files** for the duckyPad Pro in **STL** and **STEP** formats.

---

## **Repository Structure**

```
.  ducky-pad-pro
│   ├──  case                                             # Custom case design files
│   │   ├──  low-profile                                  # Low profile design files
│   │   │   ├──  'DPP Case Low Profile - Button.step'
│   │   │   ├── 󰆧 'DPP Case Low Profile - Button.stl'
│   │   │   ├──  'DPP Case Low Profile - Top.step'
│   │   │   └── 󰆧 'DPP Case Low Profile - Top.stl'
│   │   ├──  standard                                     # standard sized design files
│   │   │   ├──  'DPP Case - Bottom.step'
│   │   │   ├── 󰆧 'DPP Case - Bottom.stl'
│   │   │   ├──  'DPP Case - Button.step'
│   │   │   ├── 󰆧 'DPP Case - Button.stl'
│   │   │   ├──  'DPP Case - Top.step'
│   │   │   └── 󰆧 'DPP Case - Top.stl'
│   │   ├──  'DPP Case Low Profile Render.PNG'
│   │   └──  'DPP Case Render.png'
│   ├──  config                                           # My personal scripts
│       ├── ...
│   └──  README.md
├──  LICENSE
└──  README.md                                            # This README file
```

---

## **Features**


1. **Custom Case Designs**:
   - **Low-Profile Option**: 
     - A slim top and button design.
     - Accommodates the existing dials.
     - Uses the same bottom case as the standard option.
   - **Standard Option**: 
     - Designed for a more traditional look and feel.
     - Requires new dials to be printed.
     - Allows for further customization with third-party components.

2. **Configuration Files**:
   - My personal Ducky Pad Pro scripts.

3. **File Formats**:
   - **STL**: Ready for 3D printing.
   - **STEP**: Editable for further design customization.

---

## **Usage**


### **3D Printing the Case**
1. Navigate to the `case/` folder.
2. Choose between:
   - `low-profile/`: For a slim, compact design (print the button twice).
   - `standard/`: For a more traditional design (print the button twice).
3. Download the `.stl` file(s) and print them using your preferred 3D printer.
   - Recommended material: PLA or ABS for durability.
   - Suggested layer height: 0.16mm for optimal detail.
   - I used tree supports (remove them carefully).

### **Customizing the Case**
1. Use the `.step` files in your preferred CAD software (e.g., Fusion 360, SolidWorks).
2. Modify the design as needed.
3. Export as `.stl` for 3D printing.

---

## **Case Types**

### **Low-Profile Case**
<img src="case/DPP%20Case%20Low%20Profile%20Render.PNG" alt="Low Profile Case" width="250" />

- Slim top design for compact style with the sides of the case below the top of the MX switches.
- Uses original dials provide in the kit.
- Includes low-profile button design compatible with duckyPad Pro buttons.

### **Standard Case**
<img src="case/DPP%20Case%20Render.png" alt="Low Profile Case" width="250" />


- A more traditional case design with the sides of the case extending above the top of the MX switches.
- Requires new dials to be printed.
    - I used this one [Encoder Knob](https://www.printables.com/model/347536-encoder-knob) by VOID.
    - You may use any dial you wish but they need to have a diameter less than 16mm.


### This is my 3D printed case!

<img src="case/DPP%20Case%20Finished.png" alt="Low Profile Case" width="250" />

---

## **Acknowledgments**

- Inspired by the original [duckyPad Pro](https://github.com/dekuNukem/duckyPad-Pro) by [dekuNukem](https://github.com/dekuNukem). 
- For more details on the Ducky Pad Pro, check out the [Kickstarter](https://www.kickstarter.com/projects/dekunukem/duckypad-pro-advanced-macro-scripting-beyond-qmk-via/description) page.
