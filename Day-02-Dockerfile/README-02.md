#Day 02 - Docker file

##Date 2026 - 02 - 09

- Created first Dockerfile
- Built custom Python image
- Understood commands (FROM, WORKDIR, COPY, CMD)
    1. FROM (Start from an existing image)
    2. WORKDIR (Default folder inside container)
    3. COPY (Bring files into image)
    4. CMD (Default command when container runs)
       
- Ran container successfully

-Commands Used
  1. docker built -t <image-name>
  2. docker run <image-name>
  3. docker rmi (for deleting images)
  4. docker rm (for deleting container)
  5. docker exec -it <id> /bin/sh (to get inside the container and work)
     
