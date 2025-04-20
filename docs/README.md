# Audio IO protoboard

This is a template for making Fusion 360 projects for local usage or storing everything on git.

1. Run [create_dirs.sh](../create_dirs.sh)
2. Change README.md (this file)

---

Folder structure:

```
/3D_Projects/
└── ProjectName/
├── src/
│   ├── design.f3d
│   └── design.step
├── export/
│   ├── design.3mf
│   └── design.stl
├── references/
│   └── sketches, screenshots, PDFs, etc.
└── docs/
│   └── README.md (notes about the project, print settings, etc.)
```

- `.f3d` – Native Fusion 360 archive format (good for re-editing)
- `.step` – Interoperable CAD format (good for switching software later)
- `.3mf` and/or `.stl` – For slicing and 3D printing