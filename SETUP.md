# Setup Instructions

## Repository Structure

```
bcnh-nanorings/
├── README.md                               # Main page
├── LICENSE                                 # CC-BY-4.0 license
├── images/                                 # Visualization figures
│   ├── README.md
│   ├── nonopt_4x4-1.png                   # Add your PNG files here
│   ├── nonopt_4x4-2.png
│   ├── nonopt_4x4-3.png
│   ├── nonopt_4x4-4.png
│   ├── opt_4x4-1.png
│   ├── opt_4x4-2.png
│   ├── opt_4x4-3.png
│   └── opt_4x4-4.png
└── structures/                             # Molecular structure files
    ├── README.md
    ├── b3c3-isomers-non-optimized.zip     # Add your ZIP files here
    └── b3c3-isomers-optimized.zip
```

## Required Files to Add

You need to add the following files before pushing to GitHub:

### In `images/` folder:
- [ ] nonopt_4x4-1.png
- [ ] nonopt_4x4-2.png
- [ ] nonopt_4x4-3.png
- [ ] nonopt_4x4-4.png
- [ ] opt_4x4-1.png
- [ ] opt_4x4-2.png
- [ ] opt_4x4-3.png
- [ ] opt_4x4-4.png

### In `structures/` folder:
- [ ] b3c3-isomers-non-optimized.zip
- [ ] b3c3-isomers-optimized.zip

## Quick Start

1. **Create GitHub repository:**
   ```bash
   # On GitHub, create a new repository named "bcnh-nanorings"
   ```

2. **Initialize local repository:**
   ```bash
   cd /path/to/your/files
   git init
   git add .
   git commit -m "Initial commit: BxCyHz nanorings project"
   ```

3. **Connect to GitHub:**
   ```bash
   git remote add origin https://github.com/yourusername/bcnh-nanorings.git
   git branch -M main
   git push -u origin main
   ```

4. **Verify:**
   - Visit your repository URL
   - Check that images display correctly
   - Test download links for ZIP files

## Notes

- Images should be PNG format, approximately 1200×1200 pixels or larger
- ZIP files should contain MOL format molecular structures
- Update the repository URL in README.md if needed

---

**Contact:** david888azv@unb.br
