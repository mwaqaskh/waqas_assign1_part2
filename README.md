# waqas_assign1_part2

# Step 1 (5 marks): Used the docker image from Part 1
Done
# Step 2 (20 marks): Run the Docker Container
Docker is running with any error
![image](https://github.com/mwaqaskh/waqas_assign1_part2/assets/39801941/53c91f58-0210-44fd-a597-6cb6697064c9)


# Step 3 (20 marks): used all below Docker Container Commands

# 'docker ps' command to list all running containers
![image](https://github.com/mwaqaskh/waqas_assign1_part2/assets/39801941/b741890d-5e0b-4e1e-b45e-d09e82b8e576)

# 'docker stop' command to stop a running container

docker stop d76c5bcb653b29241a636ef2915009989054913b0e2d5190fa67c9650142eff9                                                                                                  ─╯
d76c5bcb653b29241a636ef2915009989054913b0e2d5190fa67c9650142eff9
![image](https://github.com/mwaqaskh/waqas_assign1_part2/assets/39801941/c7306765-c113-4dc5-8407-a8bddca4077b)

# 'docker rm' command to remove a stopped container
docker remove d76c5bcb653b29241a636ef2915009989054913b0e2d5190fa67c9650142eff9                                                                                                ─╯
d76c5bcb653b29241a636ef2915009989054913b0e2d5190fa67c9650142eff9
container removed

# 'docker logs' command to view the logs of a container
docker logs 39f1da1d180f16f13dab83abf39e53164ade9fe8ee6e32a28a24b12b9305dc97                                                                                                  ─╯
Watching for file changes with StatReloader
[18/Aug/2023 15:47:50] "GET / HTTP/1.1" 200 6
[18/Aug/2023 15:48:00] "GET / HTTP/1.1" 200 6
[18/Aug/2023 15:48:07] "GET / HTTP/1.1" 200 6
[18/Aug/2023 15:48:08] "GET / HTTP/1.1" 200 6
[18/Aug/2023 15:48:14] "GET / HTTP/1.1" 200 6
[18/Aug/2023 15:48:23] "GET / HTTP/1.1" 200 6
[18/Aug/2023 15:48:44] "GET / HTTP/1.1" 200 6


# 'docker inspect' command to view the details of a container

docker inspect 39f1da1d180f16f13dab83abf39e53164ade9fe8ee6e32a28a24b12b9305dc97                                                                                               ─╯
[
    {
        "Id": "39f1da1d180f16f13dab83abf39e53164ade9fe8ee6e32a28a24b12b9305dc97",
        "Created": "2023-08-18T15:47:40.153853252Z",
        "Path": "python3",
        "Args": [
            "manage.py",
            "runserver",
            "0.0.0.0:8000"
        ],
        "State": {
            "Status": "exited",
            "Running": false,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 0,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2023-08-18T15:47:40.320622335Z",
            "FinishedAt": "2023-08-18T15:53:13.703696587Z"
        },
        "Image": "sha256:a922721aeae962a30e198555aabd9c2293b96ad31ab4bc66faa0e520c790f188",
        "ResolvConfPath": "/var/lib/docker/containers/39f1da1d180f16f13dab83abf39e53164ade9fe8ee6e32a28a24b12b9305dc97/resolv.conf",
        "HostnamePath": "/var/lib/docker/containers/39f1da1d180f16f13dab83abf39e53164ade9fe8ee6e32a28a24b12b9305dc97/hostname",
        "HostsPath": "/var/lib/docker/containers/39f1da1d180f16f13dab83abf39e53164ade9fe8ee6e32a28a24b12b9305dc97/hosts",
        "LogPath": "/var/lib/docker/containers/39f1da1d180f16f13dab83abf39e53164ade9fe8ee6e32a28a24b12b9305dc97/39f1da1d180f16f13dab83abf39e53164ade9fe8ee6e32a28a24b12b9305dc97-json.log",
        "Name": "/nifty_wing",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": null,
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {}
            },
            "NetworkMode": "default",
            "PortBindings": {
                "8000/tcp": [
                    {
                        "HostIp": "",
                        "HostPort": "8000"
                    }
                ]
            },
            "RestartPolicy": {
                "Name": "no",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": null,
            "ConsoleSize": [
                20,
                209
            ],
            "CapAdd": null,
            "CapDrop": null,
            "CgroupnsMode": "private",
            "Dns": [],
            "DnsOptions": [],
            "DnsSearch": [],
            "ExtraHosts": null,
            "GroupAdd": null,
            "IpcMode": "private",
            "Cgroup": "",
            "Links": null,
            "OomScoreAdj": 0,
            "PidMode": "",
            "Privileged": false,
            "PublishAllPorts": false,
            "ReadonlyRootfs": false,
            "SecurityOpt": null,
            "UTSMode": "",
            "UsernsMode": "",
            "ShmSize": 67108864,
            "Runtime": "runc",
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": [],
            "BlkioDeviceReadBps": [],
            "BlkioDeviceWriteBps": [],
            "BlkioDeviceReadIOps": [],
            "BlkioDeviceWriteIOps": [],
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": [],
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": null,
            "PidsLimit": null,
            "Ulimits": null,
            "CpuCount": 0,
            "CpuPercent": 0,
            "IOMaximumIOps": 0,
            "IOMaximumBandwidth": 0,
            "MaskedPaths": [
                "/proc/asound",
                "/proc/acpi",
                "/proc/kcore",
                "/proc/keys",
                "/proc/latency_stats",
                "/proc/timer_list",
                "/proc/timer_stats",
                "/proc/sched_debug",
                "/proc/scsi",
                "/sys/firmware"
            ],
            "ReadonlyPaths": [
                "/proc/bus",
                "/proc/fs",
                "/proc/irq",
                "/proc/sys",
                "/proc/sysrq-trigger"
            ]
        },
        "GraphDriver": {
            "Data": {
                "LowerDir": "/var/lib/docker/overlay2/e42b41d90293964986f64d8c34567d4cfc4de8b2e26a34f3e1bf156bb025867f-init/diff:/var/lib/docker/overlay2/8a592qrch1753fzj7a0kj3tfk/diff:/var/lib/docker/overlay2/srur4cpry0axq44d89iauh96d/diff:/var/lib/docker/overlay2/ssd6t0xzltl9q58t6msizijm1/diff:/var/lib/docker/overlay2/i4ehm6bvbljjjf67a1ehe485d/diff:/var/lib/docker/overlay2/456e6b822af54fc492e0ded03190fa7693f9774dd73fc3ffd4d77ecbcfe9beff/diff:/var/lib/docker/overlay2/af8b6274dd1674a1bd09a06c5489f8f23a68ceb52e8375807b3991ba026eabd2/diff:/var/lib/docker/overlay2/b898e8bd73a4c6f6d278e432f5924981bd4fcb31b535e44b7d79d37e2f82cfb3/diff:/var/lib/docker/overlay2/156a6777aa5cede59c171d732cab747457f1dca7d1623559ccb49c2673ac8a57/diff:/var/lib/docker/overlay2/0a96093f7402b9c1e212357c735a6a59fd027d5d5755921e0a31463b213e37d4/diff",
                "MergedDir": "/var/lib/docker/overlay2/e42b41d90293964986f64d8c34567d4cfc4de8b2e26a34f3e1bf156bb025867f/merged",
                "UpperDir": "/var/lib/docker/overlay2/e42b41d90293964986f64d8c34567d4cfc4de8b2e26a34f3e1bf156bb025867f/diff",
                "WorkDir": "/var/lib/docker/overlay2/e42b41d90293964986f64d8c34567d4cfc4de8b2e26a34f3e1bf156bb025867f/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [],
        "Config": {
            "Hostname": "39f1da1d180f",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": true,
            "AttachStderr": true,
            "ExposedPorts": {
                "8000/tcp": {}
            },
            "Tty": false,
            "OpenStdin": false,
            "StdinOnce": false,
            "Env": [
                "PATH=/usr/local/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin",
                "LANG=C.UTF-8",
                "GPG_KEY=E3FF2839C048B25C084DEBE9B26995E310250568",
                "PYTHON_VERSION=3.8.17",
                "PYTHON_PIP_VERSION=23.0.1",
                "PYTHON_SETUPTOOLS_VERSION=57.5.0",
                "PYTHON_GET_PIP_URL=https://github.com/pypa/get-pip/raw/0d8570dc44796f4369b652222cf176b3db6ac70e/public/get-pip.py",
                "PYTHON_GET_PIP_SHA256=96461deced5c2a487ddc65207ec5a9cffeca0d34e7af7ea1afc470ff0d746207"
            ],
            "Cmd": [
                "python3",
                "manage.py",
                "runserver",
                "0.0.0.0:8000"
            ],
            "Image": "python-django",
            "Volumes": null,
            "WorkingDir": "/app",
            "Entrypoint": null,
            "OnBuild": null,
            "Labels": {}
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "ebe538c083963310d68ae3f88212a484e702d02a79b843ae6ce6a7ffd2218fe1",
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "Ports": {},
            "SandboxKey": "/var/run/docker/netns/ebe538c08396",
            "SecondaryIPAddresses": null,
            "SecondaryIPv6Addresses": null,
            "EndpointID": "",
            "Gateway": "",
            "GlobalIPv6Address": "",
            "GlobalIPv6PrefixLen": 0,
            "IPAddress": "",
            "IPPrefixLen": 0,
            "IPv6Gateway": "",
            "MacAddress": "",
            "Networks": {
                "bridge": {
                    "IPAMConfig": null,
                    "Links": null,
                    "Aliases": null,
                    "NetworkID": "0ca8d4c23c1794f5af9fbc60403d3a5edebc0be2d8313ebc8274c271f4adf97c",
                    "EndpointID": "",
                    "Gateway": "",
                    "IPAddress": "",
                    "IPPrefixLen": 0,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "MacAddress": "",
                    "DriverOpts": null
                }
            }
        }
    }
]



# 'docker exec' command to execute a command inside a running container

 docker exec -d e2841c1bef4c8f1ddf4e629eff9237c433c052073a9400dbcfad7d73710918d7 touch execWorks 

# 'docker attach' command to attach to a running container

docker attach e2841c1bef4c8f1ddf4e629eff9237c433c052073a9400dbcfad7d73710918d7                                                                                                ─╯
[18/Aug/2023 18:00:02] "GET / HTTP/1.1" 200 6
[18/Aug/2023 18:00:04] "GET / HTTP/1.1" 200 6

■ 'docker commit' command to create a new image from a container

docker commit e2841c1bef4c8f1ddf4e629eff9237c433c052073a9400dbcfad7d73710918d7                                                                                                ─╯
sha256:d808032fc54900cd2f3ab650b16248a30a9aa0a56e173dfbd4217bb7088d213c

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
