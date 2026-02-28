# GitHub Pages Deployment with GitHub Actions

This project demonstrates a simple Continuous Integration and Continuous Deployment (CI/CD) pipeline using **GitHub Actions** to deploy a static website to **GitHub Pages**.

## Project Overview

- The repository contains a static `index.html` file.
- A GitHub Actions workflow automatically deploys the site to GitHub Pages.
- The workflow is triggered **only when `index.html` is changed** and pushed to the `main` branch.

This project is intended to help understand the fundamentals of CI/CD and automated deployments.

## How It Works

1. The `index.html` file is edited locally.
2. Changes are committed and pushed to the `main` branch.
3. GitHub Actions detects the change to `index.html`.
4. The workflow packages the site files and deploys them to GitHub Pages.
5. The updated website becomes live automatically.

## Live Website

The deployed website can be accessed at:
