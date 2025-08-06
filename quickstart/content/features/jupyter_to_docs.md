+++
title = 'Jupyter to Docs'
date = 2025-08-06T15:52:31-04:00
draft = false
+++

# Jupyter Notebook Integration

This page demonstrates embedding a Jupyter notebook directly into Hugo documentation.

## Sample Notebook

Below is the test notebook embedded using our custom shortcode:

{{< jupyter "test.ipynb" >}}

## How It Works

The notebook is rendered client-side using notebook.js, which parses the `.ipynb` file and converts it to HTML with pro