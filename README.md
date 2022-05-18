# Intelisoft FHIR Training Implementation Guide

## Overview
See Published IG here: https://intellisoft-consulting.github.io/FHIR-training-ig-template

## Building Locally
### 1. Install nodejs
https://nodejs.org/en/download/

### 2. Install Ruby
Install ruby and ruby gems: https://www.ruby-lang.org/en/documentation/installation/

### 3. Install Jekyll gem
    gem install jekyll

### 4. Install Sushi
    npm install -g fsh-sushi
    sushi --help

### 4. Install Java
https://java.com/en/download/help/download_options.html

### 5. Update IG Publisher
Unix:

    ./_updatePublisher.sh
    
Windows:

    _updatePublisher.bat

### 6. Run IG Publisher
Unix:

    ./_genonce.sh
    
Windows:

    _genonce.bat

### 7. Open Published IG
Unix

    Open `./output/

Windows

    start output/
