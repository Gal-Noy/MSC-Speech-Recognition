# MSc Speech Recognition

Course exercises for *Introduction to Speech Recognition*.

## Exercise 1

The solution is in [`ex_1/solution.ipynb`](ex_1/solution.ipynb); its four input CSV files are in the same folder.

### Setup with uv

From the repository root:

```bash
uv sync
cd ex_1
uv run --project .. jupyter lab
```

Open `solution.ipynb`, select the project environment's Python kernel, then **Run All Cells**.

The notebook contains the executable solutions and plots. The report source is [`ex_1/report.tex`](ex_1/report.tex), with its images in `ex_1/figures/`.

To compile the PDF, run `pdflatex report.tex` from the `ex_1` directory.
