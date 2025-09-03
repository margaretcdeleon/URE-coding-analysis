# URE Coding Analysis Project

## Overview
This project contains a comprehensive analysis of Undergraduate Research Experience (URE) coding data exported from NVivo. The analysis includes statistical summaries, visualizations, and detailed breakdowns of coding patterns across research articles.

## Project Structure

### Main Analysis
- `analysis.ipynb` - Jupyter notebook containing all analysis code and visualizations
- `coding matrix.csv` - Original coding matrix exported from NVivo

### Generated Outputs

#### Excel Files
- `comprehensive_coding_analysis.xlsx` - Main analysis file with 4 sheets:
  - Articles_with_Codes: Detailed article analysis with metadata
  - Codes_with_Articles: Code frequency and article associations  
  - Code_Matrix: Full cross-tabulation matrix
  - Summary_Stats: Overall statistics

#### CSV Files
- `articles_with_codes_and_metadata.csv` - Articles analysis with extracted metadata
- `codes_with_article_details.csv` - Codes analysis with frequency statistics
- `coding_matrix_crosstab.csv` - Cross-tabulation matrix
- `article_summary.csv` - Basic article summary
- `code_summary.csv` - Basic code summary

#### Visualizations
- `coding_analysis_visualizations.png` - Comprehensive 8-panel visualization dashboard
- `detailed_coding_analysis.png` - Code co-occurrence and usage pattern analysis

## Key Findings

### Dataset Overview
- **335 articles** analyzed
- **81 different codes** identified
- **Average 8.4 codes per article**
- **2,818 total code applications**

### Universal Codes (used in >50% of articles)
1. Program type (91.94%)
2. Primary Institutional Context (91.64%)
3. STEM (80.0%)
4. 4-Year University (63.28%)

### Code Distribution
- **High frequency** (>50% of articles): 4 codes
- **Medium frequency** (10-50% of articles): 22 codes  
- **Low frequency** (<10% of articles): 55 codes

## Usage

### Running the Analysis
1. Ensure you have the required Python packages installed:
   ```bash
   pip install pandas numpy matplotlib seaborn openpyxl
   ```

2. Open `analysis.ipynb` in Jupyter Notebook or VS Code

3. Run all cells to:
   - Load and analyze the coding matrix
   - Generate comprehensive spreadsheets
   - Create visualizations
   - Export summary files

### Customizing the Analysis
- Modify code groupings in the visualization functions
- Add external metadata by following the instructions in the notebook
- Adjust visualization parameters for different outputs

## Requirements
- Python 3.7+
- pandas
- numpy  
- matplotlib
- seaborn
- openpyxl (for Excel file generation)

## Author
Analysis conducted as part of URE research project.

## Date
Generated: September 2025
