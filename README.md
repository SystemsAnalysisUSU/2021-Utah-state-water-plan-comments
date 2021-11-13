# Comments on 2021 draft Utah state water plan

R coding effort to produce a bar plot of Utah water provider use ranked from largest to smallest. This plot supports two comments submitted about the draft state water plan.

## Quick guide: Open the file **[UtahMunicipalIndustrialData-WaterPlanComment.pdf](https://github.com/SystemsAnalysisUSU/2021-Utah-state-water-plan-comments/raw/main/UtahMuncipalIndustrialData-WaterPlanComment.pdf)**. 

Dr. David E. Rosenberg

david.rosenberg@usu.edu | [@WaterModeler](https://twitter.com/WaterModeler)

November 13, 2021

Utah State University

## Directions to View Results
1. Open the file **UtahMunicipalIndustrialData-WaterPlanComment.pdf**
2. The PDF file is auto-generated and has documentation/explanation of methods and results.

## Requirements
* R version 4.1.1. Download from https://cran.r-project.org/.
* R Studio 1.1.456. Download from https://www.rstudio.com/.

## Directions to Reproduce Results
1. Download this repository to your local machine (towards top of webpage, click green **Code** button => **Download Zip**). Unzip contents.
1. Download and install R and RStudio (see Requirements).
1. Open the **DataAnalysis.Rproject** file. R Studio will open.
1. Select the tab for the R Markdown file **UtahMunicipalIndustrialData-WaterPlanComment.Rmd** and click **Knit**.
1. The code will generate a single PDF file with results and documentation. The PDF file will have the same filename as the .Rmd file.

## Explanation of Contents
1. Data files downloaded from UDWR data portal at  https://dwre-utahdnr.opendata.arcgis.com/pages/municipal-and-industrial-data
	1. **2015_Municipal_and_Industrial_Water_Use_Database.csv**: data for 2015.
	1. **2016_Municipal_and_Industrial_Water_Use_Database.csv**: data for 2016.
	1. **2017_Municipal_and_Industrial_Water_Use_Database.csv**: data for 2017.
	1. **2018_Municipal_and_Industrial_Water_Use_Database.csv**: data for 2018. Column headers for 2018 changed from prior years.
1. **2016-2018Population-UDWR.xlsx**: Population data downloaded from UDWR data portal
1. **2019-Population-UDWR.xlsx**: Population data for 2019.
1. **df2019.csv**, **dfAllYears.csv**, **dfAllYearsSort.csv**, **dfReductions.csv**: data frames spit out when run the R code
1. **HighlightCities.xlsx**: List of Utah water providers to show in bar plot in red.
1. **Population compare WR vs WRE.xlsx**: I don't remember what this is. Not used by the code.
1. **PopulationGrowth-AppendixC.xlsx**: Plot of Garder center population figures shown in the draft plan. Some scratch calculations.
1. **Rosenberg-ConstructiveFeedbackOn2021-UtahWaterPlan.docx**: Text feedback on the plan. Includes the figure.
1. **UtahMunicipalIndustrialData-WaterPlanComment.pdf**: Pdf generated with bar plot when knit the **UtahMunicipalIndustrialData-WaterPlanComment.Rmd** file (
1. **UtahMunicipalIndustrialData-WaterPlanComment.Rmd**: R markdown file with code. When knit, generates the file **UtahMunicipalIndustrialData-WaterPlanComment.pdf** (see Directions to Reproduce results).
1. **UtahMunicipalIndustrialUse_InitAnalyis.r**: R file version of .Rmd file. Also generates additional plots/histograms/etc. To run, open R Studio and open this file. Select all the code (Ctrl-A), and run (Ctrl-enter or click the **Run** button on the tool bar below the file tabs). The results will generate in the console.

## License

BSD-3-Clause (https://github.com/dzeke/ColoradoRiverFutures/blob/master/LICENSE). Available to use, modify, distribute, etc. for free.
All modified or derivative products must use the same BSD-3-Clause license. This license keeps this work in the public domain forever.

## Requested Citation
David E. Rosenberg (2021). "Comments on draft 2021 Utah State Water Plan." https://github.com/SystemsAnalysisUSU/2021-Utah-state-water-plan-comments.
