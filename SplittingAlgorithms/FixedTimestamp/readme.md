# FIXED TIMESTAMP SPLITTING

## Contacts

   Tommaso Di Noia, tommaso [dot] dinoia [at] poliba [dot] it  
   
   Vito Walter Anelli, vitowalter [dot] anelli [at] poliba [dot] it 
   
   Joseph Trotta, joseph [dot] trotta [at] poliba [dot] it 
   

## Usage

 -dp,--datasetPath <arg>   Dataset path
 
 -mte,--minTest <arg>      Set minimum number of ratings in the test set
 
 -mtr,--minTrain <arg>     Set minimum number of ratings in the training set
 
 -p,--splitPath <arg>      Training and test set folder path
 
 -sp,--splitter <arg>      Name of splitter to use

## Example

java -jar temporalSplitting.jar --datasetPath="toys_amazon/ratings_indexed.tsv" --splitPath="targetFolder/" --splitter="TemporalSplitterWithConstraints" --minTrain="15" --minTest="5" --separator="\t"

