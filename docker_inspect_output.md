


  # "mount":



/dev/sda1 on / type ext4 (rw,relatime,discard)
devtmpfs on /dev type devtmpfs (rw,relatime,size=4066576k,nr_inodes=1016644,mode=755,inode64)
sysfs on /sys type sysfs (rw,nosuid,nodev,noexec,relatime)
proc on /proc type proc (rw,nosuid,nodev,noexec,relatime)
securityfs on /sys/kernel/security type securityfs (rw,nosuid,nodev,noexec,relatime)
tmpfs on /dev/shm type tmpfs (rw,nosuid,nodev,inode64)
devpts on /dev/pts type devpts (rw,nosuid,noexec,relatime,gid=5,mode=620,ptmxmode=000)
tmpfs on /run type tmpfs (rw,nosuid,nodev,size=814216k,mode=755,inode64)
tmpfs on /run/lock type tmpfs (rw,nosuid,nodev,noexec,relatime,size=5120k,inode64)
tmpfs on /sys/fs/cgroup type tmpfs (ro,nosuid,nodev,noexec,mode=755,inode64)
cgroup2 on /sys/fs/cgroup/unified type cgroup2 (rw,nosuid,nodev,noexec,relatime,nsdelegate)
cgroup on /sys/fs/cgroup/systemd type cgroup (rw,nosuid,nodev,noexec,relatime,xattr,name=systemd)
pstore on /sys/fs/pstore type pstore (rw,nosuid,nodev,noexec,relatime)
efivarfs on /sys/firmware/efi/efivars type efivarfs (rw,nosuid,nodev,noexec,relatime)
bpf on /sys/fs/bpf type bpf (rw,nosuid,nodev,noexec,relatime,mode=700)
cgroup on /sys/fs/cgroup/cpu,cpuacct type cgroup (rw,nosuid,nodev,noexec,relatime,cpu,cpuacct)
cgroup on /sys/fs/cgroup/devices type cgroup (rw,nosuid,nodev,noexec,relatime,devices)
cgroup on /sys/fs/cgroup/pids type cgroup (rw,nosuid,nodev,noexec,relatime,pids)
cgroup on /sys/fs/cgroup/net_cls,net_prio type cgroup (rw,nosuid,nodev,noexec,relatime,net_cls,net_prio)
cgroup on /sys/fs/cgroup/rdma type cgroup (rw,nosuid,nodev,noexec,relatime,rdma)
cgroup on /sys/fs/cgroup/hugetlb type cgroup (rw,nosuid,nodev,noexec,relatime,hugetlb)
cgroup on /sys/fs/cgroup/perf_event type cgroup (rw,nosuid,nodev,noexec,relatime,perf_event)
cgroup on /sys/fs/cgroup/cpuset type cgroup (rw,nosuid,nodev,noexec,relatime,cpuset)
cgroup on /sys/fs/cgroup/freezer type cgroup (rw,nosuid,nodev,noexec,relatime,freezer)
cgroup on /sys/fs/cgroup/misc type cgroup (rw,nosuid,nodev,noexec,relatime,misc)
cgroup on /sys/fs/cgroup/blkio type cgroup (rw,nosuid,nodev,noexec,relatime,blkio)
cgroup on /sys/fs/cgroup/memory type cgroup (rw,nosuid,nodev,noexec,relatime,memory)
systemd-1 on /proc/sys/fs/binfmt_misc type autofs (rw,relatime,fd=28,pgrp=1,timeout=0,minproto=5,maxproto=5,direct,pipe_ino=554)
hugetlbfs on /dev/hugepages type hugetlbfs (rw,relatime,pagesize=2M)
mqueue on /dev/mqueue type mqueue (rw,nosuid,nodev,noexec,relatime)
debugfs on /sys/kernel/debug type debugfs (rw,nosuid,nodev,noexec,relatime)
tracefs on /sys/kernel/tracing type tracefs (rw,nosuid,nodev,noexec,relatime)
configfs on /sys/kernel/config type configfs (rw,nosuid,nodev,noexec,relatime)
fusectl on /sys/fs/fuse/connections type fusectl (rw,nosuid,nodev,noexec,relatime)
/var/lib/snapd/snaps/core20_1611.snap on /snap/core20/1611 type squashfs (ro,nodev,relatime,errors=continue,x-gdu.hide)
/var/lib/snapd/snaps/lxd_22753.snap on /snap/lxd/22753 type squashfs (ro,nodev,relatime,errors=continue,x-gdu.hide)
/var/lib/snapd/snaps/snapd_16292.snap on /snap/snapd/16292 type squashfs (ro,nodev,relatime,errors=continue,x-gdu.hide)
/dev/sda15 on /boot/efi type vfat (rw,relatime,fmask=0077,dmask=0077,codepage=437,iocharset=iso8859-1,shortname=mixed,errors=remount-ro)
/dev/sdb1 on /mnt type ext4 (rw,relatime,x-systemd.requires=cloud-init.service,_netdev)
tmpfs on /run/snapd/ns type tmpfs (rw,nosuid,nodev,size=814216k,mode=755,inode64)
nsfs on /run/snapd/ns/lxd.mnt type nsfs (rw)
tmpfs on /run/user/1000 type tmpfs (rw,nosuid,nodev,relatime,size=814212k,mode=700,uid=1000,gid=1000,inode64)
overlay on /var/lib/docker/overlay2/f97bc7deb35a82820923a0cb122063fce7c55e8060efadfcc2eaf477e53f998c/merged type overlay (rw,relatime,lowerdir=/var/lib/docker/overlay2/l/H2LWEW5LCWDD3GY3KZ7YALKUFX:/var/lib/docker/overlay2/l/L63TPLFFRNOFUACKG5TMVLQBUG:/var/lib/docker/overlay2/l/AHSJ2KEHPGURWRR7RY52VY4KKC:/var/lib/docker/overlay2/l/TEYRT5ZJ2XDEOEYLTHEPNEKJR5:/var/lib/docker/overlay2/l/EJ2HESPN2FM2TX674QPKMZNAD4:/var/lib/docker/overlay2/l/LCK2FAFSTEONXP252FFWQLBQW7:/var/lib/docker/overlay2/l/BFIIPTRVOQV4FCBV4INPFC3AVK:/var/lib/docker/overlay2/l/Z36REMPE4Y2ZPUIS37UKGTA4G7:/var/lib/docker/overlay2/l/FYKMYAIBIMHX6J5HT66TQSB4MF:/var/lib/docker/overlay2/l/Q54GWU3Y5ESBCO52FOUMFBRGOJ:/var/lib/docker/overlay2/l/JB3FT7NFH7WTI2TAKXYZU2VD3Z:/var/lib/docker/overlay2/l/KD36HSM7HLI3MXTD5ISL6VB2OQ,upperdir=/var/lib/docker/overlay2/f97bc7deb35a82820923a0cb122063fce7c55e8060efadfcc2eaf477e53f998c/diff,workdir=/var/lib/docker/overlay2/f97bc7deb35a82820923a0cb122063fce7c55e8060efadfcc2eaf477e53f998c/work)
shm on /var/lib/docker/containers/1af8309100f09bf63c336a5617208b3dac0bd755c0dc4387088566861575ec6b/mounts/shm type tmpfs (rw,nosuid,nodev,noexec,relatime,size=65536k,inode64)
nsfs on /run/docker/netns/2effc0b8d872 type nsfs (rw)
overlay on /var/lib/docker/overlay2/e6508640e74aed011dab9660ccaddd8bfe5f16fe7c2777745f39c3697b897605/merged type overlay (rw,relatime,lowerdir=/var/lib/docker/overlay2/l/GYZTJ5YLERUBX2BOM5PBPSPQ7C:/var/lib/docker/overlay2/l/FWFDT34RRXLPBEDQYFUSDQXT2X:/var/lib/docker/overlay2/l/SGOEBTEHAV6N5VY4SUU6DWZEND:/var/lib/docker/overlay2/l/T3LFGQP2HD36GT42CTYMQB353Y:/var/lib/docker/overlay2/l/SA5TYAKVF2EK6H5PGLDPLHWQRK:/var/lib/docker/overlay2/l/YCEZTZB3Y6E5UFRPS4WA2LHPQ2:/var/lib/docker/overlay2/l/3PBZ72U2ZMZSO3HVXRVUDNFS65:/var/lib/docker/overlay2/l/SHYO63WEYFN6TSSMQVW3CQATJ4:/var/lib/docker/overlay2/l/ZZOKLJ525BSGYV6JHIHFPGTIE7:/var/lib/docker/overlay2/l/Y4DAZDJFXO5GUDOJN4IWGGRR3M:/var/lib/docker/overlay2/l/K5YD2BNUEB336DVHR6GNX6APA5:/var/lib/docker/overlay2/l/JL5NUZILHEUVAJIWVAUAIFWGR7:/var/lib/docker/overlay2/l/ZM52XH5UIAU6A6U6OVHNYYFJAU:/var/lib/docker/overlay2/l/J4AW74473SB3TDL67ZCVYFODLB:/var/lib/docker/overlay2/l/QLSCCYXNYGJ33UNLJ3A5VNIAR6:/var/lib/docker/overlay2/l/GYMTIJIQZ4RVJBKNL3FYP2B555:/var/lib/docker/overlay2/l/T2TVSJFDD6FLWGTVQBTG4JJG5M:/var/lib/docker/overlay2/l/I3BFBWVL4JQB7L7TYDM5NVYB76:/var/lib/docker/overlay2/l/BOGKA6KVYIJFAL5TSVVXVXE33C:/var/lib/docker/overlay2/l/5CQ5KKQD6QA4QHGO3XSWOFKN6G:/var/lib/docker/overlay2/l/URY4VKOBZJFZFSAQ3D6WUEOSNB:/var/lib/docker/overlay2/l/QMUEK5CR5XZHT5SDX4ENRG7DWK,upperdir=/var/lib/docker/overlay2/e6508640e74aed011dab9660ccaddd8bfe5f16fe7c2777745f39c3697b897605/diff,workdir=/var/lib/docker/overlay2/e6508640e74aed011dab9660ccaddd8bfe5f16fe7c2777745f39c3697b897605/work)
shm on /var/lib/docker/containers/2ea04b2c148ae6b940a87e50be9f89100a12ce314919c7e658e6a31cef0baf02/mounts/shm type tmpfs (rw,nosuid,nodev,noexec,relatime,size=65536k,inode64)
nsfs on /run/docker/netns/b63fba07376c type nsfs (rw)
overlay on /var/lib/docker/overlay2/27a23d8dceb4941b3e48f138c86ef0d6f644a16787b4cec262a458d69b50b01a/merged type overlay (rw,relatime,lowerdir=/var/lib/docker/overlay2/l/7PN3ACUW5UH6WO6WTACRH4GYQG:/var/lib/docker/overlay2/l/NHSBTLOOAXAIOUK54XAB4I62QS:/var/lib/docker/overlay2/l/UI45WOOUABMCFT2UPUK2KMN26A:/var/lib/docker/overlay2/l/P7K7FK5BNSE7VLCVTKDC47SYLI:/var/lib/docker/overlay2/l/OFKDFHL4OUKB452IYV6BLMGIQP:/var/lib/docker/overlay2/l/XVBL3B6FOS4W2NBZ4RLWJPKYTR:/var/lib/docker/overlay2/l/OUCMGI67AM46656DHTUJ674JSM:/var/lib/docker/overlay2/l/R3WQBFGJTYZ2GCDWFRQ7SYLZ2M,upperdir=/var/lib/docker/overlay2/27a23d8dceb4941b3e48f138c86ef0d6f644a16787b4cec262a458d69b50b01a/diff,workdir=/var/lib/docker/overlay2/27a23d8dceb4941b3e48f138c86ef0d6f644a16787b4cec262a458d69b50b01a/work)
shm on /var/lib/docker/containers/e82c12dcab46bac83a278d14087b550adcb61891b84e6a773e239e7431b10866/mounts/shm type tmpfs (rw,nosuid,nodev,noexec,relatime,size=65536k,inode64)
nsfs on /run/docker/netns/8a92007cf680 type nsfs (rw)



  # "docker inspect swag" :


