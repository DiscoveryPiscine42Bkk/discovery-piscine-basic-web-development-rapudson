#!/bin/bash
# filepath: ex05/build.sh

if [ $# -eq 0 ]; then
    echo "No arguments supplied"
else
    for arg in "$@"
    do
        mkdir -p "ex$arg"
    done
fi
chmod +x ex05/build.sh
./ex05/build.sh 01 02 03
# # Output: Creates directories ex01, ex02, ex03
# ls -d ex0*
# # Output: ex01  ex02  ex03