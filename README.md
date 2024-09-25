# learn_linux_by_doing

Task 1:

-ZeeyahOke deleted test-1
 rm ./analyzed/test-1

-hamse-ai moved a file to analyzed directory
 mv top-5-lowest-temparatures.csv ./analyzed/

-hawwa renamed a file 
 mv top5-highest-temparatures.csv top5-highest-temparatures.csv

Task 2:
-JOSHUALU sorted the temperature raw data in a new file in data directory
 ./data/sort satelite_temperature_data.csv | uniq -d 
 ./data/sort satelite_temperature_data.csv | uniq > ./data/satelite_temperature_data_no_duplicates.csv 

-MohamDahALU saved top 5 highest heat tempratures in a file in analyzed
  sort -u ./data/satelite_temperature_data.csv | sort -r -k3 --field-separator="," | head -n 6 | tail +2 > ./analyzed/top-5-highest-temperature.csv 

-MohamDahALU saved top 5 lowest heat tempratures in a file in analyzed
 sort -u ./data/satelite_temperature_data.csv | sort -k3 --field-separator="," | head -n 5 > ./analyzed/top-5-lowest-temparatures.csv

-Remy-cloud saved heat data for Rwanda in a file in the root 
 grep Rwanda ./data/satelite_temperature_data_no_duplicates.csv > ./country-heat_data.csv