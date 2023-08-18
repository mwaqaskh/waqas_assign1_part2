# waqas_assign1_part2

# Step 1 (5 marks): Used the docker image from Part 1
Done
# Step 2 (20 marks): Run the Docker Container
Docker is running with any error
![image](https://github.com/mwaqaskh/waqas_assign1_part2/assets/39801941/53c91f58-0210-44fd-a597-6cb6697064c9)


# Step 3 (20 marks): used all below Docker Container Commands

■ 'docker ps' command to list all running containers
![image](https://github.com/mwaqaskh/waqas_assign1_part2/assets/39801941/b741890d-5e0b-4e1e-b45e-d09e82b8e576)

■ 'docker stop' command to stop a running container

docker stop d76c5bcb653b29241a636ef2915009989054913b0e2d5190fa67c9650142eff9                                                                                                  ─╯
d76c5bcb653b29241a636ef2915009989054913b0e2d5190fa67c9650142eff9
![image](https://github.com/mwaqaskh/waqas_assign1_part2/assets/39801941/c7306765-c113-4dc5-8407-a8bddca4077b)

■ 'docker rm' command to remove a stopped container
docker remove d76c5bcb653b29241a636ef2915009989054913b0e2d5190fa67c9650142eff9                                                                                                ─╯
d76c5bcb653b29241a636ef2915009989054913b0e2d5190fa67c9650142eff9
container removed

■ 'docker logs' command to view the logs of a container
docker logs 39f1da1d180f16f13dab83abf39e53164ade9fe8ee6e32a28a24b12b9305dc97                                                                                                  ─╯
Watching for file changes with StatReloader
[18/Aug/2023 15:47:50] "GET / HTTP/1.1" 200 6
[18/Aug/2023 15:48:00] "GET / HTTP/1.1" 200 6
[18/Aug/2023 15:48:07] "GET / HTTP/1.1" 200 6
[18/Aug/2023 15:48:08] "GET / HTTP/1.1" 200 6
[18/Aug/2023 15:48:14] "GET / HTTP/1.1" 200 6
[18/Aug/2023 15:48:23] "GET / HTTP/1.1" 200 6
[18/Aug/2023 15:48:44] "GET / HTTP/1.1" 200 6


■ 'docker inspect' command to view the details of a container
■ 'docker exec' command to execute a command inside a running container
■ 'docker attach' command to attach to a running container
■ 'docker commit' command to create a new image from a container
■ 'docker cp' command to copy files/folders between the container and the
host
■ 'docker stats' command to view the resource usage of containers
■ 'docker top' command to view the running processes inside a container
■ 'docker start' command to start a stopped container
■ 'docker pause' command to pause a running container
■ 'docker unpause' command to unpause a paused container
■ 'docker rename' command to rename a container
■ 'docker wait' command to wait for a container to exit and then display its
exit code
■ 'docker attach' command to attach local standard input, output, and error
streams to a running container
■ 'docker port' command to display the public-facing port that a container is
listening on
■ 'docker update' command to update a container's resource limits
■ 'docker restart' command to restart a running container
