# filter taxonomy insex form blast output

sed '/OTU/s/\t/\|/g' taxids_export_Alveolata.txt | cut -f 1,7 -d "|" | sed '/OTU/s/|/\t/g' | awk '$3=$1' | head 

sed '/OTU/s/\t/\|/g' taxids_export_Alveolata.txt | cut -f 1,7 -d "|" | awk '$3=$1' | cut -f 2 -d "|" | uniq -c | head




