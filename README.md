# Codon Evolution Simulation

A combined data‐analysis and simulation pipeline for exploring how codon volatility differs between binding and non-binding sites in proteins.

## Repository structure

- `notebooks/`  
  - `analysis.ipynb` – computes codon-usage counts, proportions, statistical tests & plots  
  - `simulation.ipynb` – implements the evolutionary model

- `data/`  
  - **`M-CSA_API_data.csv`** – raw JSON export of manually curated catalytic residues from the M-CSA API  
  - **`Protein_binding_data.csv`** – processed table of UniProt IDs, residue positions and their “binding” vs “non-binding” labels  


- `requirements` – Python dependencies (pandas, numpy, Biopython, plotnine, etc.)

1. **Clone**  
   ```bash
   git clone https://github.com/AdamKuniak/Codon_evolution_simulation.git
