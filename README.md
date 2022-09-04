# Budget PWA

## Description
This is a progressive web app allowing for mobile use as well as offline use that will resynch when connection is returned. This is accomplished using an express server, indexDB for local storage, and service workers to reroute offline requests, pull cached assets, and upload data when connection returns.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)

## Installation

The app is easy to deploy as express is the only package requiring installation, along with a mongodb server. The app can be installed just as any other PWA would be.

## Usage
The app essentially works as a checkbook. Enter in a transaction's value and name, and then select if you would like to add or subtract this amount of funds. When offline, you can still enter transactions although you will not be able to see your total. A graph will appearing showing account balance over time.

## Links
https://floating-crag-02351.herokuapp.com/
https://github.com/FredElick/pwa