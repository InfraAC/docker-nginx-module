# nginx-module custom build
    docker build --build-arg ENABLED_MODULES="with-http_dav_module" -t nginx-with-http_dav .