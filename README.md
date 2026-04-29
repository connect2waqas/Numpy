# NumPy Practice (Jupyter Notebooks)

This repository is a small, hands-on set of Jupyter notebooks where I practice **NumPy**—from creating arrays to reshaping, slicing, and understanding broadcasting. It’s meant to be a learning playground you can open, run, and tweak while you’re getting comfortable with NumPy.

## What’s inside

- **`numpy-lecture1.ipynb`**  
  Core NumPy basics:
  - Creating arrays (`array`, `arange`, `random`, `randint`, `linspace`)
  - Arrays of zeros/ones
  - Reshaping, flattening, and type conversion (`astype`)
  - Array attributes (`ndim`, `shape`, `size`, `dtype`, `nbytes`)
  - Indexing & slicing (2D/3D examples)
  - Iterating through arrays
  - A quick look at memory usage (Python list vs NumPy array)
  - Broadcasting with different shapes

- **`numpy-lecture2.ipynb`**  
  Continuation / more practice material (more NumPy exploration).

- **`full-pracitice-numpy.ipynb`**  
  A fuller practice notebook (end-to-end exercises and experimentation).

## Getting started

### Option 1: Run locally (recommended)
1. Clone the repo:
   ```bash
   git clone https://github.com/connect2waqas/Numpy.git
   cd Numpy
   ```

2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv .venv
   # Windows:
   .venv\Scripts\activate
   # macOS/Linux:
   source .venv/bin/activate
   ```

3. Install dependencies:
   ```bash
   pip install numpy jupyter
   ```

4. Start Jupyter:
   ```bash
   jupyter notebook
   ```
   Then open any `.ipynb` file.

### Option 2: Open in Google Colab
You can also upload the notebooks to Colab and run them in the browser.

## Who is this for

- Beginners learning NumPy fundamentals
- Anyone who wants quick examples of reshaping, slicing, and broadcasting
- Students following along with a NumPy lecture/practice flow

## Notes

- The repo is mainly **Jupyter Notebooks**.
- Notebook outputs may vary because some cells use random number generation.

## Contributing

If you spot a mistake or want to add better examples/exercises, feel free to open an issue or submit a pull request.

## License

No license file is currently included. If you plan to reuse this publicly, consider adding a license (MIT, Apache-2.0, etc.).
