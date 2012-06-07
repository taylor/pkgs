pkgs
====


git clone https://github.com/taylor/pkgs.git

## Local repo setup

#### ubuntu

 * cd pkgs
 * echo "deb file://$(pwd)/ubuntu precise ."  | sudo tee -a /etc/apt/sources.list.d/localpkgs.list
 * sudo aptitude udpate

which will give you something like

```deb file:///home/taylor/pkgs/ubuntu/ precise .```

