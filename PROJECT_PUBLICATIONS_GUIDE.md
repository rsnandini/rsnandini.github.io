# How to Add Publications to Project Pages

This guide shows you how to manually add publications to any project `.md` file.

## Quick Usage

Add this line anywhere in your project markdown file (e.g., `_projects/PhD.md`):

```liquid
{% include project_publications.html keys="paper1_key,paper2_key,paper3_key" %}
```

## Step-by-Step Instructions

### 1. Find the BibTeX Key

Open `_bibliography/papers.bib` and find the key of the paper you want to add.

**Example:**
```bibtex
@article{sharma2022interfacial,    ← This is the key
  title={Interfacial skyrmion...},
  ...
}
```

The key is `sharma2022interfacial`

### 2. Add to Your Project File

Open your project file (e.g., `_projects/Master's.md`) and add:

```markdown
## Related Publications

{% include project_publications.html keys="sharma2022interfacial" %}
```

### 3. Multiple Publications

To add multiple papers, separate keys with commas (no spaces):

```liquid
{% include project_publications.html keys="sharma2022interfacial,sharma2023magnetic,sharma2023all" %}
```

## Full Examples

### Example 1: PhD Project with 4 Papers

```markdown
---
layout: page
title: My PhD Research
category: Ph.D.
---

My research focused on magnetic materials...

## Related Publications

{% include project_publications.html keys="sharma2022interfacial,sharma2023magnetic,sharma2023all,sharma2023magnetic1" %}
```

### Example 2: Master's Project with 1 Paper

```markdown
---
layout: page
title: Raman Spectroscopy Study
category: Master's
---

This project investigated temperature-dependent Raman modes...

## Skills Demonstrated

XRD, Raman spectroscopy, data analysis

## Related Publications

{% include project_publications.html keys="sharma2023raman" %}
```

### Example 3: Ion Irradiation Project

```markdown
## Publications & Impact

This work resulted in a conference proceeding published in AIP...

{% include project_publications.html keys="sharma2018effect" %}
```

## What Gets Displayed

The include automatically shows:
- ✅ Paper title with link
- ✅ Authors
- ✅ Journal/venue
- ✅ Year
- ✅ Abstract (expandable)
- ✅ BibTeX button (if enabled)
- ✅ DOI/PDF/Code links (if available)
- ✅ Altmetric & Dimensions badges
- ✅ Preview image (if specified in .bib)

## Common BibTeX Keys in Your Bibliography

Quick reference for your papers:

**Preprints:**
- `sharma2023all` - TmIG magnonic crystal (arXiv)
- `khansili2022element` - CeCoIn quantum criticality

**2024:**
- `ojha2024dynamics` - VO₂ phonon dynamics

**2023:**
- `sharma2023magnetic` - TmIG thin films (Materials Letters)
- `sharma2023magnetic1` - YIG thin films (Thin Solid Films)
- `ojha2023charge` - VO₂ charge ordering
- `hissariya2023antisites` - La₂NiMnO₆ magnetization
- `sharma2023micromagnetic` - Skyrmion micromagnetic study

**2022:**
- `sharma2022interfacial` - Interfacial skyrmion review (JMMM)
- `ojha2022observation` - VO₂ V-V dimers

**2018:**
- `sharma2018effect` - Ion irradiation effects (AIP)

## Tips

1. **Order matters**: Papers display in the order you list them
2. **No spaces**: Don't put spaces after commas: `key1,key2` ✓ not `key1, key2` ✗
3. **Section placement**: Add the include wherever makes sense - after abstract, before images, at the end, etc.
4. **Heading optional**: You can use any heading or no heading at all
5. **Reusable**: Use the same include in multiple project files

## Removing Publications

Simply delete or comment out the include line:

```liquid
<!-- {% include project_publications.html keys="sharma2022interfacial" %} -->
```

Or remove the entire section:

```markdown
<!-- 
## Related Publications
{% include project_publications.html keys="..." %}
-->
```
