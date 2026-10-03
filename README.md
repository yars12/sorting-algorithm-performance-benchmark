# Sorting Algorithm Performance Benchmark

A Python benchmarking project comparing the runtime behavior of three classic **O(n²)** sorting algorithms.

## Algorithms

- Bubble Sort with early-exit optimization
- Selection Sort
- Insertion Sort

## What the Project Does

The benchmark generates random integer arrays and measures each algorithm across input sizes from **50 to 1,000 elements**. Each size is tested **5 times**, and the median runtime is recorded to reduce the effect of timing noise.

Running the benchmark creates:

- `results.csv` — median runtime measurements
- `sorting_times.png` — runtime comparison visualization

## Technologies

- Python
- NumPy
- Pandas
- Matplotlib
- Algorithm Analysis

## Files

- `algorithms.py` — implementations of Bubble, Selection, and Insertion Sort
- `benchmark.py` — timing experiment and visualization workflow
- `requirements.txt` — project dependencies

## Run the Project

```bash
pip install -r requirements.txt
python benchmark.py
```

## Skills Demonstrated

Algorithms · Data Structures · Runtime Analysis · Benchmarking · Python · Data Visualization
