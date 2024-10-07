# notes_from_RNASEQ_workshop

USE PSEDUO COUNTS AS THEY ARE BETTER AND MORE ACCURATE

# First step is to look at the quality of the raw data
Raw data often comes in FASTQ format. We can use tools like FASTQC to assess the quality of the data. Often they will range from good to bad and somewhere in between (i.e., green ticks, red, and orange range)

MultiQC can combine heaps of different reports into one report, which is cool to use at different points of the analysis (e.g., before filtering, after filtering, etc.)


Length of read starts good and then declines over time (very typical) -- trim the ends of the reads 

If the whole read is of low quality - can remove

Delete adapter sequences 

