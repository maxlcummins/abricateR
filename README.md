# abricateR
abricate combinator

## Usage

```
#Load paths to files needed for the script
abricate_path <- "placeholder/output/genotype.txt"
pointfinder_path <- "placeholder/output/pointfinder.txt"
pMLST_data <- "placeholder/output/pMLST.txt"

#Provide output names
output_name <- "ST95_all"
output_dir <- "processed"

#Load abricateR2 script
source("scripts/abricateR2.R")
#Run abricateR
abricateR(
        abricate_in = abricate_path,
        output = output_name,
        output_directory = output_dir,
        writecsv = TRUE,
        pointfinder_data = pointfinder_path,
        pMLST_data = pMLST_data
)
```
