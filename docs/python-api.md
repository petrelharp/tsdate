---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.12
    jupytext_version: 1.9.1
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

:::{currentmodule} tsdate
:::

(sec_python_api)=

# Python API

This page provides formal documentation for the `tsdate` Python API.


## Running tsdate

```{eval-rst}
.. autofunction:: tsdate.date
```

## Prior and Time Discretisation Options

```{eval-rst}
.. autofunction:: tsdate.build_prior_grid

.. autoclass:: tsdate.base.NodeGridValues
```

## Variable population sizes

```{eval-rst}
.. autoclass:: tsdate.demography.PopulationSizeHistory
```

## Preprocessing Tree Sequences

```{eval-rst}
.. autofunction:: tsdate.preprocess_ts
```

# Functions for Inferring Tree Sequences with Historical Samples

```{eval-rst}
.. autofunction:: tsdate.sites_time_from_ts
.. autofunction:: tsdate.add_sampledata_times
```