[
    {
        "Id": "e82c12dcab46bac83a278d14087b550adcb61891b84e6a773e239e7431b10866",
        "Created": "2022-09-15T12:02:21.141066183Z",
        "Path": "/init",
        "Args": [],
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 17442,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2022-09-15T12:02:21.740651715Z",
            "FinishedAt": "0001-01-01T00:00:00Z"
        },
        "Image": "sha256:c245973be0cf1fc04d6091ad42495883f7005586c9e474169dc0d26122129aff",
        "ResolvConfPath": "/var/lib/docker/containers/e82c12dcab46bac83a278d14087b550adcb61891b84e6a773e239e7431b10866/resolv.conf",
        "HostnamePath": "/var/lib/docker/containers/e82c12dcab46bac83a278d14087b550adcb61891b84e6a773e239e7431b10866/hostname",
        "HostsPath": "/var/lib/docker/containers/e82c12dcab46bac83a278d14087b550adcb61891b84e6a773e239e7431b10866/hosts",
        "LogPath": "/var/lib/docker/containers/e82c12dcab46bac83a278d14087b550adcb61891b84e6a773e239e7431b10866/e82c12dcab46bac83a278d14087b550adcb61891b84e6a773e239e7431b10866-json.log",
        "Name": "/swag",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "docker-default",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": [
                "/home/johnny/wordpress/nginx-default:/config/nginx/site-confs/default:rw",
                "64d415077b5bf1f6b102e66dc2918c9f192eaa35b67d133ee94776815e857e07:/config:rw"
            ],
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {}
            },
            "NetworkMode": "wordpress_default",
            "PortBindings": {
                "443/tcp": [
                    {
                        "HostIp": "",
                        "HostPort": "443"
                    }
                ],
                "80/tcp": [
                    {
                        "HostIp": "",
                        "HostPort": "80"
                    }
                ]
            },
            "RestartPolicy": {
                "Name": "unless-stopped",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": [],
            "CapAdd": [
                "NET_ADMIN"
            ],
            "CapDrop": null,
            "CgroupnsMode": "host",
            "Dns": null,
            "DnsOptions": null,
            "DnsSearch": null,
            "ExtraHosts": null,
            "GroupAdd": null,
            "IpcMode": "shareable",
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
            "ConsoleSize": [
                0,
                0
            ],
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": null,
            "BlkioDeviceReadBps": null,
            "BlkioDeviceWriteBps": null,
            "BlkioDeviceReadIOps": null,
            "BlkioDeviceWriteIOps": null,
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": null,
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "KernelMemory": 0,
            "KernelMemoryTCP": 0,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": false,
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
                "LowerDir": "/var/lib/docker/overlay2/27a23d8dceb4941b3e48f138c86ef0d6f644a16787b4cec262a458d69b50b01a-init/diff:/var/lib/docker/overlay2/aa51d9712d127aa6be8093a2c14d22a9dd10ef27a0f9f26cce9f52a4ec2661a4/diff:/var/lib/docker/overlay2/ab7b48f8af827e6ec0175cce8ded192012c9f463f3b840e4e5d8dfc7f2a9bc9f/diff:/var/lib/docker/overlay2/a2599369d72dc5e0c3ce7e66eea4adb9924792914f3ac625b193e83304acfdcf/diff:/var/lib/docker/overlay2/4d43f0874c9fa898776d52af3afa4ca434bd18aaf15f723d3ca07f09ec18e6a7/diff:/var/lib/docker/overlay2/6bf9023fdac2a355cdbda7f4db1746ff9b59f7876fbd201bc8d5cb18187e4d6d/diff:/var/lib/docker/overlay2/9084c103fce7b796f259e6d242b9ebbec6207559274014598e180b0cade54f08/diff:/var/lib/docker/overlay2/773af2b0e5eaee2d0b510db5652bad9d1bb8c7250f13205e9ae039a814dd3c68/diff",
                "MergedDir": "/var/lib/docker/overlay2/27a23d8dceb4941b3e48f138c86ef0d6f644a16787b4cec262a458d69b50b01a/merged",
                "UpperDir": "/var/lib/docker/overlay2/27a23d8dceb4941b3e48f138c86ef0d6f644a16787b4cec262a458d69b50b01a/diff",
                "WorkDir": "/var/lib/docker/overlay2/27a23d8dceb4941b3e48f138c86ef0d6f644a16787b4cec262a458d69b50b01a/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [
            {
                "Type": "bind",
                "Source": "/home/johnny/wordpress/nginx-default",
                "Destination": "/config/nginx/site-confs/default",
                "Mode": "rw",
                "RW": true,
                "Propagation": "rprivate"
            },
            {
                "Type": "volume",
                "Name": "64d415077b5bf1f6b102e66dc2918c9f192eaa35b67d133ee94776815e857e07",
                "Source": "/var/lib/docker/volumes/64d415077b5bf1f6b102e66dc2918c9f192eaa35b67d133ee94776815e857e07/_data",
                "Destination": "/config",
                "Driver": "local",
                "Mode": "rw",
                "RW": true,
                "Propagation": ""
            }
        ],
        "Config": {
            "Hostname": "e82c12dcab46",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": false,
            "AttachStderr": false,
            "ExposedPorts": {
                "443/tcp": {},
                "80/tcp": {}
            },
            "Tty": false,
            "OpenStdin": false,
            "StdinOnce": false,
            "Env": [
                "URL=site12345.westeurope.cloudapp.azure.com",
                "VALIDATION=http",
                "affinity:container==c335c9f72382d3eca80e84ee50a06088c89225e22d22a2f72a3abca3b7126edd",
                "PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin",
                "PS1=$(whoami)@$(hostname):$(pwd)\\$ ",
                "HOME=/root",
                "TERM=xterm",
                "S6_CMD_WAIT_FOR_SERVICES_MAXTIME=0",
                "DHLEVEL=2048",
                "ONLY_SUBDOMAINS=false",
                "AWS_CONFIG_FILE=/config/dns-conf/route53.ini",
                "S6_BEHAVIOUR_IF_STAGE2_FAILS=2"
            ],
            "Cmd": null,
            "Image": "linuxserver/swag",
            "Volumes": {
                "/config": {},
                "/config/nginx/site-confs/default": {}
            },
            "WorkingDir": "",
            "Entrypoint": [
                "/init"
            ],
            "OnBuild": null,
            "Labels": {
                "build_version": "Linuxserver.io version:- 1.30.0-ls145 Build-date:- 2022-09-07T15:56:29-05:00",
                "com.docker.compose.config-hash": "de76cb3ad80492d863feef39c5c0bba76e47d968900d54ddafcbe72e89062835",
                "com.docker.compose.container-number": "1",
                "com.docker.compose.oneoff": "False",
                "com.docker.compose.project": "wordpress",
                "com.docker.compose.project.config_files": "docker-compose.yml",
                "com.docker.compose.project.working_dir": "/home/johnny/wordpress",
                "com.docker.compose.service": "swag",
                "com.docker.compose.version": "1.25.0",
                "maintainer": "aptalca",
                "org.opencontainers.image.authors": "linuxserver.io",
                "org.opencontainers.image.created": "2022-09-07T15:56:29-05:00",
                "org.opencontainers.image.description": "SWAG - Secure Web Application Gateway (formerly known as letsencrypt, no relation to Let's Encrypt™) sets up an Nginx webserver and reverse proxy with php support and a built-in certbot client that automates free SSL server certificate generation and renewal processes (Let's Encrypt and ZeroSSL). It also contains fail2ban for intrusion prevention.",
                "org.opencontainers.image.documentation": "https://docs.linuxserver.io/images/docker-swag",
                "org.opencontainers.image.licenses": "GPL-3.0-only",
                "org.opencontainers.image.ref.name": "8d5430dadaeb1bcf57899022a3c13243d88dbe2f",
                "org.opencontainers.image.revision": "8d5430dadaeb1bcf57899022a3c13243d88dbe2f",
                "org.opencontainers.image.source": "https://github.com/linuxserver/docker-swag",
                "org.opencontainers.image.title": "Swag",
                "org.opencontainers.image.url": "https://github.com/linuxserver/docker-swag/packages",
                "org.opencontainers.image.vendor": "linuxserver.io",
                "org.opencontainers.image.version": "1.30.0-ls145"
            }
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "8a92007cf6803071e999ef08009e5aadf810dcbb1685e32820c3fd0d22187aba",
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "Ports": {
                "443/tcp": [
                    {
                        "HostIp": "0.0.0.0",
                        "HostPort": "443"
                    },
                    {
                        "HostIp": "::",
                        "HostPort": "443"
                    }
                ],
                "80/tcp": [
                    {
                        "HostIp": "0.0.0.0",
                        "HostPort": "80"
                    },
                    {
                        "HostIp": "::",
                        "HostPort": "80"
                    }
                ]
            },
            "SandboxKey": "/var/run/docker/netns/8a92007cf680",
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
                "wordpress_default": {
                    "IPAMConfig": null,
                    "Links": null,
                    "Aliases": [
                        "e82c12dcab46",
                        "swag"
                    ],
                    "NetworkID": "7efa43057b2aa0caa8fe0b948feae66639e59eb918a1c07a14b30862bde0e66c",
                    "EndpointID": "a2bb74d0e3fe37a736a4b8ba258af055b85ef9c47395641a751cccb2219978fe",
                    "Gateway": "172.18.0.1",
                    "IPAddress": "172.18.0.3",
                    "IPPrefixLen": 16,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "MacAddress": "02:42:ac:12:00:03",
                    "DriverOpts": null
                }
            }
        }
    }
]

   
  # "docker inspect wordpress_wordpress_1" :


