# Introduction

Azure Pipeline with Contrast Demonstration

# Pre-Requirements

# Getting Started

## Run from Jenkins

TODO

## Run from Azure

1. Create Azure DevOps account
1. Use this repo

## Run from CLI

1. Clone this repo and cd into it
1. Update ./Manifests/overlays/contrast/contrast_security.yaml
1. Use context: kubectl use context default
1. Create Namespace: kubectl create namespace springboot
1. Deploy: kubectl apply -k ./Manifests/overlays/contrast
1. Get IP: kubectl get services
