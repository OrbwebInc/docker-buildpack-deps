
1. choose folder
2. `docker build -t orbweb/orbweb-agent-buildpack-deps:thecus-n7770 .`

# issue

目前 jessie / stretch 的版本, 因為 libz.so.1 中的 GLIBC_2.14 版本過高, 無法放入 thecus 中