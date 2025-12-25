# Button

This document describes the Button component used in PuppyTrack.

## States
- Default
- Hover
- Pressed
- Disabled

## Color Tokens
- color/primary
- color/secondary
- color/text-primary
- color/text-secondary
- color/surface-default

## State Mapping

### Default
- Background: color/primary
- Text: color/text-primary

### Hover
- Background: color/secondary
- Text: color/text-primary

### Pressed
- Background: color/primary
- Opacity: 90%

### Disabled
- Background: color/surface-default
- Text: color/text-secondary (40%)
- Stroke: color/text-secondary (40%)

## Behavior
- Auto Layout (Hug)
- Width expands based on text
- Disabled state is non-interactive

## Figma
](https://www.figma.com/design/rDSx5lPyeMNFHmftZQTj25/Puppy-Track-Design-System?node-id=18-64&t=DkvTgOEG4TfiM7YI-1)
