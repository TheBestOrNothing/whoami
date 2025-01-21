# whoami
Two vm required, one is oidc provider and the other is matrix server.
1. oidc provider with reverse proxy, the openresty nginx conf is in the oidc-nginx.conf
2. matrix server with reverse prox, the openresty nginx conf is in the matrix-nginx.conf
3. how to install the openresty, https://openresty.org/en/linux-packages.html#ubuntu
4. the matrix-nginx use lua-resty-openidc to check oauth, https://github.com/zmartzone/lua-resty-openidc?tab=readme-ov-file
5. there are many utilities in the openresty, https://opm.openresty.org/  https://github.com/openresty/lua-resty-redis 
