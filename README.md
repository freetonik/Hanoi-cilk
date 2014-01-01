Hanoi-cilk
==========

Hanoi towers using Cilk

To compile:

cilk++ hanoi.cilk -O1 -g -lcilkutil -o hanoi

To run:

./cilk (optional)<number of disks>

e.g.: 

./cilk
runs with default number of disks = 3
 
./cilk 4
runs with 4 disks
