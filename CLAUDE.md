# v-kiros Video Projects

Kiros client video projects.

## Final Assets Directory

The `final/` directory stores **publishable final videos** ready for distribution.

**Naming convention**: `{project-name}-v{version}.mp4` (lowercase-kebab-case)

**Examples**:
```
project-name/
└── final/
    ├── project-name-v1.mp4          # First version
    ├── project-name-v2.mp4          # Revised version
    └── project-name-short-v1.mp4    # Short variant
```

If you have voice variants (e.g., different voice actors), include that in the name:
```
project-name/
└── final/
    ├── project-name-american-grace-v1.mp4
    └── project-name-british-alice-v1.mp4
```

**Git tracking**: Files in `final/` are tracked (exception to video ignore rules).

**When to use**:
- ✅ Final client deliverables
- ✅ Multiple versions for client review
- ✅ Voice variant testing
- ❌ NOT for work-in-progress renders

---

Last updated: 2025-10-21
