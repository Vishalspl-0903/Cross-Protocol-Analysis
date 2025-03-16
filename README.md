# Cross-Protocol Analysis Using Wireshark
This work explores cross-protocol analysis using Wireshark, focusing on DNS and HTTP interactions to assess network efficiency and implement optimization strategies.

## Project Overview
The analysis investigates how DNS response times influence HTTP request efficiency and evaluates DNS caching as a solution to improve performance.

## Key Features
- Packet capture using Wireshark for detailed analysis.
- Evaluation of DNS-HTTP dependency times.
- Implementation of DNS caching to optimize network performance.
- Visual analysis using scatter plots, histograms, and cumulative average plots.

## Prerequisites
- Python (Recommended version: 3.8 or higher)
- Jupyter Notebook or Google Colab
- Wireshark for packet capture

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/cross-protocol-analysis.git
   ```
2. Navigate to the project folder:
   ```bash
   cd cross-protocol-analysis
   ```
3. Install required libraries:
   ```bash
   pip install pandas matplotlib numpy
   ```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Run the `.ipynb` file step by step, following the provided instructions for:
   - Capturing DNS and HTTP traffic.
   - Analyzing unoptimized vs. optimized dependency times.
   - Visualizing results using scatter plots and histograms.

## Results
- **Scatter Plot:** Shows reduced DNS-HTTP dependency times after caching.
- **Histogram:** Demonstrates a higher frequency of faster HTTP requests in the optimized scenario.
- **Cumulative Average Plot:** Highlights consistent reduction in dependency times over a session with caching.

## Conclusion
DNS caching significantly improves network performance by minimizing delays between DNS responses and HTTP requests. This method enhances user experience, conserves bandwidth, and can be extended to optimize other protocol interactions.

## License
This project is licensed under the MIT License.

