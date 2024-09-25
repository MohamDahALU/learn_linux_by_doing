# learn_linux_by_doing

Task 1:

-ZeeyahOke: rm ./analyzed/test-1

-hamse-ai: mv top-5-lowest-temparatures.csv ./analyzed/

-hawwa: mv top5-highest-temparatures.csv top5-highest-temparatures.csv

Task 2:
-JOSHUALU: ./data/sort satelite_temperature_data.csv | uniq -d 
          ./data/sort satelite_temperature_data.csv | uniq > ./data/satelite_temperature_data_no_duplicates.csv 

-MohamDahALU:  sort -u ./data/satelite_temperature_data.csv | sort -r -k3 --field-separator="," | head -n 6 | tail +2 > ./analyzed/top-5-highest-temperature.csv 

