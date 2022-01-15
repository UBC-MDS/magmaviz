# magmaviz

Exploratory Data Analysis is one of the key steps in a machine learning project. This package aims to make this process easy by providing python functions based on the Altair package to plot four common types of plots with the 'magma' color theme. To maximize interpretability, the plots have defined color schemes (discrete, diverging, sequential) based on the kind of data they show.

## Functions

The four data visualization functions included in the package are outlined below:

### Boxplot

Returns a boxplot based on the data frame, a numerical feature to view the distribution of and a categorical feature to bucket data into categories. Additionally, there is a boolean option to facet the boxplots into separate charts.

### Correlation Plot

Returns a correlation plot based on the numerical features present in the data frame. While the default plot would use circle shapes, an auxiliary input provides the flexibility to switch to square shapes. Additionally, it will print the correlated numerical feature pairs along with their correlation values.

### Histogram

Returns a histogram based on the data frame and a categorical feature to plot on the x-axis. The y-axis will display the count of records.

### Scatterplot

Returns a scatterplot based on the data frame and two numerical feature names passed as the required inputs. An auxiliary input provides the flexibility to color-code the data points based on a categorical feature.

## Installation

```bash
$ pip install magmaviz
```

## Usage

- TODO

## Contributing

The primary contributors to this package are:

1. Abdul Moid Mohammed
2. Mukund Iyer
3. Irene Yan
4. Rubén De la Garza Macías

We welcome new ideas and contributions. Please refer to the contributing guidelines in the CONTRIBUTING.MD file. Do note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`magmaviz` was created by Abdul Moid Mohammed, Mukund Iyer, Irene Yan, Rubén De la Garza Macías. It is licensed under the terms of the MIT license.

## Credits

`magmaviz` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
