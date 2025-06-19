### ✅ Step 1: Install R

Download and install R from CRAN:

🔗 [https://cran.r-project.org/](https://cran.r-project.org/)

---

### ✅ Step 2: Install Jupyter via Anaconda (Recommended)

If you don't have Jupyter installed, use Anaconda:

1. Download and install Anaconda:
   🔗 [https://www.anaconda.com/products/distribution](https://www.anaconda.com/products/distribution)

2. Anaconda comes with Python, Jupyter Notebook, and many data science packages.

---

### ✅ Step 3: Install the R Kernel for Jupyter

1. Open **R** or **RStudio**.
2. Run the following R code to install the IRkernel:

```r
install.packages("IRkernel")
IRkernel::installspec()
```

- `IRkernel` allows R to run inside Jupyter.
- `installspec()` registers the R kernel with Jupyter.

✅ You will now see an R option when launching a new notebook in Jupyter.
