---
author: Edson Ayllon
category: functionality
tags:
- ipfs
- react
status: complete
twitter: https://twitter.com/relativeread
---

## Modular 22-2019

# IPFSjs with html file

Alternate ipfs.js implementation using an externally held ipfs.js library instead of npm component. Meant to reduce size of final build. 

## 1. Description

Creats an IPFS peer to peer instance before the React app fully loads by inserting into `./client/public/index.html`.

![Screenshot](./Screenshot_7.jpg)

## 2. Getting Started

### 2.1 Install

Install dependencies for the React Client.

```
cd client
yarn || npm install
```


### 2.2 Run

Run the client. In `./client`:

```
yarn start || npm run start
```
