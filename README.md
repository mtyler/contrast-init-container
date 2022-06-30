# Introduction

Azure Pipeline with Contrast Demonstration

# Pre-Requirements

-

# Getting Started

# Run

1. Clone this repo and cd into it
2. Update ./Manifests/overlays/contrast/contrast_security.yaml
1. Use context: kubectl use context default
1. Create Namespace: kubectl create namespace springboot
3. Deploy: kubectl apply -k ./Manifests/overlays/contrast
4. Get IP: kubectl get services
