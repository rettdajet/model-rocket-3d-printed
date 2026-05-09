# Rocket Assembly - COMPLETE

## Major Milestone
Core rocket design is finished and assembled in CAD!

## Components Completed

### Body Tube
- File: `body_tube_BT80_hollow.f3d`
- Specifications:
  - Length: 28.4 inches (2 × 14.2" tubes with BT80 coupler)
  - Outer diameter: 2.6 inches
  - Inner diameter: 2.56 inches
  - Wall thickness: 0.02 inches
  - Material: PLA (3D printed)
  - Features: Hollow interior, joint marker at 14.2"
- Status: Ready to export to STL 

###  Nosecone
- File: `nosecone_BT80.f3d`
- Specifications:
  - Total height: 4.3 inches (4.0" visible cone + 0.3" friction fit base)
  - Base diameter: 2.6 inches (friction fit over body tube)
  - Tip diameter: 0.1 inches (sharp point)
  - Wall thickness: 2mm
  - Material: PLA
  - Features: Shock cord loop at tip, rounded leading edge
- Status: Ready to export to STL 

### ✅ Fins (4 pieces)
- File: `fin_BT80_single.f3d` (use 4× in assembly)
- Specifications:
  - Quantity: 4 fins at 90° spacing
  - Height (root to tip): 3.0 inches
  - Root chord (base): 2.0 inches
  - Tip chord (point): 0.5 inches
  - Thickness: 3.0mm (0.12 inches)
  - Material: PLA
  - Features: Rounded leading edge, filleted base for assembly
  - Positioning: 0.5-1 inch from bottom of body tube
- Status: Ready to export to STL 

## Assembly File
- File: `rocket_assembly_BT80.f3d`
- Status: Complete and verified 
- Shows all components fitted together
- Confirmed spacing and clearances

## Final Rocket Specifications

### Dimensions
- **Total height:** 32.4 inches (2.7 feet)
- **Body diameter:** 2.6 inches
- **Fin span:** ~5.6 inches (2.6" + 3.0" fins on both sides)

### Weight (Estimated)
- Body tube: ~50g
- Nosecone: ~30g
- Fins (4×): ~30g
- Avionics bay: ~50g (not yet designed)
- Engine mount: ~30g (not yet designed)
- **Total estimated: ~350-400g**  Well under 1,500g legal limit

### Performance
- Engine: Estes C6-5
- Expected altitude: 500-1000 feet
- Recovery: Parachute + AirTag tracking
- Legal status: Compliant with all FAA/NAR regulations

## What's Next
- [ ] Design avionics bay (sensor housing)
- [ ] Design engine mount
- [ ] Design parachute bay connector
- [ ] Export all parts to STL files
- [ ] Begin 3D printing
- [ ] Assemble physical rocket
- [ ] Integrate sensors
- [ ] Launch and test!

## Design Process Notes

### CAD Skills Applied
- Sketch creation (circles, lines, trapezoids)
- Extrude operations (creating 3D from 2D)
- Loft operations (tapering cone shape)
- Fillet operations (rounding edges)
- Assembly creation and component positioning
- Understanding coordinate planes (XY, XZ, YZ)

### Engineering Decisions Made
1. Switched from BT-20 (2.0") to BT-80 (2.6") for better avionics fit
2. Used BT80 couplers for internal tube connection (vs gluing)
3. Designed friction-fit nosecone for parachute deployment
4. 4 fins at 90° spacing for optimal stability
5. Hollow body tube design (realistic)

## Files in This Project

### CAD Design Files (Fusion 360)
- `body_tube_BT80_hollow.f3d`
- `nosecone_BT80.f3d`
- `fin_BT80_single.f3d`
- `rocket_assembly_BT80.f3d`

### Ready to Export
All parts are ready to be exported as STL files for 3D printing.

---
Date: 5/9/26
Status: Assembly design complete
Next milestone: STL export and 3D printing
