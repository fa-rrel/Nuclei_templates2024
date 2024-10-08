<h1 align="center">
Custom Nuclei Templates
</h1>
<h4 align="center">A community-curated list of templates for the Nuclei engine to find security vulnerabilities in applications.</h4>

<p align="center">
<a href="https://github.com/fa-rrel/Nuclei_templates2024/issues"><img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat"></a>
<a href="https://github.com/fa-rrel/Nuclei_templates2024/releases"><img src="https://img.shields.io/github/v/release/fa-rrel/Nuclei_templates2024.svg"></a>
</p>

## Introduction

This repository contains custom Nuclei templates that can be used to identify various security vulnerabilities in web applications. The templates are written in YAML format and can be easily integrated into your security testing workflows.

## Getting Started

To use these templates, simply clone this repository and point Nuclei to the directory containing the `.yaml` files.

```bash
git clone https://github.com/fa-rrel/Nuclei_templates2024.git
cd Nuclei_templates2024
nuclei -t ./templates
