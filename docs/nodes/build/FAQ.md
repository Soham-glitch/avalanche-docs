# Frequently Asked Questions

## Introduction

If you experience any issues building your node, here are some common errors and possible solutions.

### Error: `WARN node/node.go:291 failed to connect to bootstrap nodes`

This error can occur when the node doesn't have access to the Internet or if the NodeID 
is already being used by a different node in the network. This can occur when an old instance
is running and not terminated.

### Error: `err="cannot query unfinalized data"`

There may be a number of reasons for this issue, but it is likely that the node is not 
connected properly to other validators, which is usually caused by networking 
misconfiguration (wrong public IP, closed p2p port 9651).
