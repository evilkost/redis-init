## SUMMARY
Init script for run multi redis nodes with dedicated configs.

## Prerequisites
Installed redis-server and redis-cli binaries

## Setup
If you use debian, simple build and install package. Otherwise copy and rename
init script in compliance with your distribution.

## Configuration
Edit variables $CONFIG_DIR, $DAEMON, $REDIS_CLI according to your setup.

## Usage
1. Run one node
    sudo /etc/init.d/redis-init start foo
2. Run all nodes
    sudo /etc/init.d/redis-init start
3. Stop one node
    sudo /etc/init.d/redis-init stop foo
4.  Stop all nodes
    sudo /etc/init.d/redis-init stop all
