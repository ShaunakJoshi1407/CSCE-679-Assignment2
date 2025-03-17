# CSCE-679-Assignment2
Assignment 2 for CSCE-679 (Data Visualization)

This repository contains the solutions for the Level 1 and Level 2 challenges of the data visualization assignment.

## Level 1: Year/Month Heatmap
The visualization for Level 1 can be accessed [here](https://observablehq.com/d/141b7a17dac7f382).  
It demonstrates a heatmap showing monthly maximum and minimum temperatures across years.

## Level 2: Improved Heatmap with Daily Changes
The visualization for Level 2 can be accessed [here](https://observablehq.com/d/538299c2326aca89).  
It includes an improved heatmap with embedded line charts in each cell to show daily temperature variations.

---

### How to Use
- Visit the above links to interact with the visualizations directly on Observable.
- For more details about the implementation, refer to the code in the folders Level 1 and Level 2.

## Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/ShaunakJoshi1407/CSCE-679-Assignment2.git
cd CSCE-679-Assignment2
```

### 2. Extract the Archive
```bash
cd Level2  # or Level1
tar -xvzf 538299c2326aca89.tgz
cd <extracted-folder-name>  # replace with actual folder name
```

### 3. Run with http-server or python3
```bash
npm install -g http-server
http-server -p 8000
```

```bash
python3 -m http.server 8000
```

Go to http://localhost:8000 to view the results.

Make sure to install python3 /npm / node if not installed already. 

Run the server from the folder that contains the index.js and the index.html files.
