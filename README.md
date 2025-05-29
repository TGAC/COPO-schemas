# COPO Metadata Schemas

The **COPO-schemas** repository contains a collection of **schemas for various types of metadata** used in the [COPO project website](https://copo-project.org), developed and maintained by the Collaborative OPen Omics (COPO) team at the [Earlham Institute](https://www.earlham.ac.uk).

These schemas define metadata structures and checklists relevant to various omics data types and submission requirements. They serve as a reference for how metadata is structured across COPO's metadata workflows.

## What This Repository Contains 📂

- JSON, YAML and XLSX schemas organised by **metadata type** or **submission checklist**
- Versioned files to track schema evolution over time
- Human-readable definitions and descriptions within each schema
- Schema files used for **validation and rendering** in the COPO web application

> ⚠️ This repository is maintained separately from the COPO project source code, but its schemas are integrated into the COPO platform and used for metadata validation and manifest rendering.

## Schema Usage 🧩

These schemas are used internally by the COPO platform to:
- Drive user-facing metadata manifests
- Validate user-submitted metadata
- Inform data submission to external repositories (e.g. [European Nucleotide Archive (ENA)](https://www.ebi.ac.uk/ena/browser/home), [Zenodo](https://zenodo.org) and [BioImage Archive (BIA)](https://www.ebi.ac.uk/bioimage-archive))

They are not intended for direct use by external tools but may serve as references for integration or review.

## Checklist Types 📌

Each schema aligns with a **checklist** or **metadata category**, such as:
- Single-cell submissions
- Spatial ranscriptomic datasets
- Sample metadata
- Image metadata

## Terminology 📝

Checklists are sometimes referred to interchangeably as manifests. A manifest is essentially a spreadsheet (e.g., CSV or XLSX) that can be filled in with metadata relevant to a particular data type or submission workflow.

## Structure 🛠
The repository is structured as follows:

```
COPO-schemas/
├── images/
│   └── image_schema_main.xlsx
├── sample/
│   ├── sample_checklist_dwc.xml
│   └── sample_checklist_faang.xml
├── single_cell/
│   ├── singlecell_schema_main.json
│   ├── singlecell_schema_main.yaml
│   └── singlecell_schema_main.xlsx
├── LICENSE
└── README.md
```
> All schemas follow a versioning convention (e.g. v0.1, v1, v2, etc.) to track changes over time. Refer to the file names for the most recent version.

## Development & Contribution 🧪

This repository is currently managed by the COPO project team. Contributions or suggestions may be considered via [pull request](https://github.com/TGAC/COPO-schemas/pulls) or [GitHub issues](https://github.com/TGAC/COPO-schemas/issues), especially regarding schema corrections or updates based on evolving standards.

## License 📄

Unless otherwise stated, all schema files are released under the [MIT License](LICENSE).

## Related Resources 🔗

- [COPO web platform](https://copo-project.org)
- [About COPO](https://copo-project.org/about)
- [COPO Documentation](https://copo-docs.readthedocs.io/en/latest)
- [Earlham Institute](https://www.earlham.ac.uk)
- [Single-cell schemas website](https://singlecellschemas.org)
- [Single-cell schemas documentation](https://copo-docs.readthedocs.io/en/latest/submissions/single-cell-submissions.html)

## Related GitHub repositories 🐙

Here are other COPO-related repositories you may find useful:

- [COPO project repository](https://github.com/TGAC/COPO-production)
- [SingleCellSchemas repository](https://github.com/TGAC/SingleCellSchemas)

---

## Contact 📬

For questions, feedback or collaboration enquiries, please contact the COPO team at [ei.copo@earlham.ac.uk](mailto:ei.copo@earlham.ac.uk).