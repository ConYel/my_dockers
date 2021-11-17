Docker file for the analysis of data from SPORTS, SPAR and other workflows.  
>To run:  
`docker run --rm -v $(pwd):/home/$USER/projects -p 8787:8787 -e PASSWORD=12345 -e USER=$USER -e USERID=$UID rocker_tidyverse_plus_de_pckages:v_3_14`

DockerHub: https://hub.docker.com/r/congelos/rocker_tidyverse_plus_de_pckages
