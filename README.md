# end-to-end-movie-recommender-system

# How to run ?

### Steps :
**Step 1: Clone the repository**
```bash 
git clone https://github.com/vivek-3369/end-to-end-movie-recommender-system
cd end-to-end-movie-recommender-system
```

**Step 2: Create a Conda environment**
```bash
conda create -p movie python==3.7.10 -y
conda activate movie/
```

**Step 3: Install the backend requirements**
```bash
pip install -r requirements.txt
```

*(Optional) If you face a ModuleNotFoundError regarding `src`, install the local package:*
```bash
pip install -e .
```