# 🎰 HubSpot Dummy Data Generator

After registering a new account in the HubSpot, it contains almost no data, so the reports eventually have no figures.

This notebook generates dummy data for companies, contacts, deals, tickets, and line items as a downloadable Excel file.

Once the data has been imported to the HubSpot, the following reports can be generated:
* Closed revenue by month with deal total and closed revenue breakdown
* Closed deal revenue amount by source over time
* Deal stage weighted revenue per day vs. goal
* Deal created totals vs. goal
* Company revenue by close date with source breakdown
* Ticket totals by status


## Run the notebook in your browser via JupyterLight (WASM)

1. Open https://jupyter.org/try-jupyter/notebooks/index.html?fromURL=https://raw.githubusercontent.com/IvanRublev/hubspot_dummy_data_generator/refs/heads/master/hubspot_dummy_data_generator.ipynb in a new tab

2. Wait for the JupyterLight environment to start and select the _Python (Pyodide)_ kernel

3. Select menu "Run - Run All Cells" and follow the instructions in the notebook


## Run the notebook locally

1. Install Python (version 3.11 or higher) from [python.org](https://www.python.org/downloads/)

2. Clone or download this repository
   ```bash
   git clone https://github.com/IvanRublev/hubspot_dummy_data_generator.git
   cd hubspot_dummy_data_generator
   ```

3. Create a virtual environment
   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment
   
   On Windows:
   ```bash
   venv\Scripts\activate
   ```
   for PowerShell
   ```bash
   venv\Scripts\Activate.ps1
   ```

   On macOS/Linux:
   ```bash
   source venv/bin/activate
   ```

5. Install Jupyter Notebook
   ```bash
   pip install jupyter notebook
   ```

6. Start Jupyter Notebook
   ```bash
   jupyter notebook
   ```

   - Your default web browser should automatically open, if not, copy the URL shown in the terminal (usually `http://localhost:8888`)
   - Navigate to and open `hubspot_dummy_data_generator.ipynb`

7. Run the notebook
   - Select menu "Run - Run All Cells"
   - Follow the instructions within the notebook


## License

Copyright © 2025 Ivan Rublev

This notebook is licensed under the [MIT license](https://mit-license.org/license.txt)


