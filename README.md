# CodecFlow Branding Assets

Official CodecFlow logo and partner assets.

## Repository structure

```text
branding/
├── codecflow-logo/
│   ├── symbol/
│   │   ├── svg/
│   │   ├── pdf/
│   │   ├── png/
│   │   └── jpg/
│   ├── lockup/
│   │   ├── svg/
│   │   ├── pdf/
│   │   ├── png/
│   │   └── jpg/
│   └── lockup-with-background/
│       └── png/
└── integrations/
    └── Partners/
        └── grayscale/
```

## CodecFlow logo variants

### Symbol

The standalone CodecFlow symbol is available in black and white artwork variants.

- `codecflow_symbol_black`: black symbol with a white counter
- `codecflow_symbol_white`: white symbol with a black counter

SVG and PNG files preserve transparency. PNG files are provided at `@1x`, `@2x`, and `@4x` resolutions.

### Lockup

The horizontal lockup combines the CodecFlow symbol and wordmark.

- `codecflow_lockup_black`: black artwork for light backgrounds
- `codecflow_lockup_white`: white artwork for dark backgrounds

SVG and PNG files preserve transparency. PNG files are provided at `@1x`, `@2x`, and `@4x` resolutions.

### Lockup with background

Ready-to-use PNG lockups are available with fixed backgrounds:

- `codecflow_lockup_black_on_white`
- `codecflow_lockup_white_on_black`

Both variants are provided at `@1x`, `@2x`, and `@4x` resolutions.

## Format guidance

- Use SVG for websites, interfaces, and scalable digital layouts.
- Use PDF for print and design applications.
- Use transparent PNG files when raster artwork is required.
- Use the background PNG files when a fixed black or white field is needed.
- Use JPG only when transparency is not required.

## Naming convention

Files follow this pattern:

```text
codecflow_[asset]_[artwork-or-context][resolution].[extension]
```

Examples:

- `codecflow_symbol_black.svg`
- `codecflow_lockup_white@2x.png`
- `codecflow_lockup_black_on_white@4x.png`

## Partner assets

`integrations/Partners/` contains partner and integration logos. Grayscale variants are stored in `integrations/Partners/grayscale/`.
