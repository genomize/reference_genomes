# Genomize reference genomes

Public reference-genome FASTAs for the **Genomize Compression** desktop app.

Each release asset is a gzip-compressed reference FASTA mirrored from its
canonical public source (Ensembl / UCSC / T2T Consortium) so the desktop app
can download it quickly and reliably. Every file is verified by SHA-256 after
download; the authoritative name / hash / variant for each is in the app's
`genomes.py` catalog.

These are open, freely-redistributable reference assemblies — no proprietary
data lives here.

## Why a separate public repo

The Genomize codec and GUI are private. This repo holds only public reference
data, kept separate so the desktop app can fetch assets from unauthenticated
release URLs.
