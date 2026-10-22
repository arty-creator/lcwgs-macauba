# lcwgs-macauba

Pipeline de sequenciamento genômico de baixa cobertura (lcWGS) para genômica populacional da macaúba (*Acrocomia aculeata*).

## Pipeline

O fluxo está no notebook [scripts/pipeline_lcwgs_macauba.ipynb](scripts/pipeline_lcwgs_macauba.ipynb) e inclui controle de qualidade, trimming das reads e alinhamento ao genoma de referência.

Requer FastQC, MultiQC, fastp, BWA-MEM2 e SAMtools, além dos arquivos FASTQ e do genoma de referência. Ajuste os caminhos no notebook conforme o ambiente.
