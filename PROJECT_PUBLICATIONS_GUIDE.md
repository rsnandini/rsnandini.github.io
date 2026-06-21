# How to Add Publications to Project Pages

This guide shows you how to manually add publications to any project `.md` file.

## Quick Usage

Add this code block anywhere in your project markdown file (e.g., `_projects/PhD.md`):

```liquid
## Related Publications

<div class="publications">
{% bibliography -f papers.bib --query @*[key=paper_key]* %}
</div>
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

<div class="publications">
{% bibliography -f papers.bib --query @*[key=sharma2022interfacial]* %}
</div>
```

### 3. Multiple Publications

To add multiple papers, use the `||` (OR) operator:

```liquid
<div class="publications">
{% bibliography -f papers.bib --query @*[key=paper1 || key=paper2 || key=paper3]* %}
</div>
```

## Full Examples

### Example 1: PhD Project with 4 Papers

```markdown
---
layout: page
title: Magnetic Thin Films for Spintronics
category: Ph.D.
---

My research focused on magnetic materials...

## Related Publications

<div class="publications">
{% bibliography -f papers.bib --query @*[key=sharma2022interfacial || key=sharma2023magnetic || key=sharma2023all || key=sharma2023magnetic1]* %}
</div>
```

### Example 2: Single Paper

```markdown
---
layout: page
title: Ion Irradiation Study
category: Project
---

This project investigated swift heavy ion effects...

## Related Publications

<div class="publications">
{% bibliography -f papers.bib --query @*[key=sharma2018effect]* %}
</div>
```

### Example 3: Two Papers

```markdown
## Publications

<div class="publications">
{% bibliography -f papers.bib --query @*[key=sharma2023magnetic || key=sharma2023magnetic1]* %}
</div>
```

## What Gets Displayed

The bibliography automatically shows:
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

## Template for Copy-Paste

**Single paper:**
```liquid
## Related Publications

<div class="publications">
{% bibliography -f papers.bib --query @*[key=YOUR_KEY_HERE]* %}
</div>
```

**Multiple papers:**
```liquid
## Related Publications

<div class="publications">
{% bibliography -f papers.bib --query @*[key=KEY1 || key=KEY2 || key=KEY3]* %}
</div>
```

## Tips

1. **Spacing**: No extra spaces needed around `||` - `key=a||key=b` works fine
2. **Order**: Papers display in the order they appear in your `.bib` file, not the order you list them
3. **Heading**: Use any heading you want - "Publications", "Related Work", "Papers", etc.
4. **Placement**: Add anywhere in your project file - after abstract, before images, at the end

## Removing Publications

Simply delete or comment out the code block:

```liquid
<!-- 
## Related Publications
<div class="publications">
{% bibliography ... %}
</div>
-->
```
