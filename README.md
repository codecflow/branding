# CodecFlow Branding Assets

Official CodecFlow logo and partner assets.

## Repository structure

```text
branding/
├── codecflow-logo/
│   ├── logo/
│   │   ├── svg/
│   │   ├── pdf/
│   │   ├── png/
│   │   └── jpg/
│   ├── monogram/
│   │   ├── svg/
│   │   ├── pdf/
│   │   ├── png/
│   │   └── jpg/
│   └── logo-with-background/
│       └── png/
└── integrations/
    └── Partners/
        └── grayscale/
```

## Logo

`logo/` contains the horizontal CodecFlow logo. The black artwork is visible on white and light backgrounds.

Available formats:

- SVG for websites, interfaces, and scalable layouts
- PDF for print and design applications
- Transparent PNG at `@1x`, `@2x`, and `@4x`
- JPG for applications that do not support transparency

## Monogram

`monogram/` contains the standalone CodecFlow mark. The black artwork is visible on white and light backgrounds.

Available formats:

- SVG
- PDF
- Transparent PNG at `@1x`, `@2x`, and `@4x`
- JPG

## Logo with background

`logo-with-background/` contains ready-to-use PNG files with fixed backgrounds:

- `codecflow_logo_black_on_white`
- `codecflow_logo_white_on_black`

Both variants are available at `@1x`, `@2x`, and `@4x`.

## Visibility

White transparent logo and monogram exports are not included because their white lettering and shapes disappear in white-background previews. Use `codecflow_logo_white_on_black` when a white logo is required.

## Naming convention

Files follow this pattern:

```text
codecflow_[asset]_[artwork-or-context][resolution].[extension]
```

Examples:

- `codecflow_logo_black.svg`
- `codecflow_monogram_black@2x.png`
- `codecflow_logo_white_on_black@4x.png`

## Partner assets

`integrations/Partners/` contains partner and integration logos. Grayscale variants are stored in `integrations/Partners/grayscale/`.
