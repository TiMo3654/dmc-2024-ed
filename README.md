# Additional Code Resources to "A Review on Design Methodologies for Power Electronics and the Bridge to VLSI EDA"

This repo contains the code for text mining of research papers on design automation for power electronics. The results have been published on the IEEE DMC2024 in Grenoble, France.

If the code supports your research, please consider citing the paper. Thanks!

```
@INPROCEEDINGS{Moldenhauer24,
  author={Moldenhauer, Till and Uhlmann, Yannick and Scheible, Jürgen},
  booktitle={2024 IEEE Design Methodologies Conference (DMC)}, 
  title={{A Review on Design Methodologies for Power Electronics and the Bridge to VLSI EDA}}, 
  year={2024},
  volume={},
  number={},
  pages={1-6},
}
```

## 1. Creating the Database

The Jupyter Notebook *database.ipynb* contains the code to query IEEE Xplore with a defined search string. To target specific journal our conferences the publication numbers can be used. Depending on the response size of your request, the query can take up to 30 Minutes or more.

## 2. Labeling the Research Articles

Once the database is complete, the functions and definitions in the *labeling.ipynb* notebook can be utilized. By adding different rules or altering the wording, the code can be adapted to any topic.

## 3. Analysis

Given the tags, one can analyze trends, distributions or anything else. In the three remaining notebooks some examples are shown.

# Contact

Feel free to contact or ask questions! Best of luck for your research endeavours! :rocket: