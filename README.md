# Tone of Voice Engine & Standards Generator

An interactive tool for exploring tone of voice spectrums and generating detailed content standards with granular sub-dimension tracking.

## Overview

This tool helps content designers, UX writers, and teams establish and document their tone of voice positioning. It provides:

- **Interactive spectrum exploration** across 5 tone dimensions (Playful↔Serious, Casual↔Formal, Direct↔Indirect, Warm↔Cool, Energetic↔Calm)
- **Granular sub-dimension tracking** with 4 unique sub-dimensions per spectrum
- **Linguistic device guidance** with definitions, examples, and UX context
- **Automated content standard generation** following schema v2.0
- **Anti-pattern detection** to identify conflicting tone signals

## Features

### Tone Spectrum Configuration
- Slide to position your tone on a 0-100 scale
- See real-time updates across 4 sub-dimensions
- Explore 50+ linguistic devices with detailed examples
- Click any device to see definition, examples, and UX impact

### Content Standard Generation
- Generate comprehensive content standards (v2.0 format)
- Includes sub-dimension breakdown with positioning and devices
- Provides anti-patterns to avoid
- Contains validation rules and testing criteria
- Export as markdown or copy to clipboard

### Schema Documentation
- View the complete v2.0 schema structure
- Copy schema template for reference
- Machine-readable validation rules (JSON/YAML)

## Using the Tool

1. **Select a spectrum** using the tabs (e.g., Playful vs. Serious)
2. **Position the slider** to your desired tone (0-100)
3. **Review sub-dimensions** to see how each contributes to overall tone
4. **Explore devices** by clicking on any to see examples and impact
5. **Generate standard** by clicking "Create a content standard"
6. **Configure details** (scope level, owner, domain, content types)
7. **Generate and download** your content standard

## Technology

- Pure HTML, CSS, and JavaScript
- No dependencies or build process
- Fully client-side (no server required)
- Mobile-responsive design

## Content Standard Schema

Generated standards follow the **Tone of Voice Content Standard Schema v2.0**, which includes:

- Metadata with versioning
- Context and scope definition
- Primary positioning with rationale
- Sub-dimension breakdown (4 dimensions per spectrum)
- Linguistic guidance (primary devices, secondary devices, anti-patterns)
- Content patterns and examples
- Implementation guidelines with validation rules
- Testing criteria
- Maintenance schedule

See `standard_schema.md` for complete documentation.

## Project Structure

```
/
├── Tone_tool.html              # Main application
├── walkthrough.html            # Slide deck explaining the tool
├── standard_schema.md          # v2.0 schema specification
├── video_script.md             # Presentation script
├── Tone_standard.md            # v1.0 example output (legacy)
├── Tone_standard_v2_example.md # v2.0 example output
├── CHANGELOG.md                # Version history
└── README.md                   # This file
```

## About

This tool was built to explore new approaches to documenting and implementing tone of voice standards in content design work. It demonstrates how AI-assisted prototyping can help content designers build custom tools for their workflows.

The focus is on:
- **Granularity**: Breaking tone into measurable, actionable sub-dimensions
- **Specificity**: Linking abstract tone concepts to concrete linguistic devices
- **Usability**: Providing machine-readable validation rules alongside human guidance
- **Experimentation**: Testing new frameworks for tone of voice work

## Feedback

This is an experimental tool. Feedback, suggestions, and questions are welcome!

---

**Version**: 2.0
**Last Updated**: 2025-10-29
**Status**: Experimental prototype
