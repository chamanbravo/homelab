<h1 align="center">
  Homelab
</h1>

<p align="center">
  <a href="https://github.com/k8s-at-home" alt="Image used with permission from k8s-at-home"><img alt="Image used with permission from k8s-at-home" src="https://avatars.githubusercontent.com/u/61287648" /></a>
</p>

<p align="center">
  <a href="https://k3s.io/">
    <img alt="k3s" src="https://img.shields.io/badge/k3s-v1.34.1-orange?logo=kubernetes&logoColor=white&style=flat-square">
  </a>
  <a href="https://github.com/adityathebe/homelab/commits/master">
    <img alt="GitHub Last Commit" src="https://img.shields.io/github/last-commit/chamanbravo/homelab?logo=git&logoColor=white&color=purple&style=flat-square">
  </a>
</p>

<p align="center">
Using GitOps principals and workflow to manage a lightweight <a href="https://k3s.io">k3s</a> cluster.
</p>

## Overview

This is a mono repository for my home infrastructure and Kubernetes cluster with the goal to learn and experiment.

## Stack

### Core

The core components of the cluster

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/k3s.svg"></td>
        <td><a href="https://k3s.io/">K3s</a></td>
        <td>Lightweight Kubernetes</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/helm.svg"></td>
        <td><a href="https://helm.sh/">Helm</a></td>
        <td>The package manager for Kubernetes</td>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/loganmarchione/svg-assets/main/assets/fluxcd.svg"></td>
        <td><a href="https://fluxcd.io/">Flux CD</a></td>
        <td>Continuous delivery solutions for Kubernetes </td>
    </tr>
</table>

### `cluster/apps`

The applications that run in my homelab (listed in alphabetical order)

<table>
    <tr>
        <th>Logo</th>
        <th>Name</th>
        <th>Description</th>
    </tr>
    <tr>
        <td><img vertical-align=baseline width="32" src="https://raw.githubusercontent.com/chamanbravo/upstat/main/docs/assets/upstat.png"></td>
        <td><a href="https://github.com/chamanbravo/upstat">Upstat</a></td>
        <td>Status monitoring tool</td>
    </tr>
</table>
