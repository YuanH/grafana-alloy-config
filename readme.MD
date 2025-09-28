# Grafana Alloy Config

This repository contains configuration files for [Grafana Alloy](https://grafana.com/docs/alloy/latest/), a lightweight, multi-function telemetry collector.

## Features

- Centralized configuration management for Alloy
- Easy integration with Grafana and other observability tools
- Modular and customizable setup

## Getting Started

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yuan/grafana-alloy-config.git
    ```

2. **Review the configuration:**
    - All configuration files are located in the `@config.alloy` directory.
    - Edit the files to match your environment and requirements.

    ```bash
    ETC_DIR="$(brew --prefix)/etc/grafana-alloy"                                   
    mkdir -p "$ETC_DIR"
    ln -sf /Users/yuanhuang/repo/grafana-alloy-config/config.alloy "$ETC_DIR/config.alloy"
    ```

3. **Apply the configuration:**
    - Follow the [Grafana Alloy documentation](https://grafana.com/docs/alloy/latest/configuration/) to deploy the configuration.

`brew services restart grafana-alloy`
