this project is for group 29 these are the commands that were used 
rm test-1 
mv top-5-lowest-temperatures.csv analysed
sort filename.txt | uniq > cleaned_filename.txt
sort satelite_temperature_data.csv | uniq > satelite_temperature_data.csv
sort -t, -k2 -nr satelite_temperature_data.csv | head -n 5 > ../analyzed/top-5-highest-temperatures.csv
sort -t, -k2 -n satelite_temperature_data.csv | head -n 5 > ../analyzed/top-5-lowest-temperatures.csv
grep "Chad" satelite_temperature_data.csv > ../analyzed/country-heat_data.csv
