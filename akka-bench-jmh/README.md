# Akka Microbenchmarks

This subproject contains some microbenchmarks excercising key parts of Akka.

You can run them like:

   project akka-bench-jmh
   jmh:run -i 3 -wi 3 -f 1 .*ActorCreationBenchmark

Use 'jmh:run -h' to get an overview of the availabe options.
