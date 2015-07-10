# docker-cling

This is a Dockerfile for building CLING, the C++ interpreter.

You can run the C++ interpreter using:

    docker run -i -t tmbdev/cling-local cling

You will probably set up some mounts and change the UID to make this more useful for running C++ scripts.
