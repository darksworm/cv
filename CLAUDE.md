# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a CV/resume repository using RenderCV YAML format to generate a professional PDF resume. The main file is `cv.yaml` which contains structured CV data.

## Commands

### Generate PDF Resume
```bash
# Install RenderCV if not already installed
pip install rendercv

# Generate the PDF from the YAML file
rendercv render cv.yaml
```

The output PDF will be generated as `Ilmars_Janis_Bluzmanis_DevEx_CV.pdf` as specified in the `rendercv_settings.output_path` field.

## Key Configuration

The YAML file uses the RenderCV schema (https://github.com/rendercv/rendercv) and includes:
- CV content sections: Profile, Experience, Skills, Education, Languages, Interests
- Design configuration: Classic theme with A4 page size
- RenderCV settings: Bold keywords highlighting, custom output path

When updating the CV, maintain the existing YAML structure and respect the schema validation.