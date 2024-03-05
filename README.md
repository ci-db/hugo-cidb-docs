TEST
# falls Hugo lokal benutzt werden soll

    git submodule update --init
    git submodule update --remote

# Hugo start

    hugo serve --disableFastRender

# mit docker

    cp docker-compose.yaml ../../.    
    cp nginx.conf ../../.    
    cp dev.yaml ../../.

# gitlab deploy

    cp example.gitlab-ci.yml ../../.gitlab-ci.yml