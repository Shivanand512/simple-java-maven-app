#!/bin/bash

set -e

echo "Starting the build process..."

mvn -B -DskipTests clean package

if [ $? -eq 0 ]; then
    echo "Build completed successfully!"
else
    echo "Build failed!"
    exit 1
fi
