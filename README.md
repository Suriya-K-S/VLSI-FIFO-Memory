# FIFO Memory Using Verilog HDL

## Project Overview

This project implements an 8-bit FIFO (First In First Out) Memory using Verilog HDL.

The design supports synchronous write and read operations with FULL and EMPTY status flags.

## FIFO Principle

First In → First Out

Example:

Write: A, B, C, D

Read: A, B, C, D

## Features

* 8-bit Data Width
* 8-Location Memory Depth
* Write Enable Control
* Read Enable Control
* FULL Flag
* EMPTY Flag

## Architecture

Memory Array

Write Pointer

Read Pointer

Counter

FULL / EMPTY Detection

## Inputs

| Signal       | Description  |
| ------------ | ------------ |
| clk          | Clock        |
| rst          | Reset        |
| wr_en        | Write Enable |
| rd_en        | Read Enable  |
| data_in[7:0] | Input Data   |

## Outputs

| Signal        | Description     |
| ------------- | --------------- |
| data_out[7:0] | Output Data     |
| full          | FIFO Full Flag  |
| empty         | FIFO Empty Flag |

## Concepts Used

* Memory Design
* Sequential Logic
* Read Pointer
* Write Pointer
* FIFO Architecture

## Tools Used

* Verilog HDL
* Icarus Verilog
* VS Code
* GitHub

## Project Structure

RTL/
└── fifo.v

TB/
└── fifo_tb.v

## Author

Suriya K S

Electronics and Communication Engineering

Government College of Engineering, Erode
