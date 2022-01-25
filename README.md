## In this Github repo I provide a genome assembly and annotation pipeline. Beside the code, the bits of data added in here are public, already published, and usually downloaded form the [SRA](git@github.com:Gian77/Genome-work.git) archive.

# Acknowledgement

## I want to thank all the people that shared their code with me, I am greatfull to all of you and to one of you in particular.

# Genome Assembly

## I will divide this pipeline in many steps/scripts as I used to run them separately. But, I will also show how to combine them in chunks so they can the results of one process in one run. For examplem the *Preprocessing* step includes *download the data*, *verify transfer*, and *check general quality*.

# Before starting you need

* ## Download databases

* ### NCBI

For NCBI database like `nt`, and `taxdb` please look in the [BLAST-work-tools](https://github.com/Gian77/BLAST-work-tools) repo.

* ### BUSCO

For [BUSCO](https://busco.ezlab.org/) database:

https://busco-data.ezlab.org/v5/data/lineages/ <br>

For just the bacteria or some bacterial group you can select:

https://busco-data.ezlab.org/v5/data/lineages/*bacteria*.tar.gz <br>

Some examples:

https://busco-data.ezlab.org/v5/data/lineages/bacteria_odb10.2020-03-06.tar.gz <br>
https://busco-data.ezlab.org/v5/data/lineages/acidobacteria_odb10.2020-03-06.tar.gz <br>
https://busco-data.ezlab.org/v5/data/lineages/alphaproteobacteria_odb10.2021-02-23.tar.gz <br>
https://busco-data.ezlab.org/v5/data/lineages/betaproteobacteria_odb10.2021-02-23.tar.gz <br>
https://busco-data.ezlab.org/v5/data/lineages/coriobacteriales_odb10.2020-03-06.tar.gz <br>
https://busco-data.ezlab.org/v5/data/lineages/coriobacteriia_odb10.2020-03-06.tar.gz <br>
https://busco-data.ezlab.org/v5/data/lineages/corynebacteriales_odb10.2020-03-06.tar.gz <br>
https://busco-data.ezlab.org/v5/data/lineages/cyanobacteria_odb10.2021-02-23.tar.gz <br>
https://busco-data.ezlab.org/v5/data/lineages/deltaproteobacteria_odb10.2021-02-23.tar.gz <br>

* ## Install softwares
