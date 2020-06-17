# Overview

**Title:** Doreme Doe  
**Category:** Web  
**Flag:** libctf{1d2767bb-64fb-48b3-bd39-31659e959dc5}  
**Difficulty:** Trivial  

# Usage

The following will pull the latest 'elttam/ctf-doreme-doe' image from DockerHub, run a new container named 'libctfso-doreme-doe', and publish the vulnerable service on port 80:

```sh
docker run --rm \
  --publish 80:80 \
  --name libctfso-doreme-doe \
  elttam/ctf-doreme-doe:latest
```

# Build (Optional)

If you prefer to build the 'elttam/ctf-doreme-doe' image yourself you can do so first with:

```sh
docker build ${PWD} \
  --tag elttam/ctf-doreme-doe:latest
```

