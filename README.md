# ModulTech AI-Centive Ontologies

This repository contains semantic vocabularies for explainable mobility predictions developed as part of the ModulTech AI-Centive project.

## Overview

These ontologies provide formal semantic definitions for representing AI-generated mobility predictions with comprehensive explainability data. They enable conversion of ML (mainly GCN) outputs into queryable RDF knowledge graphs that support transparency, auditability, and regulatory compliance requirements.

## Repository Contents

- **`mobility.ttl`** - Mobility Ontology defining trip predictions, users, activities, and confidence metrics
- **`explanation.ttl`** - Explanation Ontology defining explainability data, pattern evidence, and reasoning structures
- **`index.html`** - Complete documentation with ontology specifications, usage examples, and integration guidelines

## Usage

These ontologies are designed for **offline use** in research and development environments. Since the namespace URIs (`http://modultech.eu/aicentive/mobility#` and `http://modultech.eu/aicentive/explanation#`) are primarily used for semantic identification rather than live web resolution, this GitHub repository serves as the primary distribution point for the ontology files.

### Quick Start

1. Download the ontology files for local use
2. Reference the namespace URIs in your semantic applications
3. View `index.html` for detailed documentation and usage examples

### Integration

The ontologies integrate with standard W3C vocabularies including:
- **PROV-O** for provenance tracking
- **TIME Ontology** for temporal relationships  
- **FOAF** for user representation
- **OWL** for formal semantics

## Applications

- Explainable AI for mobility prediction systems
- Semantic conversion of machine learning outputs
- Regulatory compliance for AI transparency requirements
- Research collaboration through standardized vocabularies

## Documentation

The `index.html` file provides comprehensive documentation including:
- Complete ontology specifications
- Usage examples and SPARQL queries
- Integration guidelines
- Namespace reference information

## License

These ontologies are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to:
- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material for any purpose

Under the following terms:
- **Attribution** — You must give appropriate credit and indicate if changes were made

## Citation

If you use these ontologies in your research, please cite:

```
Braşoveanu, A. M. P., Nixon, L. J. B., Scharl, A., Charwat, G., & Prünster, E. (2025).
Explainable mobility prediction in urban transit zones. In *Semantics for Transportation -
Sem4Tra 2025 @ SEMANTICS 2025 EU: 21st International Conference on Semantic Systems*
(September 3–5, 2025, Vienna, Austria).
```

or alternatively

```
ModulTech AI-Centive Ontologies for Explainable Mobility Predictions
Available at: https://github.com/[your-username]/[repo-name]
License: CC BY 4.0
```

## Contact

For questions, contributions, or collaboration opportunities, please contact the ModulTech AI-Centive project team.

---

**Project:** ModulTech AI-Centive Ontologies
**Version:** 1.0  
**Last Updated:** May 2025 (public: since August 2025)
