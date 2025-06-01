# Contributing

This document is here to help those interested in contributing get their bearings.

## Repository Layout

- /firefox - firefox extension for jazz midi
- /media - unknown, TODO: unknown ask @jazz-soft
- /midi - platform specific implementations of CMidi
- /native - this looks like a cli tool wrapper around CMidi, TODO: ask @jazz-soft to clarify
- /node - this is the node.js package published to NPM. the node.js module binaries are embedded in the package for distribution.
- /node-gyp - this is the node.js module code, the output is put in /node/bin/{platform}/jazz.node
- /safari - safari integration