[
    {
        "Id": "2ea04b2c148ae6b940a87e50be9f89100a12ce314919c7e658e6a31cef0baf02",
        "Created": "2022-09-15T11:57:28.427035134Z",
        "Path": "docker-entrypoint.sh",
        "Args": [
            "apache2-foreground"
        ],
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 16765,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2022-09-15T11:57:29.376324546Z",
            "FinishedAt": "0001-01-01T00:00:00Z"
        },
        "Image": "sha256:18f67377ee02d5a52eeafeec5f179ff563eca40c83ee9c4d18d28520ef7cc1dd",
        "ResolvConfPath": "/var/lib/docker/containers/2ea04b2c148ae6b940a87e50be9f89100a12ce314919c7e658e6a31cef0baf02/resolv.conf",
        "HostnamePath": "/var/lib/docker/containers/2ea04b2c148ae6b940a87e50be9f89100a12ce314919c7e658e6a31cef0baf02/hostname",
        "HostsPath": "/var/lib/docker/containers/2ea04b2c148ae6b940a87e50be9f89100a12ce314919c7e658e6a31cef0baf02/hosts",
        "LogPath": "/var/lib/docker/containers/2ea04b2c148ae6b940a87e50be9f89100a12ce314919c7e658e6a31cef0baf02/2ea04b2c148ae6b940a87e50be9f89100a12ce314919c7e658e6a31cef0baf02-json.log",
        "Name": "/wordpress_wordpress_1",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "docker-default",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": [
                "wordpress_uploads:/var/www/html/uploads:rw"
            ],
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {}
            },
            "NetworkMode": "wordpress_default",
            "PortBindings": {},
            "RestartPolicy": {
                "Name": "always",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": [],
            "CapAdd": null,
            "CapDrop": null,
            "CgroupnsMode": "host",
            "Dns": null,
            "DnsOptions": null,
            "DnsSearch": null,
            "ExtraHosts": null,
            "GroupAdd": null,
            "IpcMode": "shareable",
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
            "ConsoleSize": [
                0,
                0
            ],
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": null,
            "BlkioDeviceReadBps": null,
            "BlkioDeviceWriteBps": null,
            "BlkioDeviceReadIOps": null,
            "BlkioDeviceWriteIOps": null,
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": null,
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "KernelMemory": 0,
            "KernelMemoryTCP": 0,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": false,
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
                "LowerDir": "/var/lib/docker/overlay2/e6508640e74aed011dab9660ccaddd8bfe5f16fe7c2777745f39c3697b897605-init/diff:/var/lib/docker/overlay2/0ddce38669023c004a2061d3fe4c7bffedc3d6ee3e96076b80dad7c7cca3182a/diff:/var/lib/docker/overlay2/e16016b6b6c3a323e67983ac7d8d06d16bc4a67b3acac1cf78833a4536dc0517/diff:/var/lib/docker/overlay2/01b4b25861641613af89d730776911f5f104cd41d024b257002aedc07181b533/diff:/var/lib/docker/overlay2/f0e58b2f3bbb68602ad5437f16f5adf7f29cf9cad4a71f1ff77679a9f5d97ce3/diff:/var/lib/docker/overlay2/e114dbab433432142bf9f3b3b3f2cc18a14fb42979edd8c9335f75b08c7ba8b7/diff:/var/lib/docker/overlay2/17435a2e179daac9bd56f71385af6d64c7b3b65f88d4838ec718bbe7f2ffb655/diff:/var/lib/docker/overlay2/0a11759774b8da9fa49d8b118865e5896bacfcfbc1172a00ecc019d050baed15/diff:/var/lib/docker/overlay2/ea7b76e3f4dd5bf2eabc2403c275b0806fbcba6e013da67f3cfae2283159e76b/diff:/var/lib/docker/overlay2/2c9dd5bc168ccc9ec6789c943580d0c32ad283d28f28cd52432d97871bce7ac0/diff:/var/lib/docker/overlay2/8c7736e79060da1895282a5f4a01a8edc48f8360a3af0e2244d18c3e39ff402b/diff:/var/lib/docker/overlay2/4e43b8fa6e7fda8595b2d4c6607289540dcdb8b19a93cc3a17279060bd274669/diff:/var/lib/docker/overlay2/2a7421b805b8f21be10367b3afc35d5b01d28dd6eb825c51652a950da39fc451/diff:/var/lib/docker/overlay2/79995bbf79d5519c18a32c3f55c233c9cd20878b63a9914143ab1dbedcee695d/diff:/var/lib/docker/overlay2/cb99016b2c01d4ed74c1ef2fec9710594ad4b82b132fc816fcfff9af375548b7/diff:/var/lib/docker/overlay2/be72c6c288b4f8d043ccd6109c42b00a15c01f92de566b6b40860f2f264350b5/diff:/var/lib/docker/overlay2/d4109ecef82510ad6dd62c5b14c10f3934740448264f2aad144aef623c8b7195/diff:/var/lib/docker/overlay2/8ee89e1c6e1333a673c3cd8088217390c833ca566a4512c7c0ec8fefcff162ce/diff:/var/lib/docker/overlay2/b5cea038915bac1975d889dffe4cdac1c8454b97599477f7b65d70e6309fa594/diff:/var/lib/docker/overlay2/f44d2509d4786a73824800912269c3240ed2c453d57cf5e08b709430d6afdd7f/diff:/var/lib/docker/overlay2/98e8e6c3563e702bc8ae13daa3181aa12ed9b7c20249d8dd224da0ea6861833b/diff:/var/lib/docker/overlay2/c49a8fe489f84783ff2b80d9946cee9f9c03b44915a40c860f1dc535480eb74c/diff",
                "MergedDir": "/var/lib/docker/overlay2/e6508640e74aed011dab9660ccaddd8bfe5f16fe7c2777745f39c3697b897605/merged",
                "UpperDir": "/var/lib/docker/overlay2/e6508640e74aed011dab9660ccaddd8bfe5f16fe7c2777745f39c3697b897605/diff",
                "WorkDir": "/var/lib/docker/overlay2/e6508640e74aed011dab9660ccaddd8bfe5f16fe7c2777745f39c3697b897605/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [
            {
                "Type": "volume",
                "Name": "wordpress_uploads",
                "Source": "/var/lib/docker/volumes/wordpress_uploads/_data",
                "Destination": "/var/www/html/uploads",
                "Driver": "local",
                "Mode": "rw",
                "RW": true,
                "Propagation": ""
            },
            {
                "Type": "volume",
                "Name": "31a378dae9d9a6e10dada12172a764ad246a78f7f9b6a2bed3ec70691fc715a6",
                "Source": "/var/lib/docker/volumes/31a378dae9d9a6e10dada12172a764ad246a78f7f9b6a2bed3ec70691fc715a6/_data",
                "Destination": "/var/www/html",
                "Driver": "local",
                "Mode": "",
                "RW": true,
                "Propagation": ""
            }
        ],
        "Config": {
            "Hostname": "2ea04b2c148a",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": false,
            "AttachStderr": false,
            "ExposedPorts": {
                "80/tcp": {}
            },
            "Tty": false,
            "OpenStdin": false,
            "StdinOnce": false,
            "Env": [
                "WORDPRESS_DB_HOST=db:3306",
                "WORDPRESS_DB_USER=wordpress",
                "WORDPRESS_DB_PASSWORD=wordpress",
                "PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin",
                "PHPIZE_DEPS=autoconf \t\tdpkg-dev \t\tfile \t\tg++ \t\tgcc \t\tlibc-dev \t\tmake \t\tpkg-config \t\tre2c",
                "PHP_INI_DIR=/usr/local/etc/php",
                "APACHE_CONFDIR=/etc/apache2",
                "APACHE_ENVVARS=/etc/apache2/envvars",
                "PHP_CFLAGS=-fstack-protector-strong -fpic -fpie -O2 -D_LARGEFILE_SOURCE -D_FILE_OFFSET_BITS=64",
                "PHP_CPPFLAGS=-fstack-protector-strong -fpic -fpie -O2 -D_LARGEFILE_SOURCE -D_FILE_OFFSET_BITS=64",
                "PHP_LDFLAGS=-Wl,-O1 -pie",
                "GPG_KEYS=42670A7FE4D0441C8E4632349E4FDC074A4EF02D 5A52880781F755608BF815FC910DEB46F53EA312",
                "PHP_VERSION=7.4.30",
                "PHP_URL=https://www.php.net/distributions/php-7.4.30.tar.xz",
                "PHP_ASC_URL=https://www.php.net/distributions/php-7.4.30.tar.xz.asc",
                "PHP_SHA256=ea72a34f32c67e79ac2da7dfe96177f3c451c3eefae5810ba13312ed398ba70d"
            ],
            "Cmd": [
                "apache2-foreground"
            ],
            "Image": "wordpress:latest",
            "Volumes": {
                "/var/www/html": {},
                "/var/www/html/uploads": {}
            },
            "WorkingDir": "/var/www/html",
            "Entrypoint": [
                "docker-entrypoint.sh"
            ],
            "OnBuild": null,
            "Labels": {
                "com.docker.compose.config-hash": "f9af0c9b3c9559de9e401fe3ac7c8b0d85edc1401997c314b4d7297dbffd51a8",
                "com.docker.compose.container-number": "1",
                "com.docker.compose.oneoff": "False",
                "com.docker.compose.project": "wordpress",
                "com.docker.compose.project.config_files": "docker-compose.yml",
                "com.docker.compose.project.working_dir": "/home/johnny/wordpress",
                "com.docker.compose.service": "wordpress",
                "com.docker.compose.version": "1.25.0"
            },
            "StopSignal": "SIGWINCH"
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "b63fba07376c6fca840eb72f576bddb68b721995ee1085e5d3a1f23f6fe4fd35",
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "Ports": {
                "80/tcp": null
            },
            "SandboxKey": "/var/run/docker/netns/b63fba07376c",
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
                "wordpress_default": {
                    "IPAMConfig": null,
                    "Links": null,
                    "Aliases": [
                        "wordpress",
                        "2ea04b2c148a"
                    ],
                    "NetworkID": "7efa43057b2aa0caa8fe0b948feae66639e59eb918a1c07a14b30862bde0e66c",
                    "EndpointID": "753d5def16b7ef6a293cc71ea86593cae60599d1fcf1a68116cb386a4d25992a",
                    "Gateway": "172.18.0.1",
                    "IPAddress": "172.18.0.4",
                    "IPPrefixLen": 16,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "MacAddress": "02:42:ac:12:00:04",
                    "DriverOpts": null
                }
            }
        }
    }
]


   # "docker inspect wordpress_db_1" :

