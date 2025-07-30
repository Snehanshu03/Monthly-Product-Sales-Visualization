# Monthly Product Sales Visualization

A comprehensive project for analyzing and visualizing monthly product sales—now updated for smooth use with **Google Colab**! This tool lets anyone explore sales, revenue, and performance by region, product category, and payment method with easy data visualizations and pivots—even if you use only a browser.

## Downloading the Project

- **Option 1: GitHub ZIP Download**
  1. Visit the project’s GitHub page.
  2. Click the green **Code** button and select "Download ZIP."
  3. Unzip to your preferred folder.

- **Option 2: Clone with Git**
  ```sh
  git clone https://github.com/Snehanshu03/Monthly-Product-Sales-Visualization.git
  cd Monthly-Product-Sales-Visualization
  ```

- **Dataset:**  
  The file `Online-Sales-Data-missing-values.xlsx` is included in the repository.

## Project Structure

| File                                       | Purpose                                                    |
|---------------------------------------------|------------------------------------------------------------|
| `Monthly-Product-Sales-Visualization.ipynb` | Main notebook for data analysis (works in Colab!)          |
| `Online-Sales-Data-missing-values.xlsx`   | Main sales dataset                                         |
| `README.md`                                | Instructions and project overview                          |

## Requirements

*No local installation needed—just use your browser with Google Colab!*

However, if you wish to run locally, you’ll need:

- Python 3.7+
- Libraries: `pandas`, `matplotlib`.

You can install dependencies with:
```sh
pip install pandas matplotlib 
```

## Running the Project in Google Colab

**Quick Start Using Google Colab:**

1. **Open the notebook in Colab**  
   - Go to the repo and locate `Monthly-Product-Sales-Visualization.ipynb`.
   - Click on the notebook file, then press the "Open in Colab" button (or copy the notebook URL and open [colab.research.google.com](https://colab.research.google.com), then select "GitHub" tab and paste the URL).
2. **Upload the dataset**  
   - In the Colab notebook, run the first cell, then use the file upload widget:
     ```python
     from google.colab import files
     uploaded = files.upload()
     ```
   - Select and upload `Online-Sales-Data-missing-values.xlsx` from your computer to the Colab environment.
3. **Continue running each code cell in sequence**  
   - The notebook will:
     - Load and clean the data
     - Generate summary/EDA visuals
     - Show analysis of revenue by region, payment method, and product

**Output:**  
All charts and tables will appear in your Colab browser window!

## Data Format

The Excel file should include:

- Transaction ID, Date, Month, Product Category, Product Name, Units Sold, Unit Price, Total Revenue, Region, Payment Method

With built-in pivot tables summarizing units sold and revenue by category and region.

## Contributing

Contributions are welcome! Open issues or submit pull requests for improvements or bug fixes.

## License

Distributed under the MIT License.

**Tip:** Use the Colab platform for the fastest, most accessible start—no setup required beyond uploading your data file! If you change filenames or columns, update references in the notebook accordingly.

*Ready to explore your sales insights in Colab? Open the notebook, upload your dataset, and see your summary charts in minutes!*

