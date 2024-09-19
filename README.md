# Astro CloudCannon Monorepo Demo

Demonstrating how to set up a monorepo of two Astro sites in CloudCannon.

## Site One build config

### Command Line Options

Install Command: `cd site-one && npm install`

Build Command: `cd site-one && npm run build`

Output Path: `site-one/dist`

### Environment Variables

`CLOUDCANNON_CONFIG_PATH=site-one/cloudcannon.config.yml`

`SITE_DIR=site-one`

## Site Two build config

### Command Line Options

Install Command: `cd site-two && npm install`

Build Command: `cd site-two && npm run build`

Output Path: `site-two/dist`

### Environment Variables

`CLOUDCANNON_CONFIG_PATH=site-two/cloudcannon.config.yml`

`SITE_DIR=site-two`
