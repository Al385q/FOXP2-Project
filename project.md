First we create a conda envirmonet and if the enviroment already exist we activate the envioroment.
<img width="800" alt="Screenshot 2023-11-08 at 2 44 51 PM" src="https://github.com/Al385q/FOXP2-Project/assets/147442178/e8b47683-0d96-4f18-b775-a7ab81b09dc3">
Obatain the .fasta data set by from a reliable source.
I use the nano command to create files and copied my data from NCBI.
Use the awk command to get rid of the unnecessary stuff in the header of eachfile.
<img width="564" alt="Screenshot 2023-11-09 at 1 00 14 PM" src="https://github.com/Al385q/FOXP2-Project/assets/147442178/413f121c-d099-4d81-9378-4e7d9c4502c5">

combine all the files into one file.

<img width="576" alt="Screenshot 2023-11-08 at 10 36 32 PM" src="https://github.com/Al385q/FOXP2-Project/assets/147442178/a5028a41-9561-4c83-b7d4-d67e0d3b87c8">

submit a script to align the all the sequences in your file.

<img width="589" alt="Screenshot 2023-11-09 at 1 29 51 PM" src="https://github.com/Al385q/FOXP2-Project/assets/147442178/52ea1eaf-8670-419f-bf1a-31c391b83fb4">

Then we will submit a script to run iq tree on our output file from the last script 

<img width="574" alt="Screenshot 2023-11-15 at 1 05 28 AM" src="https://github.com/Al385q/FOXP2-Project/assets/147442178/79f2644a-60e9-4b80-b916-57130d4a22f8">

Use the cat command to print the file with contree at the end of it and then copy the results.

<img width="571" alt="Screenshot 2023-11-16 at 12 09 57 PM" src="https://github.com/Al385q/FOXP2-Project/assets/147442178/c3f7564d-a2c3-4968-a719-84c00af0a97e">

Paste the contree text into the "" after ssh_tree in R studio

<img width="1047" alt="Screenshot 2023-11-16 at 12 28 11 PM" src="https://github.com/Al385q/FOXP2-Project/assets/147442178/100d4332-76be-4567-900f-c279528bc4fd">

Then you will see the graph in R studio

<img width="1099" alt="Screenshot 2023-11-16 at 1 53 37 PM" src="https://github.com/Al385q/FOXP2-Project/assets/147442178/29ea6783-4936-4ee5-a168-780e40a32c94">






