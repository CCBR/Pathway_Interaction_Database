# Pathway_Interaction_Database

This a screen scrape backup of the Pathway Interaction Database from 25 September 2010.  It includes html files and images.

See the original PID paper here : https://www.nature.com/articles/npre.2008.2243.1
or and PMID at https://pubmed.ncbi.nlm.nih.gov/18832364/

"The Pathway Interaction Database ( PID .... ) is a freely available collection of curated and peer-reviewed pathways composed of human molecular signaling and regulatory events and key cellular processes. Created in a collaboration between the US National Cancer Institute and Nature Publishing Group, the database serves as a research tool for the cancer research community and others interested in cellular pathways, such as neuroscientists, developmental biologists and immunologists."

It was created by Carl Schaefer's gang at the Center for Biomedical Informatics and Information Technology (CBIIT) of the National Cancer Institute.

Created with: 
split -b 24M pid.tar.bz2 chunk

To recreate the bzip2 tarball download the chunk* files and then run this command:
cat chunk* > pid.tar.bz2

Then untar the pid.tar.bz2 file with this command:
tar xvf pid.tar.bz2

The full listing of the files is in the manifest file.

