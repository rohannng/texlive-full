# texlive-full
Docker image for texlive-full on latest ubuntu/

## Build

    docker build --tag rohannng/texlive-full .

## Run

Mount current dir with your tex filename.tex and run

    docker run \
    --volume $(pwd):/data \
    rohannng/texlive-full \
    xelatex filename.tex