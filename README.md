mac os: you need
curl -OL https://raw.github.com/narkoleptik/os-x-berkeleydb-patch/master/atomic.patch
and
patch {project}/dbinc/atomic.h < atomic.patch

cd build_unix
make
make install

