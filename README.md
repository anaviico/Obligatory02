# Obligatory02
Obligatory assignment INF214-Concurrent programming UIB

#Task 1:

#part 1A

The printer could produce 6! different outputs, which is 720 outputs.

#part 1B

printer() {
  process P1 {P; write("1"); write("2"); V;}
  process P2 {P; write("3"); write("4"); V;}
  process P3 {P; write("5"); write("6"); V;}
}
