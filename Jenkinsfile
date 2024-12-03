#!/bin/bash

# Exit immediately if a command exits with a non-zero status
set -e

# Print a message indicating the start of the build process
echo "Starting the build process..."

# Clean and build the Maven project without running tests
mvn -B -DskipTests clean package

# Print a success message
if [ $? -eq 0 ]; then
    echo "Build completed successfully!"
else
    echo "Build failed!"
    exit 1
fi
