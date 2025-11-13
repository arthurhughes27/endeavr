# Multivariate normal distribution probability density function compute the value of the density of a multivariate normal distribution on at n points.

Multivariate normal distribution probability density function compute
the value of the density of a multivariate normal distribution on at n
points.

## Usage

``` r
mvnpdf(x, mean = rep(0, nrow(x)), varcovM = diag(nrow(x)), Log = TRUE)

mvnpdfoptim(x, mean = rep(0, nrow(x)), varcovM = diag(nrow(x)), Log = TRUE)

mvnpdfsmart(x, mean = rep(0, nrow(x)), varcovM = diag(nrow(x)), Log = TRUE)
```

## Arguments

- x:

  a matrix, with n columns (the observations) and p rows

- mean:

  a vector of means

- varcovM:

  a variance-covariance matrix

- Log:

  a logical parameter, zith default TRUE, which takes the log of the pdf

## Value

Returns a list containing the matrix x, and a vector of length n of the
multivariate normal distribution density values at those points