[
    {
        "Id": "1af8309100f09bf63c336a5617208b3dac0bd755c0dc4387088566861575ec6b",
        "Created": "2022-09-15T11:57:27.342032779Z",
        "Path": "docker-entrypoint.sh",
        "Args": [
            "mysqld"
        ],
        "State": {
            "Status": "running",
            "Running": true,
            "Paused": false,
            "Restarting": false,
            "OOMKilled": false,
            "Dead": false,
            "Pid": 16509,
            "ExitCode": 0,
            "Error": "",
            "StartedAt": "2022-09-15T11:57:28.388775342Z",
            "FinishedAt": "0001-01-01T00:00:00Z"
        },
        "Image": "sha256:daff57b7d2d1e009d0b271972f62dbf4de64b8cdb9cd646442aeda961e615f44",
        "ResolvConfPath": "/var/lib/docker/containers/1af8309100f09bf63c336a5617208b3dac0bd755c0dc4387088566861575ec6b/resolv.conf",
        "HostnamePath": "/var/lib/docker/containers/1af8309100f09bf63c336a5617208b3dac0bd755c0dc4387088566861575ec6b/hostname",
        "HostsPath": "/var/lib/docker/containers/1af8309100f09bf63c336a5617208b3dac0bd755c0dc4387088566861575ec6b/hosts",
        "LogPath": "/var/lib/docker/containers/1af8309100f09bf63c336a5617208b3dac0bd755c0dc4387088566861575ec6b/1af8309100f09bf63c336a5617208b3dac0bd755c0dc4387088566861575ec6b-json.log",
        "Name": "/wordpress_db_1",
        "RestartCount": 0,
        "Driver": "overlay2",
        "Platform": "linux",
        "MountLabel": "",
        "ProcessLabel": "",
        "AppArmorProfile": "docker-default",
        "ExecIDs": null,
        "HostConfig": {
            "Binds": [
                "wordpress_dbdata:/var/lib/mysql:rw"
            ],
            "ContainerIDFile": "",
            "LogConfig": {
                "Type": "json-file",
                "Config": {}
            },
            "NetworkMode": "wordpress_default",
            "PortBindings": {},
            "RestartPolicy": {
                "Name": "always",
                "MaximumRetryCount": 0
            },
            "AutoRemove": false,
            "VolumeDriver": "",
            "VolumesFrom": [],
            "CapAdd": null,
            "CapDrop": null,
            "CgroupnsMode": "host",
            "Dns": null,
            "DnsOptions": null,
            "DnsSearch": null,
            "ExtraHosts": null,
            "GroupAdd": null,
            "IpcMode": "shareable",
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
            "ConsoleSize": [
                0,
                0
            ],
            "Isolation": "",
            "CpuShares": 0,
            "Memory": 0,
            "NanoCpus": 0,
            "CgroupParent": "",
            "BlkioWeight": 0,
            "BlkioWeightDevice": null,
            "BlkioDeviceReadBps": null,
            "BlkioDeviceWriteBps": null,
            "BlkioDeviceReadIOps": null,
            "BlkioDeviceWriteIOps": null,
            "CpuPeriod": 0,
            "CpuQuota": 0,
            "CpuRealtimePeriod": 0,
            "CpuRealtimeRuntime": 0,
            "CpusetCpus": "",
            "CpusetMems": "",
            "Devices": null,
            "DeviceCgroupRules": null,
            "DeviceRequests": null,
            "KernelMemory": 0,
            "KernelMemoryTCP": 0,
            "MemoryReservation": 0,
            "MemorySwap": 0,
            "MemorySwappiness": null,
            "OomKillDisable": false,
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
                "LowerDir": "/var/lib/docker/overlay2/f97bc7deb35a82820923a0cb122063fce7c55e8060efadfcc2eaf477e53f998c-init/diff:/var/lib/docker/overlay2/af1258214b635c1792e0b671eb1c91347bbc7da27f3c6a8c3c16158facb9cdc9/diff:/var/lib/docker/overlay2/22116adbf8372736d854b75c9a18043b289880435862546e088f36e8f9b0da0c/diff:/var/lib/docker/overlay2/54979047cab481660ae5e330101a31dcb30d0b8928c7f93ff4321b68776cf8a9/diff:/var/lib/docker/overlay2/36bbb5abb286c51b48fac2a0d12ef2b290376eebe8805ec26114b612def4cdf2/diff:/var/lib/docker/overlay2/f73397daf09a62f5db73e938471ea6d860155fbfe86d08dd4412cc5ac1b2a112/diff:/var/lib/docker/overlay2/f446789f127b5485707b0f835f62c0a27fcbc509dc66318ff991f6958bf7690f/diff:/var/lib/docker/overlay2/80d3515e9b30cb2275a8f7b71d2f5683f761154c8d016d4261b7b02cc03d268b/diff:/var/lib/docker/overlay2/db10be8882916ce547a165bab8602e3b7665626b46fe8980b42a6e21a93d6883/diff:/var/lib/docker/overlay2/04c0a7c8e8a2bb27a7e333740b30af42c97a6d904109dd3493661388693a8b7c/diff:/var/lib/docker/overlay2/c17c4d467fa4eb6bbdc902d00e90e29ba41ba14e4a1e3398e1eca1367827c3e7/diff:/var/lib/docker/overlay2/b6a062693d1a7ad2470c022dff8debefee273ad67613fac2307adedd5bb96400/diff",
                "MergedDir": "/var/lib/docker/overlay2/f97bc7deb35a82820923a0cb122063fce7c55e8060efadfcc2eaf477e53f998c/merged",
                "UpperDir": "/var/lib/docker/overlay2/f97bc7deb35a82820923a0cb122063fce7c55e8060efadfcc2eaf477e53f998c/diff",
                "WorkDir": "/var/lib/docker/overlay2/f97bc7deb35a82820923a0cb122063fce7c55e8060efadfcc2eaf477e53f998c/work"
            },
            "Name": "overlay2"
        },
        "Mounts": [
            {
                "Type": "volume",
                "Name": "wordpress_dbdata",
                "Source": "/var/lib/docker/volumes/wordpress_dbdata/_data",
                "Destination": "/var/lib/mysql",
                "Driver": "local",
                "Mode": "rw",
                "RW": true,
                "Propagation": ""
            }
        ],
        "Config": {
            "Hostname": "1af8309100f0",
            "Domainname": "",
            "User": "",
            "AttachStdin": false,
            "AttachStdout": false,
            "AttachStderr": false,
            "ExposedPorts": {
                "3306/tcp": {},
                "33060/tcp": {}
            },
            "Tty": false,
            "OpenStdin": false,
            "StdinOnce": false,
            "Env": [
                "MYSQL_ROOT_PASSWORD=somewordpress",
                "MYSQL_DATABASE=wordpress",
                "MYSQL_USER=wordpress",
                "MYSQL_PASSWORD=wordpress",
                "PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin",
                "GOSU_VERSION=1.14",
                "MYSQL_MAJOR=5.7",
                "MYSQL_VERSION=5.7.39-1.el7",
                "MYSQL_SHELL_VERSION=8.0.30-1.el7"
            ],
            "Cmd": [
                "mysqld"
            ],
            "Image": "mysql:5.7",
            "Volumes": {
                "/var/lib/mysql": {}
            },
            "WorkingDir": "",
            "Entrypoint": [
                "docker-entrypoint.sh"
            ],
            "OnBuild": null,
            "Labels": {
                "com.docker.compose.config-hash": "e0974012ccca6ec7fad87419c6db0f615612b56b4e9afdbd20e5cb68d83a7677",
                "com.docker.compose.container-number": "1",
                "com.docker.compose.oneoff": "False",
                "com.docker.compose.project": "wordpress",
                "com.docker.compose.project.config_files": "docker-compose.yml",
                "com.docker.compose.project.working_dir": "/home/johnny/wordpress",
                "com.docker.compose.service": "db",
                "com.docker.compose.version": "1.25.0"
            }
        },
        "NetworkSettings": {
            "Bridge": "",
            "SandboxID": "2effc0b8d8727e112cf1234fdebef0810f770d7338f8ca28f03dabd90a08e8c8",
            "HairpinMode": false,
            "LinkLocalIPv6Address": "",
            "LinkLocalIPv6PrefixLen": 0,
            "Ports": {
                "3306/tcp": null,
                "33060/tcp": null
            },
            "SandboxKey": "/var/run/docker/netns/2effc0b8d872",
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
                "wordpress_default": {
                    "IPAMConfig": null,
                    "Links": null,
                    "Aliases": [
                        "db",
                        "1af8309100f0"
                    ],
                    "NetworkID": "7efa43057b2aa0caa8fe0b948feae66639e59eb918a1c07a14b30862bde0e66c",
                    "EndpointID": "4d0a598aabd213056dbbbf312e9d7009adbf091a2ff1bf6e510f66f7f4590f27",
                    "Gateway": "172.18.0.1",
                    "IPAddress": "172.18.0.2",
                    "IPPrefixLen": 16,
                    "IPv6Gateway": "",
                    "GlobalIPv6Address": "",
                    "GlobalIPv6PrefixLen": 0,
                    "MacAddress": "02:42:ac:12:00:02",
                    "DriverOpts": null
                }
            }
        }
    }
]


  # "docker network inspect wordpress_default" :


