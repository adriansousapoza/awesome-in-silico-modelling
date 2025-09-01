# Contributing to Awesome In Silico Modelling

Thank you for your interest in contributing to this curated list! Your contributions help keep this resource valuable and up-to-date for the research community.

## How to Contribute

### Adding a New Entry

1. **Fork** the repository
2. **Create** a new branch for your contribution
3. **Add** your entry following the format guidelines below
4. **Submit** a pull request with a clear description

### Entry Format

Each entry should follow this format:
```markdown
- **Title** (Year) — Brief description highlighting key methodology and application domain. [[paper](DOI-or-URL)] [[code](GitHub-URL)] [[optional-additional-links]]
```

### Entry Requirements

- **Paper**: Must be peer-reviewed or a well-documented preprint from reputable venues (Nature, Science, Cell, PLOS, Bioinformatics, bioRxiv, arXiv, etc.)
- **Relevance**: Must focus on in silico perturbation modeling or gene regulatory network inference
- **Code availability**: Strongly preferred but not mandatory
- **Recency**: Generally within the last 10 years, with exceptions for foundational work
- **No duplicates**: Check existing entries before adding

### Description Guidelines

- Keep descriptions **concise** (1-2 sentences)
- Highlight the **key methodology** (transformer, VAE, optimal transport, etc.)
- Mention **data modalities** when relevant (scRNA-seq, multi-omics, etc.)
- Use **neutral, factual language**
- Avoid marketing terms or subjective claims

### Categorization

Place entries in the most appropriate category:

**Perturbation Modelling:**
- Transformer-Based Models: Foundation models, attention mechanisms
- Variational & Latent Models: VAEs, latent space approaches
- Optimal Transport & Manifold Methods: OT, Wasserstein, manifold learning
- Graph & Attention Models: GNNs, graph transformers

**Gene Regulatory Network Inference:**
- Single-Cell Methods: scRNA-seq specific approaches
- Tree-Based & Ensemble Methods: Random forests, boosting
- Deep Learning Approaches: Neural networks, deep architectures

### Quality Standards

- Entries must represent **significant methodological contributions**
- Avoid listing every minor variant or application paper
- Prioritize methods with **demonstrated impact** (citations, adoption, benchmarks)
- Include **diverse approaches** rather than overrepresenting single methodologies

### Pull Request Guidelines

- **One entry per PR** when possible
- Use descriptive commit messages
- Ensure all links are functional
- Check that awesome-lint passes (if configured)
- Provide context in PR description about why the entry is valuable

### Updating Existing Entries

- Fix broken links
- Update publication status (preprint → published)
- Add code repositories when they become available
- Correct factual errors

### What Not to Include

- Commercial software without academic publication
- Blog posts or informal tutorials as primary references
- Duplicate methods with minimal novel contributions
- Off-topic papers (general ML, basic bioinformatics)
- Purely application papers without methodological novelty

## Content Standards

### Writing Style
- Use consistent formatting throughout
- Employ British or American English consistently
- Use present tense for descriptions
- Keep technical jargon accessible

### Link Standards
- Always use DOI links for published papers when available
- Prefer official repository links over personal forks
- Use HTTPS URLs
- Verify all links work before submitting

## Review Process

All contributions will be reviewed for:
1. **Relevance** to the list's scope
2. **Quality** of the paper/method
3. **Formatting** consistency
4. **Link** functionality
5. **Uniqueness** (not already listed)

## Questions?

If you're unsure about whether something belongs in the list or have questions about formatting, please:
- Open an issue for discussion
- Check existing entries for examples
- Review the README for scope clarification

## Recognition

Contributors will be acknowledged in the repository. Significant contributors may be listed in a contributors section.

Thank you for helping maintain this valuable resource for the research community!