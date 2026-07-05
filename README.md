# License Plate Frames

A collection of custom 3D-printed license plate frame designs created in Fusion 360 and manufactured on a Bambu Lab H2C printer.

The purpose of this repository is to develop, document, and organize unique license plate frame concepts while maintaining a common design template, manufacturing process, and set of dimensions.

Some designs are humorous. Some are commentary. Some may simply exist because the idea seemed amusing at the time.

---

## Design Approach

The Fusion 360 project is organized around reusable components that make it easy to create new frame designs.

### License Plate Reference

A dimensionally accurate model of a standard U.S. license plate used to verify:

- Plate visibility
- Registration sticker clearance
- Mounting hole locations
- Readability of required information

This component exists only as a design reference and is never printed.

### Frame Template

A reusable frame component containing:

- Outer frame geometry
- Standard mounting holes
- Reinforced mounting areas
- Plate opening dimensions
- Shared structural features

Every frame design is built on top of this template.

### Design-Specific Components

Each license plate frame concept is implemented as its own Fusion component containing only the unique graphics, text, and decorative elements required for that design.

This minimizes duplication and allows multiple designs to share the same base platform.

---

## Standard Dimensions

### U.S. License Plate Reference

| Dimension | Value |
|------------|---------|
| Width | 304.8 mm |
| Height | 152.4 mm |
| Hole Spacing X | 177.8 mm |
| Hole Spacing Y | 120.65 mm |

### Frame

| Dimension | Value |
|------------|---------|
| Outer Width | 330 mm |
| Outer Height | 178 mm |
| Thickness | 3.6 mm |
| Window Width | 296 mm |
| Window Height | 140 mm |

---

## Design Guidelines

When creating a new frame design:

- Do not obstruct registration stickers.
- Do not cover required plate information.
- Maintain clear visibility of license plate numbers.
- Reinforce mounting-hole locations when needed.
- Maintain sufficient clearance around holes and edges.

### Recommended Text Parameters

- Text Height: 18–22 mm
- Raised Depth: 1.4 mm
- Minimum Stroke Width: 1.2 mm

---

## Printing

### Recommended Materials

- PETG
- ASA

Avoid PLA for long-term outdoor use due to heat and UV exposure.

### Bambu H2C Settings

- Layer Height: 0.16 mm (final)
- Layer Height: 0.20 mm (draft)
- Walls: 4
- Top Layers: 6
- Infill: 20% Gyroid
- Brim: 8 Lines

### Multi-Color Printing

Typical configuration:

- Frame: Black
- Text / Graphics: White or contrasting color

Recommended Bambu Studio settings:

- Enable Flush Into Infill
- Flush Multiplier ≈ 0.6–0.7
- Enable Ironing for final surface quality

---

# Current Designs

## Endangered Species

A commentary-themed frame inspired by changes occurring in the Three Rivers community.

The design uses wildlife conservation language to draw attention to the declining number of year-round local residents.

Top:

THREE RIVERS LOCAL

Bottom:

ENDANGERED SPECIES


See:

[endangered-species/readme.md](endangered-species/readme.md)

---

## Bark 4 Eric

A humor-themed frame inspired by Riggs, a Redbone Hound who takes neighborhood security very seriously.

The design features a howling hound silhouette and the slogan:

Bark 4 Eric

Created as a lighthearted response to ongoing complaints regarding a dog doing what dogs naturally do—alerting on deer, bears, visitors, vehicles, and suspicious activity.

See:

[bark-4-eric/readme.md](bark-4-eric/readme.md)

## Repository Layout

```text
README.md

bark-4-eric/
    README.md

endangered-species/
    README.md
```

---

## Future Designs

New concepts can be added by:

1. Creating a new Fusion component based on the shared template.
2. Creating a matching repository folder.
3. Adding a README describing the concept and design story.

The framework is intended to allow a growing collection of license plate frame designs to share a common manufacturing and documentation process.