[
    {
        "Name": "wordpress_default",
        "Id": "7efa43057b2aa0caa8fe0b948feae66639e59eb918a1c07a14b30862bde0e66c",
        "Created": "2022-09-15T11:55:24.427522597Z",
        "Scope": "local",
        "Driver": "bridge",
        "EnableIPv6": false,
        "IPAM": {
            "Driver": "default",
            "Options": null,
            "Config": [
                {
                    "Subnet": "172.18.0.0/16",
                    "Gateway": "172.18.0.1"
                }
            ]
        },
        "Internal": false,
        "Attachable": true,
        "Ingress": false,
        "ConfigFrom": {
            "Network": ""
        },
        "ConfigOnly": false,
        "Containers": {
            "1af8309100f09bf63c336a5617208b3dac0bd755c0dc4387088566861575ec6b": {
                "Name": "wordpress_db_1",
                "EndpointID": "4d0a598aabd213056dbbbf312e9d7009adbf091a2ff1bf6e510f66f7f4590f27",
                "MacAddress": "02:42:ac:12:00:02",
                "IPv4Address": "172.18.0.2/16",
                "IPv6Address": ""
            },
            "2ea04b2c148ae6b940a87e50be9f89100a12ce314919c7e658e6a31cef0baf02": {
                "Name": "wordpress_wordpress_1",
                "EndpointID": "753d5def16b7ef6a293cc71ea86593cae60599d1fcf1a68116cb386a4d25992a",
                "MacAddress": "02:42:ac:12:00:04",
                "IPv4Address": "172.18.0.4/16",
                "IPv6Address": ""
            },
            "e82c12dcab46bac83a278d14087b550adcb61891b84e6a773e239e7431b10866": {
                "Name": "swag",
                "EndpointID": "a2bb74d0e3fe37a736a4b8ba258af055b85ef9c47395641a751cccb2219978fe",
                "MacAddress": "02:42:ac:12:00:03",
                "IPv4Address": "172.18.0.3/16",
                "IPv6Address": ""
            }
        },
        "Options": {},
        "Labels": {
            "com.docker.compose.network": "default",
            "com.docker.compose.project": "wordpress",
            "com.docker.compose.version": "1.25.0"
        }
    }
]