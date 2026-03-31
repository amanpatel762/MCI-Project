# MCI-Project
Designing a Merger Compatibility Index (MCI) for evaluating bank mergers

## Data schema and sample inputs
- `data/schema.yaml`: Field definitions (type, required, description) for a bank profile used by the MCI scoring engine.
- `data/templates/bank_profile_template.csv`: Header-only CSV template aligned to the schema for creating new bank inputs.
- `data/samples/sample_bank_profiles.csv`: Two example bank profiles populated with realistic values for quick testing.

### How to use
1. Copy `data/templates/bank_profile_template.csv` to your working file (e.g., `my_bank_profiles.csv`).
2. Fill each row according to `data/schema.yaml` (ratios are decimals, percentages are 0–100).
3. Use your populated file as input to downstream scoring/analysis notebooks or apps.
