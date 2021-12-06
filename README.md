# Digital_pathology_tool_wiki
A collection of links to useful digital pathology tools to summarise, simplify and better communicate the plethora of tools available. 

Task to achieve	Tool name	Tool description	Publication link (if any)	Tool link	Notes
Registration of related images	HistoReg	An ITK tool for rapid registration achieving high registration accuracy in ANHIR challenge.	https://arxiv.org/abs/1904.11929 ; https://ieeexplore.ieee.org/document/9058666 	https://github.com/CBICA/HistoReg	I encountered some difficulties building ITK as described in installation instructions. Issues were resolved on Ubuntu 20.04 with local installation of ITK 4.13.2 using  apt package 
	ANHIR_MW	A Python tool that trials multiple registration methods to achieve high registration accuracy in ANHIR challenge.	https://ieeexplore.ieee.org/document/9058666	https://github.com/MWod/ANHIR_MW	Due to brute force approach, tool is slower than HistoReg. Installation and use is simple. 
Nuclear segmentation	HoverNet	Simultaneous segmentation and classification using a multibranch CNN. 	https://www.sciencedirect.com/science/article/pii/S1361841519301045?via%3Dihub	https://github.com/vqdang/hover_net	
	StarDist	Unet for segmentation of rounded objects, i.e. nuclei.	https://link.springer.com/chapter/10.1007%2F978-3-030-00934-2_30	https://github.com/stardist/stardist	All detected objects will take rounded, star-convex polygon structure
	CellPose	Unet for segmentation of objects – no assumptions of object shape.	https://www.nature.com/articles/s41592-020-01018-x	https://github.com/MouseLand/cellpose	Experience has shown that predicted boundaries extend past the nucleus reflecting the tool objective of predicting cell structure. Beware use in situations with little tolerance for extension past the nuclear membrane.
Preprocessing	Staintools	Tools for processing stains of digital pathology images (i.e. stain normalisation, noise reduction, stain separation)	Documentation: https://staintools.readthedocs.io/en/latest/normalization.html#module-staintools.normalization.macenko	https://github.com/Peter554/StainTools	The pip package recommended is a bit aged and does not follow the structure of the GitHub repo. Advised to test both pip and GitHub versions to determine preference.
![image](https://user-images.githubusercontent.com/44582194/144854888-9f8974be-79d4-4f70-8911-f32becc51469.png)

## All contributions, forks, pull requests, suggestions etc. welcome! Don't be a stranger :-) 
