# Python_GSEA-GUI_Hw6

# Description
This is a simple, Python-based graphic interface application implying GSEA algorythm

# Code structure
## *GSEA* function
This is a simple function for GSEA algorythm performance for transcript enrichment analysis by Kolmogorov-Smirnov test. The code body has been benevolently provided by Eugene Bakin of Bioinformatics Institute.

## *App* class
A simple GUI object builder. Apart from class constructor, it bears following functions:
+ *initUI*: stands for window geometry. coloring and textbar and button offset;
+ *on_click*: connects *GSEA* function and button pushing event
+ *closeEvent*: asks user whether they are sure to quit the app.

# Visual style
![Overview](https://github.com/PreacherCasy/Python_GSEA-GUI_Hw6/blob/master/Overview.png)
![Leaving Pop-Up](https://github.com/PreacherCasy/Python_GSEA-GUI_Hw6/blob/master/Leaving.png)

# Acknowledgements
Eugene Bakin of BI for Python crash course and GSEA algorythm realization
