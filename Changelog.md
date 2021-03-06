# Changelog

## 0.0.5

 * blas: documentation
 * ops_inplace: high level interface for the most important BLAS functions
 * regression: trait to create a design matrix
 * matrix: 
   * PartialEq and Eq for matrices
   * derive from Debug
   * from_col_vectors
   * from_row_vectors
   * implement the trait Similar for vectors
 * datasets: struct to create normal distributed data
 * more documentation
 * nn: module for neural networks
 * vector: 
   * trait to append a vector to another one
   * trait to select indexes from a vector
   * create vector via from_value
   * trait VectorIO
 * fixed some warning introduced by Rust 1.3

## 0.0.4

 * hash::{simple_hash}: Computes a very simple hash over a bytes.
 * pipeline: Set of utilities and scripts to create pipelines for machine learning tasks.
 * io::{match_lines_stdin, match_lines, MatchLines}
 * sliding::{string_slider, byte_slider, StringSlider, ByteSlider}
 * opt: module for optimization problems with an implementation of gradient descent
 * octave: module to run scripts with octave
 * ops: matrix vector multiplication with BLAS
 * regression: new module for linear regression
 * matrix: insert column

## 0.0.3

 * module `ops`
   * matrix-scalar, matrix-vector, vector-vector, etc operations
 * module `ops_inplace`
   * operations on matrices and vectors inplace
 * OpenCV integration
 * Point2D
 * DBSCAN clustering algorithm
 * multidimensional sliding windows

## 0.0.2

 * more documentation and examples
 * module `matrix`
   * implementation of trait Clone for `Matrix`
   * multiply `Matrix` with a scalar
   * add a scalar to a `Matrix`
 * module `vectors`
   * multiply vector with a scalar
   * add a scalar to a vector
 * module `gaussian` to estimate the parameters of a gaussian distribution from a set of samples

## 0.0.1

 * inital version
